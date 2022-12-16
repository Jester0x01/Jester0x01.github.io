---
title: Bypassing Twitter's mastodon censorship using zero width space trick
author: Jester0x01
date: 2022-12-16
categories: [Websec]
tags: [writeup, unicode]

---

Today when I opened the Twitter app, saw my timeline filled with "Elon Musk is on rampage, he is blocking everyone" tweets.
Umm... Twitter drama of everyday...



and few seconds later noticed they have blocked all links of mastodon. 😐


I began searching if there is any bypass for this.

All of the bypass I found suggested 2 things:
1. use a url shortener link.
2. post urls with spaces or [.] instead of direct url.


 both solutions work but there is one problem.


> it is a pain to create short links and not having "clickable" links for mastodon. 😶


So, I started poking Twitter's url blocking implementation.

After 5 minutes of poking, I came to few conclusions:

1. Direct resolve of `mastodon url` is not allowed.
2. `mastodon url` preview is enabled but tweet posting is not allowed.
3. using url bypasses and tricks are making `mastodon url` not directly resolvable.

With this in mind, i started thinking of possible bypasses.


The first thing I tried was this trick I learned recently: ZERO WIDTH SPACE

> The zero-width space is technically a space, but rendered with no width. You won't be able to see it.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">%e2%80%8b is the unicode zero width space. You can add that randomly to a host name in a URL and the URL still works.<a href="https://t.co/nPMaTpJmDS">https://t.co/nPMaTpJmDS</a> =&gt; goo%e2%80%<a href="https://t.co/PLToeogORn">https://t.co/PLToeogORn</a></p>&mdash; daniel:// stenberg:// (@bagder) <a href="https://twitter.com/bagder/status/1603376649055178752?ref_src=twsrc%5Etfw">December 15, 2022</a></blockquote> 



```
https://in%e2%80%8bfosec.exchange/@0
```

Well, this and it's payload variation didn't work because it triggered 3rd condition.


The second thing that came to mind was use open redirects. Unfortunately I didn't found any open redirects on twitter. So, I thought of using third party open redirects.

For those who don't know what open redirect is:

> An open redirect is where the redirected URL can be specified from outside the application and an arbitrary location can be provided. For example, in the URL goodexample.com/redir.php?q=badexample.com , the application redir.php is accepting the query string q=badexample.com and redirecting to badexample.com (from Fastly.com)


I quickly decided to go with
`http://testphp.vulnweb.com`. this is one  I remember by heart 🥹


```
http://testphp.vulnweb.com/redir.php?r=https://infosec.exchange/@0
```

And to my surprise it didn't work either, because it triggered the 2nd conclusion. 🥲

I tried many bypasses like "@" "/" "///@" etc.. but none of them worked.

After few minutes, I thought of focusing effort on indirect bypass instead of spending time on dealing with Twitter's implementation.


And finally the old tricks of town worked: using third party open redirect and zero width space trick.

```
http://testphp.vulnweb.com/redir.php?r=https://in%e2%80%8bfosec.exchange/@0
```



I am using zero width space (`%e2%80%8b`) in the middle of instance name. `in-bypasshere-fosec.exchange` because this way, it won't trigger any conditions I observed earlier. Other payload variations will work too.


This bypass should work for all sites blocked by Twitter. It also bypasses Twitter's url malware detection.

Here are few examples for mastodon instances.


Replace `your-username-here` with your mastodon instance's username.


### infosec.exchange

 `http://testphp.vulnweb.com/redir.php?r=https://in%e2%80%8bfosec.exchange/@your-username-here`

### mastodon.social


`http://testphp.vulnweb.com/redir.php?r=https://mast%e2%80%8bodon.social/@your-username-here`



------
here's link to my infosec.exchange profile 
`http://testphp.vulnweb.com/redir.php?r=https://in%e2%80%8bfosec.exchange/@0`

you can post this on twitter and see if it is resolvable or not. ;)




Connect with me here:
https://infosec.exchange/@0
https://twitter.com/jester0x01
