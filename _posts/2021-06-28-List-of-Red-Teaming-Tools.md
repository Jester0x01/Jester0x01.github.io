---
title: List of Red Teaming Tools
author: Jester0x01
date: 2021-06-28
categories: [Pentest]
tags: [tools, red-team]

---

 ### Map of Red Teaming Tools
 
```sh
├───AD
│   ├───ACLPwn
│   ├───ACL_PWN
│   ├───ADAPE
│   ├───ADAudit
│   ├───ADCollector
│   ├───ADpwn
│   ├───ADRecon
│   ├───ADReconPowershell
│   ├───AD_DomainSwevices_Script
│   ├───AD_LDAP_Enum
│   ├───AttackCheatSheet
│   ├───Auditscript
│   ├───Awesomeness
│   ├───Bloodhound
│   ├───BloodHoundPython
│   ├───CrackMapExec
│   ├───DomainEnumWithJavascript
│   ├───DSInternals
│   ├───DumpDNS
│   ├───GetVulnerableGPO
│   ├───Grouper
│   ├───InterestingRestore
│   ├───JoinLinuxToAD
│   ├───LDAPDomainDump
│   ├───LDAPper
│   ├───LDAP_Search
│   ├───ListDomains
│   ├───LogonHistory
│   ├───PrivEsc
│   ├───PythonEnumerateUsers
│   ├───QueryClearTextLDAPBinds
│   ├───SharpAdidnsdump
│   ├───SharpGPOAbuse
│   ├───SharpHound
│   └───WinLDAPSearch
├───ARP
│   ├───EavesARP
│   └───SwissLogger
├───AtomicRedTeam
├───Audit
│   └───Seatbelt
├───AutorunsToJson
├───Autosploit
├───A_CsharpSelfMorphing
├───Bandicam
├───Bash
├───BDFProxy
├───BeyondCompare
├───BinaryDiffingTools
│   ├───BinDiff
│   ├───DarunGrim4
│   └───Diaphora
├───BruteForce
│   ├───Blazy
│   ├───DomainPasswordSpray
│   ├───Openssl-bruteforce
│   └───THC-hydra-Windows
├───BufferOverflow
│   └───EggHunter
├───Burp
│   ├───ContentDiscovery
│   └───IpRotate
├───Bypass
│   ├───AMSI
│   │   ├───AmsiScanBypass
│   │   ├───Another
│   │   ├───GadgetToJscript
│   │   ├───MattAmsi
│   │   └───PSAMSI
│   ├───AppLocker
│   │   └───PowerAL
│   ├───AppWhiteListing
│   │   └───CscriptShell
│   ├───ASLR_DEP
│   │   └───PESecinfo
│   ├───AutoRunsDetection
│   ├───AV
│   │   ├───Arno0x
│   │   ├───AswCrypter
│   │   ├───AVET
│   │   ├───CactusTorch
│   │   ├───GreatSCT
│   │   ├───HerculesPayloadGenerator
│   │   ├───InceptionFramework
│   │   ├───KmzExample
│   │   ├───MsVenonCustomShellcodr
│   │   ├───ObfuscateCactusTorch
│   │   ├───OwaspZSC
│   │   ├───PayloadSplitting
│   │   ├───PyCloak
│   │   ├───ShellCodeWrapper
│   │   ├───Shellter
│   │   ├───SystemCallsFromVisuslStudio
│   │   ├───TikiTorch
│   │   ├───VeilEvasion
│   │   └───WithMSBuildAndShellCode
│   ├───CmdRestriction
│   ├───COM
│   ├───ConstrainedLanguageMode
│   │   └───PSBypassCLM
│   ├───DownloadAndExwcuteIdeas
│   ├───EDR
│   │   ├───WithINF
│   │   └───ZombieAnt
│   ├───Firewall
│   │   └───Firefox_Tunnell
│   ├───Logs
│   │   └───Log-killer
│   ├───MemoryScanning
│   │   └───Gargoyles
│   ├───MoveFilesFreelyIdea
│   ├───NAC
│   │   └───DelosCloak
│   ├───Proxy
│   │   ├───GimmeTheFile
│   │   └───Reqrypt
│   ├───Sysmon
│   ├───UAC
│   │   ├───ALPC-BypassUAC
│   │   ├───CSharpPlaintext
│   │   ├───PythonUac
│   │   ├───SilentCleanup
│   │   ├───UAC-Bypass
│   │   ├───UACMe
│   │   ├───UAC_bypass_windows_store
│   │   └───WithFolderTrickery
│   ├───WAF
│   │   ├───DNSHistoryWAFBypass
│   │   └───WhatWAF
│   └───WindowsDefender
│       └───Disable
├───C2
│   ├───BindShellBypassHostFirewallwithSMB
│   ├───ChaShell
│   ├───CobaltStrike
│   ├───Covenant
│   ├───DDoor
│   ├───Diagon
│   ├───DnsCat2
│   ├───DnsShell
│   ├───DockerDBC2
│   ├───DockerDNSCat
│   ├───DOHC2
│   ├───dropboxC2_DBC2
│   ├───External_c2_framework
│   ├───FudgeC2
│   ├───GCat
│   ├───Gorsh
│   ├───HRShell_httpShell
│   ├───ICMPSH
│   ├───ICMPTunnel
│   ├───ICMP_Tunnel_Python
│   ├───Invoke-PipeShell
│   ├───MacSwiftShell
│   ├───Merlin
│   ├───Nuages
│   ├───OneLogicalMyth_Shell
│   ├───Ping-Pwn
│   ├───PoshC2
│   ├───PowerCat
│   ├───PowerHub
│   ├───PowershellExample
│   ├───Prismatica
│   ├───Pupy
│   ├───RedPeanut
│   ├───ReUseExistingConnectionOneWayStager
│   ├───ReverseShellGen
│   ├───ReverseTCPEncrptedPowershell
│   ├───RSH
│   ├───SharpSocks
│   ├───SilentTrinity
│   ├───Slackor
│   ├───Throwback
│   ├───ThunderShell
│   ├───TinkerShell
│   ├───Tiny-SHell
│   ├───TrevorC2
│   ├───Tunna
│   ├───Udp2Raw
│   ├───UndetectableCSharpShell
│   ├───Websocket-Smuggle
│   ├───WebSocketC2
│   ├───WheresMyImplant
│   └───WinSpy
├───Calculator
├───Cars
│   ├───CANalyzator
│   └───CanZator
├───Certs
│   ├───CarbonCopy
│   ├───CertCheck
│   ├───CertExp
│   └───MkCert
├───Chrome
├───CIRCL_AIL_Framework
├───Cisco
│   └───CCat
├───C 
CallExe
│   │   ├───Katz
│   │   ├───LoadMethodScanner
│   │   ├───LoadsDotNETAssemblyIntoScriptHostFromCurrentPath
│   │   ├───LocalKernelDebugger
│   │   ├───MimikatzJS
│   │   ├───MimikatzSct
│   │   ├───MouseKeyLogger
│   │   ├───MsBuildLSAASProcessDump
│   │   ├───msbuildXSLTExecuteFromURL
│   │   ├───Neat
│   │   ├───NeatLittleTrick
│   │   ├───ObfuscatedXSL
│   │   ├───Powershell_Suite
│   │   ├───PoweshellWebshell
│   │   ├───ProcessCommandLineParameters
│   │   ├───RecommendReadingOnDotNet
│   │   ├───RemoteSCT
│   │   ├───ScareTheJitOuttaDefenders
│   │   ├───SCT
│   │   ├───Service
│   │   ├───ShellcodeJS
│   │   ├───ShellcodeStuffedIntoNumeric
│   │   ├───ShellcodeViaXSL
│   │   ├───SubTeeBackupFromSomeone
│   │   ├───SyscallExtractNtDll
│   │   ├───Tasks
│   │   ├───TLSC2
│   │   ├───WMIKatz
│   │   ├───Workflow
│   │   └───XML
│   └───Vysec
│       ├───Cactus
│       ├───RDPInception
│       └───Sharpshooter
├───Hooking
│   └───InfinityHook
├───Hunter
├───ICACLS
├───IIS_LogParser
├───Image
│   ├───BinaryImageWitbPayload
│   └───InvokePsImage
├───InMemoryPowershellWebDavServer
├───Interesting
│   ├───CopyNetCatByteByByte
│   ├───CrlInject
│   ├───FirstBite
│   ├───Hmm
│   ├───MarkBaggett
│   ├───Msf-Autoshell
│   ├───Narsil_SpyAgencyTeasing
│   ├───PandorasBox
│   ├───Sheepl
│   └───WebTTY
├───InterviewQuestions
├───IOC
│   ├───Fenrir
│   └───LOKI
│       └───Install
├───IOT
│   └───DNSRebind
├───IPhoneTesting
│   └───IGoat
├───IPv6
│   ├───Enyx_SNMP_IPV6_Enum
│   ├───IPv6_checker
│   ├───PythonNmap
│   └───TermColor
├───Java
│   ├───Barmie_java_RMI_test
│   ├───JavaScriptDeserialization
│   │   └───GadgetInspector
│   └───New folder
├───Javascript
│   ├───HermesJavaScriptEngine
│   ├───NodeJSSimpleHttpServer
│   └───SimpleSerialize
├───Jenkins
│   ├───Jenkins-Pillage
│   └───JenkinsPasswordSpray
├───JSDotNet
├───JSON
│   ├───JQ_ToMakeJSON_EASY
│   ├───JWTCrack
│   ├───JWT_Attack_Playbook
│   ├───JWT_Toolkit
│   └───The JSON Web Token Toolkit
├───Kalitorify
├───Kerberoasting
├───Keylogger
│   ├───PowershellKeylogger
│   └───SpyKeogger
├───KeyStone
├───LABS
│   ├───EquationGroup
│   └───PurpleLabs
│       └───DanderSpritz Lab
├───LAPS
│   └───LapsToolkit
├───Laptop
├───LateralMovement
│   ├───Invoke-SocksProxy
│   ├───LethalHTA
│   ├───SCShell
│   ├───SharpExec
│   ├───SocatForWindows
│   ├───SSHuttle
│   └───WMISploit
├───LeakScraper
├───Linux
│   ├───DirtyCow
│   ├───FindCredentials
│   ├───FireWalker
│   ├───GetKerberos-KeyTab
│   ├───Hardening
│   │   ├───LinuxHardeningChecklist
│   │   └───Lynis
│   ├───LinEnum
│   ├───LinuxFirewalls
│   ├───LinuxKernalExploits
│   ├───LinuxSwapDigger
│   ├───Linux_rootkit_example
│   └───MaSSH-Enum
├───LOL
│   ├───CMDs
│   │   ├───Appvlp
│   │   ├───AT
│   │   ├───ATBroker
│   │   ├───Bash
│   │   ├───Bginfo
│   │   ├───BitsAdmin
│   │   ├───Cdb
│   │   ├───CertUtil
│   │   ├───CL_Invocation
│   │   ├───CL_Mutexverifiers
│   │   ├───CMD
│   │   ├───CMDKey
│   │   ├───Cmstp
│   │   ├───Comsvcs
│   │   ├───Control
│   │   ├───Csc
│   │   ├───Cscript
│   │   ├───csi
│   │   ├───Devtoolslauncher
│   │   ├───Dfsvc
│   │   ├───Diskshadow
│   │   ├───Dnscmd
│   │   ├───dnx
│   │   ├───Dxcap
│   │   ├───Esentutl
│   │   ├───Eventvwr
│   │   ├───Excel
│   │   ├───Expand
│   │   ├───Extexport
│   │   ├───Extrac32
│   │   ├───Findstr
│   │   ├───Forfiles
│   │   ├───Ftp
│   │   ├───Gpscript
│   │   ├───Hh
│   │   ├───Ie4uinit
│   │   ├───Ieadvpack
│   │   ├───Ieaframe
│   │   ├───Ieexec
│   │   ├───Infdefaultinstall
│   │   ├───Installutil
│   │   ├───Jsc
│   │   ├───Makecab
│   │   ├───Manage-bde
│   │   ├───Mavinject
│   │   ├───Mftrace
│   │   ├───Microsoft.Workflow.Compiler
│   │   ├───Mmc
│   │   ├───Msbuild
│   │   ├───Msconfig
│   │   ├───Msdeploy
│   │   ├───Msdt
│   │   ├───Mshta
│   │   ├───Mshtml
│   │   ├───Msiexec
│   │   ├───msxsl
│   │   ├───New folder
│   │   ├───New folder (2)
│   │   ├───Odbcconf
│   │   ├───Pcalua
│   │   ├───Pcwrun
│   │   ├───Pcwutl
│   │   ├───Pester
│   │   ├───Powerpnt
│   │   ├───Presentationhost
│   │   ├───Print
│   │   ├───Pubprn
│   │ 
e
│   ├───TheFatRat
│   ├───WhereMyImplantSharpWMI
│   ├───WMI_Implant
│   └───WPadPersistence
├───PETools
│   ├───ImmunityDebugger
│   ├───LordPE
│   ├───Stud_PE
│   └───XVI32
├───Phishing
│   ├───BlackEye
│   ├───GoPhishAndLetsEncrypt
│   ├───Modlishka
│   └───Phishery_BasicAuthCapture
├───PingCastle
│   └───pingcastle-master
│       ├───ADWS
│       ├───Data
│       ├───Graph
│       │   ├───Database
│       │   ├───Export
│       │   ├───Reporting
│       │   └───Rules
│       ├───Healthcheck
│       │   └───Rules
│       ├───misc
│       ├───Properties
│       ├───Report
│       ├───RPC
│       ├───Rules
│       ├───Scanners
│       ├───shares
│       └───template
├───Piper
├───PocketBeagle
├───PortForward
│   └───PSPortForward
├───PortScanning
│   └───agile-hacking
├───PostExploit
│   ├───DarkSpiritz
│   ├───GoodList
│   ├───Nishang
│   ├───ObfuscatedEmpire
│   ├───Orc
│   ├───SharpSploit
│   └───SilentTrinity
├───PowerOpsFDiskYou
├───Powershell
│   ├───CreateCSharpObject
│   ├───CreateExeFromPs1
│   ├───CSharpInPowershell
│   ├───ExecuteAsLoggedInUser
│   ├───FIndAllDomainComputers
│   ├───FindFruitAndMore
│   ├───FlorianRoth
│   ├───GeneralSecurityScript
│   │   └───Misc-Powershell-Scripts-master
│   ├───GetAllMacAddresses
│   ├───Harmj0yPowerUp
│   │   └───PowerSploit
│   ├───InsecurePowershell
│   ├───InsecurePowershellHost
│   ├───Install
│   │   └───Server2003
│   ├───Kmkz
│   ├───NetworkSecurity
│   ├───NoPowerShell
│   ├───Obfuscation
│   │   └───Invoke-Obfuscation
│   ├───P0wnedshell
│   ├───Piper
│   ├───PostExploit
│   │   ├───LogRM
│   │   └───Windows
│   ├───PowerAvails
│   ├───Powermad
│   ├───PowerMemory_GetMemoryCreds
│   ├───PowerOps
│   ├───PowerShdll
│   ├───PowershellArsenal
│   ├───PowershellBasicAuth
│   ├───PowershellFilelessAttacks
│   ├───PowershellGeneral
│   │   ├───JsonParse
│   │   ├───OffensivePowershell
│   │   └───SplitString
│   ├───PowershellInMemoryMagicUnicorn
│   ├───PowershellReverseShell
│   ├───PowershellScripts
│   │   ├───ADEverything
│   │   ├───CheckIfCredentialGuardIsEnabled
│   │   ├───GetAuthenticodes
│   │   ├───GetLoggedOnUsers
│   │   ├───GetShellContent
│   │   ├───Misc-Powershell-Scripts-master
│   │   └───MiscScripts
│   ├───PowershellToExe
│   │   └───GUI
│   ├───PowershellVeryLess
│   ├───PowerSploit
│   ├───PowerThief
│   ├───PowerTools
│   ├───PSKernel-Primitives
│   ├───RedTeamPowershellScripts
│   │   └───RedTeamPowershellScripts-master
│   │       └───scripts
│   ├───SelfEleveating
│   ├───Set-TokenPriv
│   ├───SMBScannerFromPingCastle
│   └───WithoutPowershell
│       ├───PowerlessShell
│       ├───Powershdll
│       ├───PowerShellAsCSharpScript
│       └───READTHIS
├───Powersploit
├───Precompiled_exploits
│   ├───KernelExploits
│   └───WindowsExploits
├───Printer
│   ├───PRET
│   └───Pretty
├───PrivEscalation
│   ├───ExploitPacks
│   │   ├───AusJock_PrivEscalation1
│   │   ├───WHP_WindowsHackingPack
│   │   ├───WindowsKernelExploits
│   │   └───www_bhafsec_com
│   ├───Linux
│   │   ├───BeRoot
│   │   ├───Capabilities
│   │   ├───CreateShadowFilePassword
│   │   ├───DirtySock
│   │   ├───Enum4Linux
│   │   ├───FSudo
│   │   ├───LinEnum
│   │   ├───LinPwn
│   │   ├───LinuxExploitSuggester
│   │   ├───LinuxPrivChecker
│   │   ├───Orc
│   │   ├───PerlLinuxExploitSuggester
│   │   ├───RootOS
│   │   ├───SudoKiller
│   │   ├───UpTux
│   │   └───Yodo
│   ├───Universal
│   │   └───Privledge-Escalation
│   └───Windows
│       ├───5WaystoFindSystemsRunningDomainAdminProcesses
│       ├───AlwaysInstallElevated
│       ├───BAD_BACKUP_OPERATORS
│       ├───BatchFilePriveEsc
│       ├───CapcomDriverSigning
│       ├───ConstrainedDelegation
│       ├───CREATE_TOKEN_EXAMPLE
│       ├───DllHijacking
│       ├───DLLInjection
│       ├───EasySystem
│       ├───Elevate
│       │   ├───Elevate
│       │   ├───elevate-master
│       ├───Enable_ALL_TOKEN_PERMISSIONS
│       │   └───Set-TokenPriv
│       ├───exploitSuggesterPY
│       ├───FindSystemsRunningDomainAdminProcesses
│       ├───GetSystem
│       │   ├───GetSystemPowershell
│       │   ├───Invoke_potato
│       │   └─ 
├───Volatility
├───VPN
│   └───Pulse
├───VulnLdap
├───VulnScanning
│   ├───Vulmap
│   └───VulnersNmapScanForServices
├───WebTesting
│   ├───AEMHackerToolset
│   ├───AnonymousHTTPGetRequests
│   ├───Apache
│   │   └───Struts
│   ├───Arjun_FindHiddenParameters
│   ├───BlackWidow
│   ├───BuiltWith
│   │   └───Webtech
│   ├───BurpSuite
│   ├───Captcha
│   │   ├───Uncaptcha
│   │   └───Uncaptcha2
│   ├───CMS
│   │   └───CMSSeek
│   ├───CookieMonster
│   ├───CORS
│   │   └───CORScanner
│   ├───Deserialization
│   │   ├───DeserializationTester
│   │   ├───YSoSerial
│   │   └───YSoSerialDotNet
│   ├───DirectoryBruteForce
│   │   └───DirHunt
│   ├───GoBuster
│   │   └───RecursiveGobuster
│   ├───HTA
│   │   └───SimpleCommandRunnsr
│   ├───LFIFreak
│   ├───NoSQLMap
│   ├───PayloadAllTheThings
│   ├───RelativeURLExtractor
│   ├───RestAPI
│   │   └───ASTRA_RestAPI_testing
│   ├───ShellShockFinder
│   ├───SSRF
│   │   └───GopherUS
│   ├───TemplateInjection
│   │   └───TPLMap
│   ├───Upload
│   │   └───FUXploider
│   ├───ViewGen
│   ├───WebAutoPwn_int0x33
│   ├───WebCrawlerExtraction_Photon
│   ├───WebInformationGarhering(WIG)
│   ├───Webshells
│   │   ├───404NotFoundWebShell
│   │   ├───Asp
│   │   │   └───CallHome
│   │   ├───HTShells
│   │   ├───Jsp
│   │   ├───Php
│   │   │   └───WindowsPHPReverseShell
│   │   ├───SharPyShell_encrypted
│   │   ├───Subshell
│   │   └───TennC
│   ├───WitnessMe
│   ├───XSS
│   │   ├───PopCalcNotAlert
│   │   ├───XsScrapy
│   │   ├───XssPayloads
│   │   └───XssStrike
│   ├───XXE
│   │   └───DTDFinder
│   └───ZAP
├───Windows10CustomKernelSigners
├───WindowsDesiredState
├───WindowsHardening
│   ├───DetectExploit
│   ├───FIrewall
│   ├───HardeningAuditor-master
│   ├───MSCT
│   ├───Osmedeus
│   ├───ReduceAttackSurface
│   ├───WinSpect
│   └───WUA_OFFLINE
├───WinPayloads
├───WinPwnage
├───WinRM
│   └───EvilWinRM
├───Wireless
│   ├───Bluetooth
│   │   ├───Jackit
│   │   └───Sniffle
│   ├───SDR
│   └───WiFi
│       ├───PiDense
│       ├───PiKarma
│       ├───PiSavar
│       ├───WifiCrack
│       └───Wifite2
├───WMI
│   ├───InvokeWMILm
│   ├───Persistence_script
│   ├───SharpWMI
│   └───Windapsearch
├───WSUS_WindowsServerUpdateService
│   ├───ThunderWoosusCSharp
│   └───WSUSpendu
└───XORFusvator 
──PSGetSystem
│       ├───GoldenTicket
│       ├───HotPotato
│       ├───InsecureRegistrySettings
│       ├───Install_Service_To_launch_System
│       ├───Invoke-Potato
│       ├───Invoke_Potato
│       ├───Jaws
│       │   └───JAWS-master
│       ├───JuicyPotato
│       ├───LonelyPotato
│       ├───MigrateProcess
│       ├───NAMED_PIPE_IMPERSONATION
│       ├───Potato
│       ├───Powerless
│       ├───PowerUp
│       │   ├───PowerUp-master
│       │   └───Privesc
│       ├───PrivEsc
│       ├───PrivExchange
│       ├───PSGetSystem
│       ├───PywerView
│       ├───RemoteDLLInjector
│       ├───RottonPotato
│       ├───RottonPotatoNG
│       ├───RottonPotatoNG_correct
│       ├───RunAs
│       ├───Seatbelt
│       │   └───CompiledDotNet4
│       ├───SecondaryLogonHandle
│       ├───SelfElevatingPowershell
│       ├───ServicePermissions
│       ├───SessionGopher
│       │   └───SessionGopher-master
│       ├───Set-TokenPermissions
│       ├───SharpUp
│       │   └───MyBinary
│       ├───Sherlock
│       │   └───Sherlock-master
│       ├───SluiFileHandlerHijackLPE
│       ├───SmashedPotato
│       ├───SysRet
│       ├───Tater
│       ├───TokenPrivModification
│       │   └───SetManually
│       ├───Tokenvator
│       ├───tokenx_privEsc
│       ├───UnquotedServicePaths
│       ├───Watson
│       ├───WESNG
│       ├───WindowPrivEscCheck
│       ├───WindowsExploitSuggester
│       │   └───Windows-Exploit-Suggester-master
│       └───WinEnumPowershell
│           └───WindowsEnum-master
├───ProcessHacker
│   └───PlugIns
├───ProcessInjection
│   ├───GenericProcessInjection
│   ├───PinJectra
│   ├───ProcessInjection_tool
│   ├───PSInject
│   └───RunAs
├───ProxyInfectFilesOnTheFly
├───ProxyPortForwarding
│   ├───Invoke-SocksProxy
│   ├───InvokeSocksProxy
│   └───Piper
├───PSEXEC
│   ├───CSharpPSExec
│   └───ReflectivePSEXEC
├───PsExecViaReflectiveDLL
├───Python
│   ├───BasicScripts
│   │   ├───FTPFuzz
│   │   ├───LearningPython
│   │   ├───NameMash
│   │   ├───SimpleWordPressBruteForce
│   │   └───WebCrawler
│   ├───Oneline
│   │   ├───One-Lin3r
│   │   └───OneLineIzer
│   ├───pcode2code_VBA_Decomiler
│   ├───Py2exe
│   │   ├───Dependancy
│   │   ├───Python2
│   │   ├───Python3
│   │   │   └───WindowsInstaller
│   │   └───Tutorial
│   ├───PyEmbed
│   ├───Pyinstaller
│   ├───pyminifier
│   ├───PyOxidizer
│   ├───Python2.7
│   ├───PythonDotNetBinaryFormat
│   ├───PythonPortScan
│   ├───PythonRegistry
│   ├───PythonToWinExe
│   ├───RTFM_PY
│   └───SMBDoor
├───Rapid7Scans
├───RaspberryPI
│   └───RPI-Hunter
├───RDP
│   ├───RDPPy
│   └───RDP_Caching
├───ReaCom
│   ├───DLLCLSID
│   ├───ExplorerEXEComHijacking
│   ├───MMCCLSID
│   ├───OpenWithExeCOMHijacking
│   ├───PowershellCLSID
│   ├───prncnfg
│   ├───PrnPort
│   ├───RunOnceComHijacking
│   ├───ScripetletFile
│   ├───ScriptletFile
│   ├───URLProtocolComHijack
│   ├───Verclsid
│   ├───WinRM_CMD
│   ├───WinRM_VBS
│   └───xWizardCLSID
├───Recon
│   ├───AltRecon
│   │   └───Censys_SubdomainsAndEmails
│   ├───EagleEye
│   ├───EavesArp_FindCompufersWhenNoLLMNR
│   ├───EyeWitness
│   ├───FacebookScraper
│   ├───FOCA
│   ├───Hamburglar
│   ├───IntRec-Pack
│   ├───Kamerika
│   ├───Marinus
│   └───Trape
├───RedTeam
│   ├───AwesomeResources
│   ├───LaptopAndArchitecture
│   ├───RedTeamTips
│   └───Vectr
├───Reflective_psExec
├───Regex
├───ReverseEngineering
│   ├───Ghidra
│   └───Tutorial
├───RID
│   ├───Bombshell
│   │   └───ReadThis
│   └───RIDHijacking
├───ROP
│   └───RP++
├───Router
│   └───RouterExploitShovel
├───RunAsSystem
│   ├───AdvancedRun
│   ├───AnotherCImplementation
│   ├───CRunAsSystem
│   │   └───MyCompiledExe
│   ├───DelphiRunAsSystem
│   ├───NirCmd
│   ├───NSudo
│   ├───PSExecCMD
│   │   ├───MyCompiledEXE
│   │   └───PsExecCMD
│   ├───psgetsystem
│   ├───RunAsSystemfromUweSieber
│   ├───RunAsSystem_BatchFile
│   ├───RunAsToken
│   │   └───MyCompileEXEs
│   ├───RunAsTrustedInstaller
│   │   └───RunAsTI-master
│   ├───SCCM_RunAsSystem
│   ├───SharePoint_runAsSystem
│   ├───Token-Priv-Code
│   └───Wraithdu
│       └───MyCompileEXEs
├───Saml
│   └───DupeKeyInjector
├───ScheduledTas 
ithDefaultCreds
│   └───ZackAttack
├───PasswordAudit
│   └───DomainPasswordAuditToolDPAT
├───PasswordCracking
│   ├───7zip
│   ├───BitCracker
│   ├───Hashcat
│   ├───JohnTheRipoer
│   └───Ntlmv1-multi
├───PasswordManagers
│   └───VaultBreaker
├───PasswordProtectedBindShell
├───PasswordSpraying
│   ├───PasswordSpraying
│   ├───Ruler
│   └───Spray
├───PatchExtraction_ForWindowsCumulativeUpdates
├───Pause-Process
├───PayloadAllTheThings
│   ├───Fuzz
│   └───PayloadsAllTheThings-master
├───PayloadDelivery
│   ├───EmbedInHTML
│   ├───PowerCloud
│   ├───PowerDNS
│   ├───PowerDropper
│   └───ShellcodeViaHTA
├───PayloadGeneration
│   ├───ARCANUS
│   ├───BackDoorFactory
│   ├───CactusTorch
│   ├───CheckAMSI_SeeHowCaught
│   ├───CheckPlease
│   ├───ClickOnceGenerator
│   ├───Cloak
│   ├───Confuser
│   ├───ConfuserEx
│   ├───CPlusPlusStringsObfuscationSystem
│   ├───Demiguise
│   ├───Ditto
│   ├───DKMC
│   ├───EncodedPythonMeterpreterpayloadwithHTTPcallback
│   ├───Enigma
│   ├───Genesis Scripting Engine
│   ├───GhostDelivery
│   ├───Hercules
│   ├───InMemoryUsingCertUtil
│   ├───Insanity-Framework
│   ├───Invoke-CradleCrafter
│   ├───Invoke-PsImage
│   ├───LuckyStrike
│   ├───MacroShop
│   ├───MCreator
│   ├───Metame
│   ├───MetaTwin
│   ├───MorphHTA
│   ├───Neo_confuserEX
│   ├───Nps_payload
│   ├───Obfuscar
│   ├───OwaspZSC
│   ├───OwaspZSC_generateShellcode
│   ├───PHANTOM EVASION 2.0.1
│   ├───Pixload
│   ├───PowerLessShell
│   ├───Powerline
│   ├───PS-ImageDelivery
│   ├───Ps1_Tookit
│   ├───Pyfuscation
│   ├───Pyobfuscate
│   ├───Recomposer
│   ├───Sharpshooter
│   ├───ShellPop_GenerateReverseShells
│   ├───ShortcutPayloadGenerator
│   ├───SpookFlare
│   ├───stager.dll_stager.exe
│   ├───StarFighters
│   ├───VBad
│   ├───VBA_RunPE
│   ├───WierdHTA
│   ├───Winpayloads - Python2.7
│   └───X86ShellcodeObfuscator
├───Payloads
│   ├───CommodityInjection
│   ├───PayloadAllTheThings
│   ├───Sec-Lists
│   │   └───SecLists-master
│   │       ├───Discovery
│   │       │   ├───DNS
│   │       │   ├───Infrastructure
│   │       │   ├───SNMP
│   │       │   └───Web-Content
│   │       │       ├───CMS
│   │       │       ├───Domino-Hunter
│   │       │       ├───SVNDigger
│   │       │       ├───URLs
│   │       │       └───Web-Services
│   │       ├───Fuzzing
│   │       │   └───Polyglots
│   │       ├───IOCs
│   │       ├───Miscellaneous
│   │       │   ├───http-request-headers
│   │       │   └───security-question-answers
│   │       │       ├───us-colleges
│   │       │       ├───us-private-schools
│   │       │       └───us-public-schools
│   │       ├───Passwords
│   │       │   ├───Common-Credentials
│   │       │   ├───Cracked-Hashes
│   │       │   ├───Default-Credentials
│   │       │   ├───Honeypot-Captures
│   │       │   ├───Leaked-Databases
│   │       │   ├───Malware
│   │       │   ├───Permutations
│   │       │   ├───Software
│   │       │   └───WiFi-WPA
│   │       ├───Pattern-Matching
│   │       │   └───Source-Code-(PHP)
│   │       ├───Payloads
│   │       │   ├───Anti-Virus
│   │       │   ├───File-Names
│   │       │   ├───Flash
│   │       │   ├───Images
│   │       │   ├───PHPInfo
│   │       │   ├───Zip-Bombs
│   │       │   └───Zip-Traversal
│   │       ├───Usernames
│   │       │   ├───Honeypot-Captures
│   │       │   └───Names
│   │       └───Web-Shells
│   │           ├───FuzzDB
│   │           ├───JSP
│   │           ├───laudanum-0.8
│   │           ├───PHP
│   │           └───WordPress
│   └───Windows-RCE-exploits
├───PcpXray
├───PenTestFrameworks
│   ├───ApFell
│   ├───DsCompromised
│   ├───EasySploit
│   ├───Nishang
│   │   └───Aug2019
│   ├───PowerHub
│   ├───PowershellEmpire
│   ├───PowershellSuite(start-hollow)_fuzzySec
│   ├───Powersploit
│   ├───PTF
│   ├───RedGhost
│   ├───RedTeamRepo
│   ├───SharpSuite
│   ├───Shr3dKit
│   └───WinPwn
├───PenTestingReportSamples
├───PentestReports
├───Persistence
│   ├───CasperStager
│   ├───DLL_Spool
│   ├───DNVM
│   ├───InvisiblePersistence
│   ├───Registry
│   │   ├───Powershell_1
│   │   └───RegistryRunKeys
│   ├───SharpDoor
│   ├───SharPersist
│   ├───SharpHid 
ng(WIG)
│   ├───Webshells
│   │   ├───404NotFoundWebShell
│   │   ├───Asp
│   │   │   └───CallHome
│   │   ├───HTShells
│   │   ├───Jsp
│   │   ├───Php
│   │   │   └───WindowsPHPReverseShell
│   │   ├───SharPyShell_encrypted
│   │   ├───Subshell
│   │   └───TennC
│   ├───WitnessMe
│   ├───XSS
│   │   ├───PopCalcNotAlert
│   │   ├───XsScrapy
│   │   ├───XssPayloads
│   │   └───XssStrike
│   ├───XXE
│   │   └───DTDFinder
│   └───ZAP
├───Windows10CustomKernelSigners
├───WindowsDesiredState
├───WindowsHardening
│   ├───DetectExploit
│   ├───FIrewall
│   ├───HardeningAuditor-master
│   ├───MSCT
│   ├───Osmedeus
│   ├───ReduceAttackSurface
│   ├───WinSpect
│   └───WUA_OFFLINE
├───WinPayloads
├───WinPwnage
├───WinRM
│   └───EvilWinRM
├───Wireless
│   ├───Bluetooth
│   │   ├───Jackit
│   │   └───Sniffle
│   ├───SDR
│   └───WiFi
│       ├───PiDense
│       ├───PiKarma
│       ├───PiSavar
│       ├───WifiCrack
│       └───Wifite2
├───WMI
│   ├───InvokeWMILm
│   ├───Persistence_script
│   ├───SharpWMI
│   └───Windapsearch
├───WSUS_WindowsServerUpdateService
│   ├───ThunderWoosusCSharp
│   └───WSUSpendu
└───XORFusvatorSecurity Tool List  
├───AD
│   ├───ACLPwn
│   ├───ACL_PWN
│   ├───ADAPE
│   ├───ADAudit
│   ├───ADCollector
│   ├───ADpwn
│   ├───ADRecon
│   ├───ADReconPowershell
│   ├───AD_DomainSwevices_Script
│   ├───AD_LDAP_Enum
│   ├───AttackCheatSheet
│   ├───Auditscript
│   ├───Awesomeness
│   ├───Bloodhound
│   ├───BloodHoundPython
│   ├───CrackMapExec
│   ├───DomainEnumWithJavascript
│   ├───DSInternals
│   ├───DumpDNS
│   ├───GetVulnerableGPO
│   ├───Grouper
│   ├───InterestingRestore
│   ├───JoinLinuxToAD
│   ├───LDAPDomainDump
│   ├───LDAPper
│   ├───LDAP_Search
│   ├───ListDomains
│   ├───LogonHistory
│   ├───PrivEsc
│   ├───PythonEnumerateUsers
│   ├───QueryClearTextLDAPBinds
│   ├───SharpAdidnsdump
│   ├───SharpGPOAbuse
│   ├───SharpHound
│   └───WinLDAPSearch
├───ARP
│   ├───EavesARP
│   └───SwissLogger
├───AtomicRedTeam
├───Audit
│   └───Seatbelt
├───AutorunsToJson
├───Autosploit
├───A_CsharpSelfMorphing
├───Bandicam
├───Bash
├───BDFProxy
├───BeyondCompare
├───BinaryDiffingTools
│   ├───BinDiff
│   ├───DarunGrim4
│   └───Diaphora
├───BruteForce
│   ├───Blazy
│   ├───DomainPasswordSpray
│   ├───Openssl-bruteforce
│   └───THC-hydra-Windows
├───BufferOverflow
│   └───EggHunter
├───Burp
│   ├───ContentDiscovery
│   └───IpRotate
├───Bypass
│   ├───AMSI
│   │   ├───AmsiScanBypass
│   │   ├───Another
│   │   ├───GadgetToJscript
│   │   ├───MattAmsi
│   │   └───PSAMSI
│   ├───AppLocker
│   │   └───PowerAL
│   ├───AppWhiteListing
│   │   └───CscriptShell
│   ├───ASLR_DEP
│   │   └───PESecinfo
│   ├───AutoRunsDetection
│   ├───AV
│   │   ├───Arno0x
│   │   ├───AswCrypter
│   │   ├───AVET
│   │   ├───CactusTorch
│   │   ├───GreatSCT
│   │   ├───HerculesPayloadGenerator
│   │   ├───InceptionFramework
│   │   ├───KmzExample
│   │   ├───MsVenonCustomShellcodr
│   │   ├───ObfuscateCactusTorch
│   │   ├───OwaspZSC
│   │   ├───PayloadSplitting
│   │   ├───PyCloak
│   │   ├───ShellCodeWrapper
│   │   ├───Shellter
│   │   ├───SystemCallsFromVisuslStudio
│   │   ├───TikiTorch
│   │   ├───VeilEvasion
│   │   └───WithMSBuildAndShellCode
│   ├───CmdRestriction
│   ├───COM
│   ├───ConstrainedLanguageMode
│   │   └───PSBypassCLM
│   ├───DownloadAndExwcuteIdeas
│   ├───EDR
│   │   ├───WithINF
│   │   └───ZombieAnt
│   ├───Firewall
│   │   └───Firefox_Tunnell
│   ├───Logs
│   │   └───Log-killer
│   ├───MemoryScanning
│   │   └───Gargoyles
│   ├───MoveFilesFreelyIdea
│   ├───NAC
│   │   └───DelosCloak
│   ├───Proxy
│   │   ├───GimmeTheFile
│   │   └───Reqrypt
│   ├───Sysmon
│   ├───UAC
│   │   ├───ALPC-BypassUAC
│   │   ├───CSharpPlaintext
│   │   ├───PythonUac
│   │   ├───SilentCleanup
│   │   ├───UAC-Bypass
│   │   ├───UACMe
│   │   ├───UAC_bypass_windows_store
│   │   └───WithFolderTrickery
│   ├───WAF
│   │   ├───DNSHistoryWAFBypass
│   │   └───WhatWAF
│   └───WindowsDefender
│       └───Disable
├───C2
│   ├───BindShellBypassHostFirewallwithSMB
│   ├───ChaShell
│   ├───CobaltStrike
│   ├───Covenant
│   ├───DDoor
│   ├───Diagon
│   ├───DnsC 
lippy
├───Cloud
│   ├───AWS
│   │   ├───Barq
│   │   ├───BucketFinder
│   │   ├───MasS3
│   │   ├───MetaDataService
│   │   ├───Pacu
│   │   ├───PowershelleryS3Finder
│   │   ├───s3Monster
│   │   ├───S3Scanner
│   │   └───TakeFullControl
│   ├───Azure
│   │   └───Microburst
│   ├───CloudBunny
│   └───Google
│       └───BruteBucket
├───CloudFlare
│   └───CloudUnflare
├───CMS
│   ├───CMSeek
│   ├───CMSMap
│   ├───JenikinsPillage
│   ├───malicious-wordpress-plugin
│   └───VulnX
├───CobaltStrike
│   └───SharpCompile
├───CodeInjection
│   ├───AtomBombing
│   ├───Cave_miner
│   ├───DNCI - Dot Net Code Injector
│   ├───Gargoyle
│   ├───GhostHook
│   └───PROPagate
├───ComHijacking
│   ├───Enigma0x3_MessageBox
│   │   └───MiscPowershell_getTasks
│   ├───OleView
│   ├───OleViewDotNet
│   └───PS1Jacker
├───CommandoVM
│   └───MetasploitWindowsInstall
├───Containers
│   └───Trivy
├───Conversion
│   ├───Bin2Hex
│   ├───DLL_to_exe
│   ├───LibPeConv
│   ├───PE_to_Shellcode
│   └───shellconv
├───CradleTest
│   ├───BLueCradleTest
│   └───CradleTest
├───CredentialDumping
│   ├───ADStuff
│   ├───AndrewSpecial
│   ├───AsRepRoast
│   ├───ATPMinidump
│   ├───AzureDumpDomainHashes
│   ├───BadODF
│   ├───BadPdf
│   ├───CaptureEdgeAndIECreds
│   ├───CaptureHashesWithURLFile
│   ├───CheckLocalAdminHash
│   ├───ChromePasswords
│   ├───CloudCopy_DumpAWSDomainHashes
│   ├───CMinidump
│   ├───CompileFromBatch
│   ├───Comsvcs
│   ├───CookieMonster
│   ├───Copy-VSS
│   ├───Crackmapexec
│   ├───CreateMiniDump
│   ├───CreateMiniDumpCPP
│   ├───Cred-Ninja
│   ├───CredCatcher
│   ├───CredentialPhisher
│   │   └───Invoke-CredentialPhisher-master
│   ├───CredentialsFileView
│   ├───CredKing
│   ├───CSharpClipboardWatcher
│   ├───CSharpMimikatz
│   │   └───Subtee
│   ├───CsharpMinidump
│   ├───CSharpPowershellCipboardWatcher
│   ├───DCOM DCERPC Local NTLM Reflection Elevation of Privilege
│   ├───DetectPasswordViaNTLMinFlow
│   ├───DomainPasswordSpray
│   ├───DSInternals
│   ├───Dumpert
│   ├───EFSFiles
│   ├───EternalRelax
│   ├───Evil-SsDp
│   ├───FGDump
│   ├───FindRiskySPNs
│   ├───Get-PasswordFile
│   ├───GetCurrentUsersPassword
│   ├───GetUserSPNs
│   ├───GhostPotato
│   ├───GoldenTicket
│   ├───GrabDump
│   ├───Impacket
│   ├───ImpacketStandAloneWindowExes
│   │   └───impacketWindowsExes
│   ├───ImpacketStaticBinaries
│   ├───ImpDump
│   ├───InternalMonologue
│   ├───InternalMonologueAttack
│   ├───Inveigh
│   ├───InveighZero
│   ├───Invoke-CredentialPhish
│   │   └───PoshWinRT
│   ├───Invoke-DCSync
│   ├───Invoke-TokenManipulation
│   ├───Invoke-WCMDump
│   ├───InvokeKerberoastHarmJoy
│   ├───InvokePasswordAudit
│   ├───InvokePasswordPrompt
│   ├───JenkinsDecrypt
│   ├───KeeThief
│   ├───Kekeo
│   ├───KerberoastingFromSetupToCracking
│   ├───KerberoastNidem
│   ├───KrbRelayx
│   ├───LaZagne
│   ├───LDAPSearch
│   ├───LSASS
│   ├───MailPasswordView
│   ├───MakeMeEnterpriseAdmin
│   ├───MicrosoftOffice NTLMHashesviaFrameset
│   ├───Mimikatz
│   │   ├───AnotherMimiKatzObfuscation
│   │   ├───DCShadow
│   │   ├───GoldenTicket
│   │   ├───ImpersonatingOfficeUsers
│   │   ├───Invoke_Mimi
│   │   ├───Latest_20190705
│   │   ├───mimikatz-master
│   │   ├───MimikatzDefense
│   │   ├───Mimikatz_obfuscator
│   │   ├───MorphedMimiKatzFromMetame
│   │   ├───NovelJSMimikatzLoader
│   │   ├───ObfuscationTechniques
│   │   ├───PowershellDetectSkeletonKey
│   │   ├───ResetKRBTGT_password_for_goldenTicketMitigation
│   │   ├───Scripts
│   │   │   └───ObfuscateMimikatz
│   │   ├───UncoverDCShadow
│   │   └───Update_AUG17_2019
│   ├───MimikatzFromWebShell
│   ├───MimikatzPowershell
│   │   └───Scripts
│   │       └───ObfuscateMimikatz
│   ├───Mimikittenz
│   ├───MimiPenguin
│   ├───Mitm6
│   ├───MS17-10_Scanner
│   ├───MyKatz
│   ├───MyPresentation_SharpCatUsingHex
│   ├───Net-creds
│   ├───NetKatz
│   ├───NetNTLMtoSilverTicket
│   ├───NetRipper
│   ├───NetworkMiner
│   ├───New folder
│   ├───Nishang
│   ├───NTDSDumpEx
│   ├───NTDSExtract
│   ├───NTLMInjector_ChangePasswordWithHASH
│   ├───NtlmRelayToEWS
│   ├───NTLM_FromRDPFiles
│   ├───Out-MiniDump
│   ├───Outlook
│ 
ks
├───Schtasks
│   └───Reflective_Schtasks
├───Scripts
│   ├───URLExecuteFile
│   └───WhitelistBypassing
├───SearchForKeys
│   ├───DumpsterDiver
│   ├───RepoScanner
│   └───TruffleHog
├───SecLists
│   └───2
├───SharpSploit
├───SharpView
├───ShellCode
│   ├───PE_To_Shellcode
│   ├───ShellCodeCompiler
│   └───Sickle
├───ShellLab
├───Shells
│   ├───PinkP4nther
│   └───PythonShells
├───SignatureVerificationAttack
├───Software
│   ├───7zip
│   ├───AutoIT
│   ├───DotNetFramework
│   │   ├───3.5
│   │   ├───4.0
│   │   ├───4.5.2
│   │   ├───4.6.2
│   │   ├───4.7.2
│   │   ├───4.8
│   │   └───Core
│   │       ├───2.1
│   │       │   └───x64
│   │       ├───2.2
│   │       │   └───x64
│   │       └───3.0
│   │           └───x64
│   ├───DSInternals
│   ├───Empire
│   │   └───Scripts
│   │       └───infosecn1nja_wmic_starfighters
│   ├───Firewall
│   │   └───pfSense
│   ├───ILSpy
│   ├───KaliLive
│   ├───Ncat
│   │   ├───AVSafeVersion
│   │   ├───IntoxWinNetCar
│   │   │   ├───32
│   │   │   └───64
│   │   └───ncat-portable-5.59BETA1
│   ├───NMAP
│   │   ├───NmapLatestInstall
│   │   └───Nmap_Vulners
│   ├───NMAP-Scripts
│   ├───Notepad++
│   ├───PIA
│   ├───ProcessHacker
│   ├───Putty
│   ├───ResourceHacker
│   ├───Splunk
│   ├───VisualStudioCode
│   │   ├───LinuxUbuntu
│   │   └───Windows
│   │       └───DotNetCorePreview
│   ├───VNCViewer
│   ├───WifiDrivers
│   ├───WinDirStat
│   └───WindowsMessageAnalyzer
├───SQL
│   ├───Audit
│   ├───BBQSql
│   ├───BlindSQLInjectionviaBitshifting
│   ├───brute-sqlcipher
│   ├───DSSS
│   ├───DumpMSSQLCreds
│   ├───GeneralScripts
│   ├───MSDat
│   ├───NoSQLMap
│   ├───PowerUpSQL
│   ├───PythonCustomStackedQuery
│   ├───SleuthQL
│   ├───SQLCompactQueryAnalyzer
│   ├───SQLInjectionWiki
│   └───WhiteWidow
├───Squiblydoo
├───SSH
│   ├───SSHAuditor
│   └───SSHLooter
├───SSO
│   └───EspreSSO
├───StaticBinaries
├───StealthDomainRecon
│   └───Vibe
├───Subdomain
│   ├───FindDomain
│   ├───SubdomainEnumeration
│   │   └───AMass
│   └───SubdomainTakeover
│       ├───SDTakeOver
│       ├───SubdomainTakeoverScanner
│       ├───SubR3con
│       ├───Subzy
│       └───TakeOver-v1
├───SymbolicLinkWindows
├───SysInternals
├───SYSMON
│   └───CONFIG
│       ├───OlofHartong
│       │   └───Sysmon-Modular
│       └───SwiftOnSecurityConfig
├───Tails
│   ├───TailsVM
│   └───USBImage
├───TEMP
├───TextToSpeech
│   └───PowerSpeak
├───THP
│   ├───CovertChannels
│   ├───MeterpreterSSH
│   └───THP2Setup
├───ThreatHunting
│   ├───PSHunt
│   └───ThreathunterPlaybook
│       └───WebShellIntelFlorianRoth
├───ThreatModeling
├───ThreatSimulation
│   ├───APTSimulator
│   ├───ATAT
│   ├───MalwLess
│   ├───Metta_attack_simulation
│   └───RedHuntThreadEmulation
├───TokenStealing
│   └───FaceDancer
├───TPLMap
├───Typhoon
├───UACMe
├───UboatHttpBot
├───Unicorn
├───UnkillableProcess
├───UnstoppableService
├───USBArmory
├───VMSS2Core
├───VMWare
│   └───FixCopyPaste
├───VNC
│   └───VNCPassword
├───VoiceClone
├───VOIP
│   └───SipVicious
├───Volatility
├───VPN
│   └───Pulse
├───VulnLdap
├───VulnScanning
│   ├───Vulmap
│   └───VulnersNmapScanForServices
├───WebTesting
│   ├───AEMHackerToolset
│   ├───AnonymousHTTPGetRequests
│   ├───Apache
│   │   └───Struts
│   ├───Arjun_FindHiddenParameters
│   ├───BlackWidow
│   ├───BuiltWith
│   │   └───Webtech
│   ├───BurpSuite
│   ├───Captcha
│   │   ├───Uncaptcha
│   │   └───Uncaptcha2
│   ├───CMS
│   │   └───CMSSeek
│   ├───CookieMonster
│   ├───CORS
│   │   └───CORScanner
│   ├───Deserialization
│   │   ├───DeserializationTester
│   │   ├───YSoSerial
│   │   └───YSoSerialDotNet
│   ├───DirectoryBruteForce
│   │   └───DirHunt
│   ├───GoBuster
│   │   └───RecursiveGobuster
│   ├───HTA
│   │   └───SimpleCommandRunnsr
│   ├───LFIFreak
│   ├───NoSQLMap
│   ├───PayloadAllTheThings
│   ├───RelativeURLExtractor
│   ├───RestAPI
│   │   └───ASTRA_RestAPI_testing
│   ├───ShellShockFinder
│   ├───SSRF
│   │   └───GopherUS
│   ├───TemplateInjection
│   │   └───TPLMap
│   ├───Upload
│   │   └───FUXploider
│   ├───ViewGen
│   ├───WebAutoPwn_int0x33
│   ├───WebCrawlerExtraction_Photon
│   ├───WebInformationGarheri 
DCOM
│   ├───DCOMrade
│   └───SharpExcel4-DCOM
├───Deception
│   ├───BashFuscator
│   ├───Endlessh
│   ├───FakeSigning_meterpreterSignedWithGoogld
│   └───PasteJacking
├───Decryption
│   ├───Decrypt-TFSSecretVariables
│   └───MicrosoftOrchestrator
├───DefaultPasswords
│   ├───IOT
│   └───SCADA_IOT
├───dex2jar
├───DHCPPwn
├───DidierStevensTools
│   ├───AMSIScan
│   ├───CustomCMD.exe
│   └───DependancyInstallForHisTools
├───Discovery
│   ├───GatherDomainAndSubdomainInfoFromIPRange
│   ├───OwaspAmass
│   └───PythonMassScan
├───DisposableEmailDomains
│   └───disposable-email-domains
├───DLL
│   ├───.NET Profiler DLL Hijack
│   ├───Bleak
│   ├───CreateThreadInjection
│   ├───CsharpDLLInjection
│   ├───DLL_Injection_3
│   ├───DueDLLigence
│   ├───Hollows_hunter
│   ├───InjectAllTheThings
│   ├───InjectDLL_InDriver
│   ├───MaliciousDLLGenerator
│   ├───Reflective DLL Injection
│   ├───reflective-injection-detection
│   ├───ReflectiveDLLInjection
│   ├───Robber
│   ├───SDRI
│   └───sRDI-ShellcodeReflectiveDLLInjection
├───DLR
│   └───OffensiveDLR
├───DNS
│   ├───DNSGrep
│   └───DNsRebinding
│       └───WhoNowDNSServer
├───Docker
│   ├───Gorsair
│   └───ListOfSecurityTools
├───DomainController
│   ├───DcShadow
│   ├───DumpNTDS.dit
│   └───SMBExec
├───Donut
│   └───DevBrach
├───DonutCS
├───DotNetInterop
├───DotNetToJScript
├───ElasticSearch
├───Encryption
│   └───EncryptStringTool
├───Entropy
│   └───EntroPY
├───Enumeration
│   ├───CommandLists
│   ├───General
│   │   └───AList
│   ├───Linux
│   │   ├───Enum4Linux
│   │   ├───Jalesc
│   │   ├───LinEnum
│   │   ├───LinuxExploitSuggester
│   │   └───PerlLinuxExploitSuggester
│   ├───RidRelay
│   └───Windows
│       ├───BloodHound
│       │   ├───BloodHound
│       │   ├───BloodHoundBinaries
│       │   ├───BloodHoundTools
│       │   ├───BoodHound.Py
│       │   └───SharpHound
│       ├───CrackmapExec
│       ├───DetectExploit
│       ├───GetSharePermissions
│       ├───HostEnum
│       │   └───SharpShared
│       ├───LDAPDomainDump
│       ├───ListDomainStuff
│       ├───NetView
│       ├───PowerSploit
│       ├───Powerview
│       ├───SensitiveDataSearch
│       │   └───SauronEye
│       ├───SMBMap
│       ├───TestAntivirus
│       ├───UserEnum
│       ├───VBSListAllComputersIntheDomain
│       └───WindowsEnum
├───EventLog
│   └───Invoke-Phant0m
├───EvilClippy
├───Exfiltration
│   ├───CloakifyFactory
│   ├───DET
│   ├───DNSExfiltration
│   │   ├───DNSExfiltratorArnox
│   │   ├───PacketWhisper
│   │   └───ReflectiveDnsExfiltration
│   ├───DNSlivery
│   ├───DNSStealv2
│   ├───PowershellAzeriaLabs
│   └───Sharpbox
├───Exploitdb
│   ├───BinSploits
│   ├───ExploitsAndShellcode
│   └───Papers
├───ExploitFolders
│   ├───0x27
│   └───Meltdown
├───FindBufferOverflows
│   └───ZeraTool
├───FIndMyHash
├───FolderPermissions
│   └───Set-permission
├───ForkBombs
├───FREE_VMS
├───Fuzz
│   ├───FuzzBuilder
│   ├───FuzzBunch
│   ├───Fuzzowski
│   └───Unicorefuzz
├───GatherDeviceInfoFromWebsite
│   └───Seeker
├───General
│   └───DonkeysRedTeamScritps
├───GeneratePasswordsFromWebScrape
├───GenerateWordlist
│   └───TheMentalist
├───GetGP-Trashfire
├───Git
│   ├───GitGot
│   └───GitSecrets
├───Gobuster
├───GoldImageScanning
├───Hak5
│   ├───BashBunny
│   ├───LanTurtle
│   ├───PacketSquirrel
│   └───WifiPineapple
├───Heros
│   ├───Arnox
│   │   ├───CSharp
│   │   └───XLL
│   ├───ClappyMonkey
│   ├───DanielBonhannon
│   │   ├───DevSec-Defense
│   │   ├───Invoke-DOSFuscation
│   │   ├───InvokeCradleCrafter
│   │   ├───InvokeObfuscation
│   │   ├───Out-FINcodedCommand
│   │   └───Revoke-Obfuscation
│   ├───FlorianRoth
│   │   └───Sigma
│   ├───FuzzySecurity
│   │   ├───PowershellKernalPrivs
│   │   ├───PowershellMusings
│   │   ├───Sharpsuite
│   │   └───UnixPrivEsc
│   ├───Hasherezade
│   │   ├───Demos
│   │   ├───HollowsHunter
│   │   └───Pe-Sieve
│   ├───Mattifestation
│   │   ├───3076EventExtractor_ps1
│   │   ├───Build
│   │   ├───CertificateCloning
│   │   ├───ConvertSIDtoUsername
│   │   ├───CopyAuthenticode
│   │   ├───DorNetRuntimeManifest
│   │   ├───DotNetDataCollectot
│   │   ├───DropBinaryInCMD 
│   │   └───SharpExchange
│   ├───Invoke-NoShell
│   ├───LyncSniper
│   ├───MacroCall
│   ├───MacroCreator
│   ├───MacroPack
│   ├───MacroShop
│   ├───MaliciousMacroMSBuild
│   ├───Ms-Content
│   ├───NotePadExploitFranework
│   ├───Outlook
│   │   ├───OutlookBruteForcer
│   │   └───OutlookToolbox
│   ├───PersistentVTSO_VSToolsForOffice
│   ├───SharePoint
│   │   └───Spartan
│   ├───Skype
│   │   └───LyncSmash
│   ├───VBARunPE
│   └───VBA_ASR_RulesBypass
├───OleView
├───OptOut
├───Oracle
│   ├───Metasploit
│   ├───ODAT
│   └───SQLPlus
├───OSCP
│   ├───AnotherRepo
│   └───OscpRepo
├───OSQuery
│   ├───MitreOSQueries
│   └───MoreWithFleet
├───PacketCapture
│   ├───Clumsy
│   ├───GoodbyeDPI
│   ├───HcxDumptool
│   ├───MicrosoftMessageAnalyzer
│   ├───NetCap
│   ├───NetRipper
│   ├───NmCap
│   ├───PhanTap
│   ├───Raw-Socket-Sniffer
│   ├───RawSocketSniffer
│   ├───SharpPCAP
│   ├───Snifter
│   ├───TCPReplay
│   ├───WinDivert
│   ├───WindivertSharp
│   └───WiresharkPortable
│       └───WiresharkPortable
├───PassTheHash_passCreds
│   ├───Cr3dov3r
│   ├───CredNinja
│   ├───InvokeTheHash
│   ├───PassHuntFindDevicesWithDefaultCreds
│   └───ZackAttack
├───PasswordAudit
│   └───DomainPasswordAuditToolDPAT
├───PasswordCracking
│   ├───7zip
│   ├───BitCracker
│   ├───Hashcat
│   ├───JohnTheRipoer
│   └───Ntlmv1-multi
├───PasswordManagers
│   └───VaultBreaker
├───PasswordProtectedBindShell
├───PasswordSpraying
│   ├───PasswordSpraying
│   ├───Ruler
│   └───Spray
├───PatchExtraction_ForWindowsCumulativeUpdates
├───Pause-Process
├───PayloadAllTheThings
│   ├───Fuzz
│   └───PayloadsAllTheThings-master
├───PayloadDelivery
│   ├───EmbedInHTML
│   ├───PowerCloud
│   ├───PowerDNS
│   ├───PowerDropper
│   └───ShellcodeViaHTA
├───PayloadGeneration
│   ├───ARCANUS
│   ├───BackDoorFactory
│   ├───CactusTorch
│   ├───CheckAMSI_SeeHowCaught
│   ├───CheckPlease
│   ├───ClickOnceGenerator
│   ├───Cloak
│   ├───Confuser
│   ├───ConfuserEx
│   ├───CPlusPlusStringsObfuscationSystem
│   ├───Demiguise
│   ├───Ditto
│   ├───DKMC
│   ├───EncodedPythonMeterpreterpayloadwithHTTPcallback
│   ├───Enigma
│   ├───Genesis Scripting Engine
│   ├───GhostDelivery
│   ├───Hercules
│   ├───InMemoryUsingCertUtil
│   ├───Insanity-Framework
│   ├───Invoke-CradleCrafter
│   ├───Invoke-PsImage
│   ├───LuckyStrike
│   ├───MacroShop
│   ├───MCreator
│   ├───Metame
│   ├───MetaTwin
│   ├───MorphHTA
│   ├───Neo_confuserEX
│   ├───Nps_payload
│   ├───Obfuscar
│   ├───OwaspZSC
│   ├───OwaspZSC_generateShellcode
│   ├───PHANTOM EVASION 2.0.1
│   ├───Pixload
│   ├───PowerLessShell
│   ├───Powerline
│   ├───PS-ImageDelivery
│   ├───Ps1_Tookit
│   ├───Pyfuscation
│   ├───Pyobfuscate
│   ├───Recomposer
│   ├───Sharpshooter
│   ├───ShellPop_GenerateReverseShells
│   ├───ShortcutPayloadGenerator
│   ├───SpookFlare
│   ├───stager.dll_stager.exe
│   ├───StarFighters
│   ├───VBad
│   ├───VBA_RunPE
│   ├───WierdHTA
│   ├───Winpayloads - Python2.7
│   └───X86ShellcodeObfuscator
├───Payloads
│   ├───CommodityInjection
│   ├───PayloadAllTheThings
│   ├───Sec-Lists
│   │   └───SecLists-master
│   │       ├───Discovery
│   │       │   ├───DNS
│   │       │   ├───Infrastructure
│   │       │   ├───SNMP
│   │       │   └───Web-Content
│   │       │       ├───CMS
│   │       │       ├───Domino-Hunter
│   │       │       ├───SVNDigger
│   │       │       ├───URLs
│   │       │       └───Web-Services
│   │       ├───Fuzzing
│   │       │   └───Polyglots
│   │       ├───IOCs
│   │       ├───Miscellaneous
│   │       │   ├───http-request-headers
│   │       │   └───security-question-answers
│   │       │       ├───us-colleges
│   │       │       ├───us-private-schools
│   │       │       └───us-public-schools
│   │       ├───Passwords
│   │       │   ├───Common-Credentials
│   │       │   ├───Cracked-Hashes
│   │       │   ├───Default-Credentials
│   │       │   ├───Honeypot-Captures
│   │       │   ├───Leaked-Databases
│   │       │   ├───Malware
│   │       │   ├───Permutations
│   │       │   ├───Software
│   │       │   └───WiFi-WPA
│   │       ├───Pattern-Matching
│   │       │   └───Source-Code-( 
├───p0wnedShell
│   ├───PassTheCache
│   ├───PasswordPopupPowershell
│   ├───PasteHunter
│   ├───PCredz
│   ├───PoshKatz
│   ├───Powermad
│   ├───PowerMemory
│   ├───PowerOps
│   ├───Powershellery_Get-SPN
│   ├───PoweshellMimikatz2
│   ├───ProcSpy
│   ├───PwnedOrNot
│   ├───Pykek
│   ├───PyKerberoastV2
│   ├───PyKerberoastV3
│   ├───PypyKatz
│   ├───PysecDumpMimiAlternative
│   ├───PythonKerberoast
│   ├───RDPSpray
│   ├───RDPThief
│   ├───ReadPst
│   ├───RedSnarf
│   ├───Relayer
│   ├───ResetWindowsPassword
│   ├───Responder
│   │   ├───August2019
│   │   ├───Responder-master
│   │   └───WindowsExes
│   ├───RIDHijacking
│   ├───Rubeus
│   ├───RunAsTI_TrustedInstaller
│   │   ├───AutoIT
│   ├───SafetyKatz
│   ├───SessionGopher
│   ├───ShareSearch
│   ├───SharpDPAPI
│   ├───SharpDump
│   ├───SharpLocker
│   ├───SharpMiniDump
│   ├───Sharproast
│   ├───SharpSniper
│   ├───SharpUp
│   ├───SharpWeb
│   ├───ShowAccountLockout
│   ├───SilverTicket
│   ├───Simple.CredentialsManager
│   ├───SMBBrute
│   │   └───V010
│   ├───SMBetray
│   ├───SprayingToolkit
│   ├───SqlDumper
│   ├───SQLServerHashDumpWithDirTree
│   ├───SubAuth
│   ├───TimMedin
│   ├───TimMedinKerberoast
│   ├───UsbArmoryLanTurtle
│   ├───VaultPasswordView
│   ├───VSOWN
│   ├───WifiPasswords
│   ├───Window10Passwords
│   ├───WindowsDebuggingTools
│   ├───Worse-PDF
│   ├───WPA2
│   └───XPN_BecomingSystem
├───Cryptography
├───CscriptShell
├───CSharpGeneral
│   ├───AmsiScanBypass
│   ├───Bin2Hex
│   ├───Bleak
│   ├───BytecodeApi
│   ├───CompileInMemory
│   │   ├───MemoryModule
│   │   └───Research
│   ├───CoolInjection
│   ├───CSharpCustomStager
│   ├───CsharpDieHarder
│   ├───CsharpEmpire
│   ├───CsharpInjection
│   ├───CSharpProcessInjection
│   ├───CShell
│   ├───CustomStager
│   ├───DotNetDeObfuscation
│   ├───DotNetOerDotNet
│   ├───DotnetToJscript
│   ├───File-Splitter
│   ├───FindCredsSharpCloud
│   ├───GetSEDebugPriviledge
│   ├───Ghostpack csharp stuff
│   ├───ILSpy
│   ├───Interesting
│   ├───NewShellWhoDis
│   ├───Noisette_The nuts-breakerCSharpObfuscator
│   ├───NoPowerShell
│   ├───OffensiveCSharp
│   │   └───Aug2019
│   ├───OleViewDotNet
│   ├───PowershellInCSharp
│   ├───RemoteRegisterDllPSEXEC
│   ├───RunAs
│   ├───SafetyKatz
│   ├───SendKeysToCMD
│   │   └───FindUserPassword_2
│   ├───Sharp-InvokeSmbExec
│   ├───Sharp-invokeWmiExec
│   ├───Sharp-Suite
│   ├───SharpAdidnsdump
│   ├───SharpAllowedToAct
│   ├───SharpCradle
│   ├───SharpDPAPI
│   ├───SharpDump
│   ├───SharpExec
│   ├───SharpFruit
│   ├───SharpPCAP
│   ├───SharpProcEnum
│   ├───SharpShell
│   ├───SharpSpray
│   ├───SingleFileEXE_core
│   ├───TaskAwait
│   ├───TokenImpersonation
│   │   └───1
│   ├───UnmanagedPowershell
│   ├───VigenereSolver
│   ├───WheresMyImplant
│   ├───WinPwn
│   ├───WinXRunPEx86x64
│   ├───WMIProcessWatcher
│   └───WritingPenTestToolsForPenTestersCSharp
├───CuckooSandBox
├───Curl2PS
├───CVE
│   └───CVE-2017-0213 Windows COM Elevation of Privilege Vulnerability
├───DCOM
│   ├───DCOMrade
│   └───SharpExcel4-DCOM
├───Deception
│   ├───BashFuscator
│   ├───Endlessh
│   ├───FakeSigning_meterpreterSignedWithGoogld
│   └───PasteJacking
├───Decryption
│   ├───Decrypt-TFSSecretVariables
│   └───MicrosoftOrchestrator
├───DefaultPasswords
│   ├───IOT
│   └───SCADA_IOT
├───dex2jar
├───DHCPPwn
├───DidierStevensTools
│   ├───AMSIScan
│   ├───CustomCMD.exe
│   └───DependancyInstallForHisTools
├───Discovery
│   ├───GatherDomainAndSubdomainInfoFromIPRange
│   ├───OwaspAmass
│   └───PythonMassScan
├───DisposableEmailDomains
│   └───disposable-email-domains
├───DLL
│   ├───.NET Profiler DLL Hijack
│   ├───Bleak
│   ├───CreateThreadInjection
│   ├───CsharpDLLInjection
│   ├───DLL_Injection_3
│   ├───DueDLLigence
│   ├───Hollows_hunter
│   ├───InjectAllTheThings
│   ├───InjectDLL_InDriver
│   ├───MaliciousDLLGenerator
│   ├───Reflective DLL Injection
│   ├───reflective-injection-detection
│   ├───ReflectiveDLLInjection
│   ├───Robber
│   ├───SDRI
│   └───sRDI-ShellcodeReflectiveDLLInjection
├───DLR
│   └───OffensiveDLR
├───DNS
│   ├───DNSGrep
│   └───DNsRebinding
│       └───WhoNowDNSSer 
Cmstp
│   │   ├───Comsvcs
│   │   ├───Control
│   │   ├───Csc
│   │   ├───Cscript
│   │   ├───csi
│   │   ├───Devtoolslauncher
│   │   ├───Dfsvc
│   │   ├───Diskshadow
│   │   ├───Dnscmd
│   │   ├───dnx
│   │   ├───Dxcap
│   │   ├───Esentutl
│   │   ├───Eventvwr
│   │   ├───Excel
│   │   ├───Expand
│   │   ├───Extexport
│   │   ├───Extrac32
│   │   ├───Findstr
│   │   ├───Forfiles
│   │   ├───Ftp
│   │   ├───Gpscript
│   │   ├───Hh
│   │   ├───Ie4uinit
│   │   ├───Ieadvpack
│   │   ├───Ieaframe
│   │   ├───Ieexec
│   │   ├───Infdefaultinstall
│   │   ├───Installutil
│   │   ├───Jsc
│   │   ├───Makecab
│   │   ├───Manage-bde
│   │   ├───Mavinject
│   │   ├───Mftrace
│   │   ├───Microsoft.Workflow.Compiler
│   │   ├───Mmc
│   │   ├───Msbuild
│   │   ├───Msconfig
│   │   ├───Msdeploy
│   │   ├───Msdt
│   │   ├───Mshta
│   │   ├───Mshtml
│   │   ├───Msiexec
│   │   ├───msxsl
│   │   ├───New folder
│   │   ├───New folder (2)
│   │   ├───Odbcconf
│   │   ├───Pcalua
│   │   ├───Pcwrun
│   │   ├───Pcwutl
│   │   ├───Pester
│   │   ├───Powerpnt
│   │   ├───Presentationhost
│   │   ├───Print
│   │   ├───Pubprn
│   │   ├───rcsi
│   │   ├───Reg
│   │   ├───Regasm
│   │   ├───Regedit
│   │   ├───Register-cimprovider
│   │   ├───Regsvcs
│   │   ├───Regsvr32
│   │   ├───Replace
│   │   ├───Rpcping
│   │   ├───Rundll32
│   │   ├───Runonce
│   │   ├───Runscripthelper
│   │   ├───Sc
│   │   ├───Schtasks
│   │   ├───Scriptrunner
│   │   ├───Setupapi
│   │   ├───Shdocvw
│   │   ├───Shell32
│   │   ├───Slmgr
│   │   ├───Sqldumper
│   │   ├───Sqlps
│   │   ├───SQLToolsPS
│   │   ├───Squirrel
│   │   ├───SyncAppvPublishingServer
│   │   ├───Syssetup
│   │   ├───te
│   │   ├───Tracker
│   │   ├───Tttracer
│   │   ├───Update
│   │   ├───Url
│   │   ├───Verclsid
│   │   ├───vsjitdebugger
│   │   ├───Wab
│   │   ├───winrm
│   │   ├───Winword
│   │   ├───Wmic
│   │   ├───Wscript
│   │   ├───Wsreset
│   │   ├───Xwizard
│   │   └───Zipfldr
│   ├───GTFOBLookup
│   ├───LOLBins_OLD
│   └───LOL_new
├───Magecart_check
├───MalwareAnalysis
│   ├───AutopsyAndSleuthKith
│   ├───De4Dot_ NETDeobfuscatorandUnpacker
│   ├───DecodeVBE_DidierStevens
│   ├───DrlTrace
│   ├───Fatt
│   ├───FNord
│   ├───MalTrail
│   ├───PowerShellArsenal
│   ├───RegiiPy
│   ├───SimpleStaticMalwareAnalysis
│   ├───UniPacker
│   ├───Virii_OldVirusSource
│   ├───Volatility
│   │   └───InstallInfo
│   ├───WindowsProcessFundamentals
│   ├───YaraGenerator
│   └───YarGen
├───MemoryInjection
│   ├───CoffeeShot
│   └───PCILeech
├───Misc
│   └───CrashCast
├───MITM
│   ├───Bettercap
│   ├───InjectionArticle
│   ├───Mitm6
│   ├───MITMf
│   ├───Seth_RDP_mitm
│   └───WSUSpectProxy
├───Mobile
│   ├───ApiKeyExractor
│   ├───BypassCertificatePinning
│   ├───EmpireMobile
│   ├───Genymotion
│   │   └───ARM_Translation
│   ├───InSSIDIous
│   ├───PhoneSploit
│   └───TrueGaze
├───MouseJack
├───MovingFiles
│   ├───Bits
│   └───SetupSimpleWebdavServer
├───MsBuild
│   └───MsBuildMacroGenerator
├───NamedPipes
├───NessusScripts
├───New folder
├───NGrok
├───NTFS_permissions
├───NTLMHashCalculator
│   ├───CalculateNTLMHash
│   ├───Microsoft
│   ├───NTLM
│   └───WinHash
├───O365
│   ├───ImpersonatingOffice365UsersWithMimikatz
│   └───UhOh365
├───OAuth
│   ├───OAuthHunting
│   └───PwnAuth
├───Obfuscation
│   ├───AutoIt-Obfuscation_Awsome
│   ├───Basfuscator
│   ├───Bin2Hex
│   ├───CallObfuscator_lookHere
│   ├───CuteIt
│   ├───Demiguise
│   ├───ExeToVBS
│   ├───Gif2xslt_excel
│   ├───HideHTAInHTML
│   ├───Invisi-Shell
│   ├───InvisiShell
│   ├───Invoke-DOSFuscation
│   ├───Ipfuscator
│   ├───IPFuscator (1)
│   ├───Noisy
│   ├───Out-EncodedCommand
│   ├───Out-EncryptedScript
│   ├───Out_compressedDll
│   ├───PEUnion
│   ├───ProcessHide
│   ├───RemoveComments
│   └───StunnexCCodePro_Obfuscator
├───OffensiveDLR
├───Office
│   ├───ADB
│   ├───excel
│   │   └───Excel4Dcom
│   ├───ExcelCellExectionPayload
│   ├───ExcelPasswordCracking
│   ├───Exchange
│   │   ├───EWSToolKit
│   │   ├───ExchangeRelayX
│   │   ├───Invoke_ExchangePrivEsc
│   │   ├───MailSniper
│   │   ├───PrivExchange
│   │   ├───Ruler_exchange_remote_acces 
mainsAndEmails
│   ├───EagleEye
│   ├───EavesArp_FindCompufersWhenNoLLMNR
│   ├───EyeWitness
│   ├───FacebookScraper
│   ├───FOCA
│   ├───Hamburglar
│   ├───IntRec-Pack
│   ├───Kamerika
│   ├───Marinus
│   └───Trape
├───RedTeam
│   ├───AwesomeResources
│   ├───LaptopAndArchitecture
│   ├───RedTeamTips
│   └───Vectr
├───Reflective_psExec
├───Regex
├───ReverseEngineering
│   ├───Ghidra
│   └───Tutorial
├───RID
│   ├───Bombshell
│   │   └───ReadThis
│   └───RIDHijacking
├───ROP
│   └───RP++
├───Router
│   └───RouterExploitShovel
├───RunAsSystem
│   ├───AdvancedRun
│   ├───AnotherCImplementation
│   ├───CRunAsSystem
│   │   └───MyCompiledExe
│   ├───DelphiRunAsSystem
│   ├───NirCmd
│   ├───NSudo
│   ├───PSExecCMD
│   │   ├───MyCompiledEXE
│   │   └───PsExecCMD
│   ├───psgetsystem
│   ├───RunAsSystemfromUweSieber
│   ├───RunAsSystem_BatchFile
│   ├───RunAsToken
│   │   └───MyCompileEXEs
│   ├───RunAsTrustedInstaller
│   │   └───RunAsTI-master
│   ├───SCCM_RunAsSystem
│   ├───SharePoint_runAsSystem
│   ├───Token-Priv-Code
│   └───Wraithdu
│       └───MyCompileEXEs
├───Saml
│   └───DupeKeyInjector
├───ScheduledTasks
├───Schtasks
│   └───Reflective_Schtasks
├───Scripts
│   ├───URLExecuteFile
│   └───WhitelistBypassing
├───SearchForKeys
│   ├───DumpsterDiver
│   ├───RepoScanner
│   └───TruffleHog
├───SecLists
│   └───2
├───SharpSploit
├───SharpView
├───ShellCode
│   ├───PE_To_Shellcode
│   ├───ShellCodeCompiler
│   └───Sickle
├───ShellLab
├───Shells
│   ├───PinkP4nther
│   └───PythonShells
├───SignatureVerificationAttack
├───Software
│   ├───7zip
│   ├───AutoIT
│   ├───DotNetFramework
│   │   ├───3.5
│   │   ├───4.0
│   │   ├───4.5.2
│   │   ├───4.6.2
│   │   ├───4.7.2
│   │   ├───4.8
│   │   └───Core
│   │       ├───2.1
│   │       │   └───x64
│   │       ├───2.2
│   │       │   └───x64
│   │       └───3.0
│   │           └───x64
│   ├───DSInternals
│   ├───Empire
│   │   └───Scripts
│   │       └───infosecn1nja_wmic_starfighters
│   ├───Firewall
│   │   └───pfSense
│   ├───ILSpy
│   ├───KaliLive
│   ├───Ncat
│   │   ├───AVSafeVersion
│   │   ├───IntoxWinNetCar
│   │   │   ├───32
│   │   │   └───64
│   │   └───ncat-portable-5.59BETA1
│   ├───NMAP
│   │   ├───NmapLatestInstall
│   │   └───Nmap_Vulners
│   ├───NMAP-Scripts
│   ├───Notepad++
│   ├───PIA
│   ├───ProcessHacker
│   ├───Putty
│   ├───ResourceHacker
│   ├───Splunk
│   ├───VisualStudioCode
│   │   ├───LinuxUbuntu
│   │   └───Windows
│   │       └───DotNetCorePreview
│   ├───VNCViewer
│   ├───WifiDrivers
│   ├───WinDirStat
│   └───WindowsMessageAnalyzer
├───SQL
│   ├───Audit
│   ├───BBQSql
│   ├───BlindSQLInjectionviaBitshifting
│   ├───brute-sqlcipher
│   ├───DSSS
│   ├───DumpMSSQLCreds
│   ├───GeneralScripts
│   ├───MSDat
│   ├───NoSQLMap
│   ├───PowerUpSQL
│   ├───PythonCustomStackedQuery
│   ├───SleuthQL
│   ├───SQLCompactQueryAnalyzer
│   ├───SQLInjectionWiki
│   └───WhiteWidow
├───Squiblydoo
├───SSH
│   ├───SSHAuditor
│   └───SSHLooter
├───SSO
│   └───EspreSSO
├───StaticBinaries
├───StealthDomainRecon
│   └───Vibe
├───Subdomain
│   ├───FindDomain
│   ├───SubdomainEnumeration
│   │   └───AMass
│   └───SubdomainTakeover
│       ├───SDTakeOver
│       ├───SubdomainTakeoverScanner
│       ├───SubR3con
│       ├───Subzy
│       └───TakeOver-v1
├───SymbolicLinkWindows
├───SysInternals
├───SYSMON
│   └───CONFIG
│       ├───OlofHartong
│       │   └───Sysmon-Modular
│       └───SwiftOnSecurityConfig
├───Tails
│   ├───TailsVM
│   └───USBImage
├───TEMP
├───TextToSpeech
│   └───PowerSpeak
├───THP
│   ├───CovertChannels
│   ├───MeterpreterSSH
│   └───THP2Setup
├───ThreatHunting
│   ├───PSHunt
│   └───ThreathunterPlaybook
│       └───WebShellIntelFlorianRoth
├───ThreatModeling
├───ThreatSimulation
│   ├───APTSimulator
│   ├───ATAT
│   ├───MalwLess
│   ├───Metta_attack_simulation
│   └───RedHuntThreadEmulation
├───TokenStealing
│   └───FaceDancer
├───TPLMap
├───Typhoon
├───UACMe
├───UboatHttpBot
├───Unicorn
├───UnkillableProcess
├───UnstoppableService
├───USBArmory
├───VMSS2Core
├───VMWare
│   └───FixCopyPaste
├───VNC
│   └───VNCPassword
├───VoiceClone
├───VOIP
│   └───SipVicious 
fsec_com
│   ├───Linux
│   │   ├───BeRoot
│   │   ├───Capabilities
│   │   ├───CreateShadowFilePassword
│   │   ├───DirtySock
│   │   ├───Enum4Linux
│   │   ├───FSudo
│   │   ├───LinEnum
│   │   ├───LinPwn
│   │   ├───LinuxExploitSuggester
│   │   ├───LinuxPrivChecker
│   │   ├───Orc
│   │   ├───PerlLinuxExploitSuggester
│   │   ├───RootOS
│   │   ├───SudoKiller
│   │   ├───UpTux
│   │   └───Yodo
│   ├───Universal
│   │   └───Privledge-Escalation
│   └───Windows
│       ├───5WaystoFindSystemsRunningDomainAdminProcesses
│       ├───AlwaysInstallElevated
│       ├───BAD_BACKUP_OPERATORS
│       ├───BatchFilePriveEsc
│       ├───CapcomDriverSigning
│       ├───ConstrainedDelegation
│       ├───CREATE_TOKEN_EXAMPLE
│       ├───DllHijacking
│       ├───DLLInjection
│       ├───EasySystem
│       ├───Elevate
│       │   ├───Elevate
│       │   ├───elevate-master
│       ├───Enable_ALL_TOKEN_PERMISSIONS
│       │   └───Set-TokenPriv
│       ├───exploitSuggesterPY
│       ├───FindSystemsRunningDomainAdminProcesses
│       ├───GetSystem
│       │   ├───GetSystemPowershell
│       │   ├───Invoke_potato
│       │   └───PSGetSystem
│       ├───GoldenTicket
│       ├───HotPotato
│       ├───InsecureRegistrySettings
│       ├───Install_Service_To_launch_System
│       ├───Invoke-Potato
│       ├───Invoke_Potato
│       ├───Jaws
│       │   └───JAWS-master
│       ├───JuicyPotato
│       ├───LonelyPotato
│       ├───MigrateProcess
│       ├───NAMED_PIPE_IMPERSONATION
│       ├───Potato
│       ├───Powerless
│       ├───PowerUp
│       │   ├───PowerUp-master
│       │   └───Privesc
│       ├───PrivEsc
│       ├───PrivExchange
│       ├───PSGetSystem
│       ├───PywerView
│       ├───RemoteDLLInjector
│       ├───RottonPotato
│       ├───RottonPotatoNG
│       ├───RottonPotatoNG_correct
│       ├───RunAs
│       ├───Seatbelt
│       │   └───CompiledDotNet4
│       ├───SecondaryLogonHandle
│       ├───SelfElevatingPowershell
│       ├───ServicePermissions
│       ├───SessionGopher
│       │   └───SessionGopher-master
│       ├───Set-TokenPermissions
│       ├───SharpUp
│       │   └───MyBinary
│       ├───Sherlock
│       │   └───Sherlock-master
│       ├───SluiFileHandlerHijackLPE
│       ├───SmashedPotato
│       ├───SysRet
│       ├───Tater
│       ├───TokenPrivModification
│       │   └───SetManually
│       ├───Tokenvator
│       ├───tokenx_privEsc
│       ├───UnquotedServicePaths
│       ├───Watson
│       ├───WESNG
│       ├───WindowPrivEscCheck
│       ├───WindowsExploitSuggester
│       │   └───Windows-Exploit-Suggester-master
│       └───WinEnumPowershell
│           └───WindowsEnum-master
├───ProcessHacker
│   └───PlugIns
├───ProcessInjection
│   ├───GenericProcessInjection
│   ├───PinJectra
│   ├───ProcessInjection_tool
│   ├───PSInject
│   └───RunAs
├───ProxyInfectFilesOnTheFly
├───ProxyPortForwarding
│   ├───Invoke-SocksProxy
│   ├───InvokeSocksProxy
│   └───Piper
├───PSEXEC
│   ├───CSharpPSExec
│   └───ReflectivePSEXEC
├───PsExecViaReflectiveDLL
├───Python
│   ├───BasicScripts
│   │   ├───FTPFuzz
│   │   ├───LearningPython
│   │   ├───NameMash
│   │   ├───SimpleWordPressBruteForce
│   │   └───WebCrawler
│   ├───Oneline
│   │   ├───One-Lin3r
│   │   └───OneLineIzer
│   ├───pcode2code_VBA_Decomiler
│   ├───Py2exe
│   │   ├───Dependancy
│   │   ├───Python2
│   │   ├───Python3
│   │   │   └───WindowsInstaller
│   │   └───Tutorial
│   ├───PyEmbed
│   ├───Pyinstaller
│   ├───pyminifier
│   ├───PyOxidizer
│   ├───Python2.7
│   ├───PythonDotNetBinaryFormat
│   ├───PythonPortScan
│   ├───PythonRegistry
│   ├───PythonToWinExe
│   ├───RTFM_PY
│   └───SMBDoor
├───Rapid7Scans
├───RaspberryPI
│   └───RPI-Hunter
├───RDP
│   ├───RDPPy
│   └───RDP_Caching
├───ReaCom
│   ├───DLLCLSID
│   ├───ExplorerEXEComHijacking
│   ├───MMCCLSID
│   ├───OpenWithExeCOMHijacking
│   ├───PowershellCLSID
│   ├───prncnfg
│   ├───PrnPort
│   ├───RunOnceComHijacking
│   ├───ScripetletFile
│   ├───ScriptletFile
│   ├───URLProtocolComHijack
│   ├───Verclsid
│   ├───WinRM_CMD
│   ├───WinRM_VBS
│   └───xWizardCLSID
├───Recon
│   ├───AltRecon
│   │   └───Censys_Subdo 
──AnotherMimiKatzObfuscation
│   │   ├───DCShadow
│   │   ├───GoldenTicket
│   │   ├───ImpersonatingOfficeUsers
│   │   ├───Invoke_Mimi
│   │   ├───Latest_20190705
│   │   ├───mimikatz-master
│   │   ├───MimikatzDefense
│   │   ├───Mimikatz_obfuscator
│   │   ├───MorphedMimiKatzFromMetame
│   │   ├───NovelJSMimikatzLoader
│   │   ├───ObfuscationTechniques
│   │   ├───PowershellDetectSkeletonKey
│   │   ├───ResetKRBTGT_password_for_goldenTicketMitigation
│   │   ├───Scripts
│   │   │   └───ObfuscateMimikatz
│   │   ├───UncoverDCShadow
│   │   └───Update_AUG17_2019
│   ├───MimikatzFromWebShell
│   ├───MimikatzPowershell
│   │   └───Scripts
│   │       └───ObfuscateMimikatz
│   ├───Mimikittenz
│   ├───MimiPenguin
│   ├───Mitm6
│   ├───MS17-10_Scanner
│   ├───MyKatz
│   ├───MyPresentation_SharpCatUsingHex
│   ├───Net-creds
│   ├───NetKatz
│   ├───NetNTLMtoSilverTicket
│   ├───NetRipper
│   ├───NetworkMiner
│   ├───New folder
│   ├───Nishang
│   ├───NTDSDumpEx
│   ├───NTDSExtract
│   ├───NTLMInjector_ChangePasswordWithHASH
│   ├───NtlmRelayToEWS
│   ├───NTLM_FromRDPFiles
│   ├───Out-MiniDump
│   ├───Outlook
│   ├───p0wnedShell
│   ├───PassTheCache
│   ├───PasswordPopupPowershell
│   ├───PasteHunter
│   ├───PCredz
│   ├───PoshKatz
│   ├───Powermad
│   ├───PowerMemory
│   ├───PowerOps
│   ├───Powershellery_Get-SPN
│   ├───PoweshellMimikatz2
│   ├───ProcSpy
│   ├───PwnedOrNot
│   ├───Pykek
│   ├───PyKerberoastV2
│   ├───PyKerberoastV3
│   ├───PypyKatz
│   ├───PysecDumpMimiAlternative
│   ├───PythonKerberoast
│   ├───RDPSpray
│   ├───RDPThief
│   ├───ReadPst
│   ├───RedSnarf
│   ├───Relayer
│   ├───ResetWindowsPassword
│   ├───Responder
│   │   ├───August2019
│   │   ├───Responder-master
│   │   └───WindowsExes
│   ├───RIDHijacking
│   ├───Rubeus
│   ├───RunAsTI_TrustedInstaller
│   │   ├───AutoIT
│   ├───SafetyKatz
│   ├───SessionGopher
│   ├───ShareSearch
│   ├───SharpDPAPI
│   ├───SharpDump
│   ├───SharpLocker
│   ├───SharpMiniDump
│   ├───Sharproast
│   ├───SharpSniper
│   ├───SharpUp
│   ├───SharpWeb
│   ├───ShowAccountLockout
│   ├───SilverTicket
│   ├───Simple.CredentialsManager
│   ├───SMBBrute
│   │   └───V010
│   ├───SMBetray
│   ├───SprayingToolkit
│   ├───SqlDumper
│   ├───SQLServerHashDumpWithDirTree
│   ├───SubAuth
│   ├───TimMedin
│   ├───TimMedinKerberoast
│   ├───UsbArmoryLanTurtle
│   ├───VaultPasswordView
│   ├───VSOWN
│   ├───WifiPasswords
│   ├───Window10Passwords
│   ├───WindowsDebuggingTools
│   ├───Worse-PDF
│   ├───WPA2
│   └───XPN_BecomingSystem
├───Cryptography
├───CscriptShell
├───CSharpGeneral
│   ├───AmsiScanBypass
│   ├───Bin2Hex
│   ├───Bleak
│   ├───BytecodeApi
│   ├───CompileInMemory
│   │   ├───MemoryModule
│   │   └───Research
│   ├───CoolInjection
│   ├───CSharpCustomStager
│   ├───CsharpDieHarder
│   ├───CsharpEmpire
│   ├───CsharpInjection
│   ├───CSharpProcessInjection
│   ├───CShell
│   ├───CustomStager
│   ├───DotNetDeObfuscation
│   ├───DotNetOerDotNet
│   ├───DotnetToJscript
│   ├───File-Splitter
│   ├───FindCredsSharpCloud
│   ├───GetSEDebugPriviledge
│   ├───Ghostpack csharp stuff
│   ├───ILSpy
│   ├───Interesting
│   ├───NewShellWhoDis
│   ├───Noisette_The nuts-breakerCSharpObfuscator
│   ├───NoPowerShell
│   ├───OffensiveCSharp
│   │   └───Aug2019
│   ├───OleViewDotNet
│   ├───PowershellInCSharp
│   ├───RemoteRegisterDllPSEXEC
│   ├───RunAs
│   ├───SafetyKatz
│   ├───SendKeysToCMD
│   │   └───FindUserPassword_2
│   ├───Sharp-InvokeSmbExec
│   ├───Sharp-invokeWmiExec
│   ├───Sharp-Suite
│   ├───SharpAdidnsdump
│   ├───SharpAllowedToAct
│   ├───SharpCradle
│   ├───SharpDPAPI
│   ├───SharpDump
│   ├───SharpExec
│   ├───SharpFruit
│   ├───SharpPCAP
│   ├───SharpProcEnum
│   ├───SharpShell
│   ├───SharpSpray
│   ├───SingleFileEXE_core
│   ├───TaskAwait
│   ├───TokenImpersonation
│   │   └───1
│   ├───UnmanagedPowershell
│   ├───VigenereSolver
│   ├───WheresMyImplant
│   ├───WinPwn
│   ├───WinXRunPEx86x64
│   ├───WMIProcessWatcher
│   └───WritingPenTestToolsForPenTestersCSharp
├───CuckooSandBox
├───Curl2PS
├───CVE
│   └───CVE-2017-0213 Windows COM Elevation of Privilege Vulnerability
├─── 
PHP)
│   │       ├───Payloads
│   │       │   ├───Anti-Virus
│   │       │   ├───File-Names
│   │       │   ├───Flash
│   │       │   ├───Images
│   │       │   ├───PHPInfo
│   │       │   ├───Zip-Bombs
│   │       │   └───Zip-Traversal
│   │       ├───Usernames
│   │       │   ├───Honeypot-Captures
│   │       │   └───Names
│   │       └───Web-Shells
│   │           ├───FuzzDB
│   │           ├───JSP
│   │           ├───laudanum-0.8
│   │           ├───PHP
│   │           └───WordPress
│   └───Windows-RCE-exploits
├───PcpXray
├───PenTestFrameworks
│   ├───ApFell
│   ├───DsCompromised
│   ├───EasySploit
│   ├───Nishang
│   │   └───Aug2019
│   ├───PowerHub
│   ├───PowershellEmpire
│   ├───PowershellSuite(start-hollow)_fuzzySec
│   ├───Powersploit
│   ├───PTF
│   ├───RedGhost
│   ├───RedTeamRepo
│   ├───SharpSuite
│   ├───Shr3dKit
│   └───WinPwn
├───PenTestingReportSamples
├───PentestReports
├───Persistence
│   ├───CasperStager
│   ├───DLL_Spool
│   ├───DNVM
│   ├───InvisiblePersistence
│   ├───Registry
│   │   ├───Powershell_1
│   │   └───RegistryRunKeys
│   ├───SharpDoor
│   ├───SharPersist
│   ├───SharpHide
│   ├───TheFatRat
│   ├───WhereMyImplantSharpWMI
│   ├───WMI_Implant
│   └───WPadPersistence
├───PETools
│   ├───ImmunityDebugger
│   ├───LordPE
│   ├───Stud_PE
│   └───XVI32
├───Phishing
│   ├───BlackEye
│   ├───GoPhishAndLetsEncrypt
│   ├───Modlishka
│   └───Phishery_BasicAuthCapture
├───PingCastle
│   └───pingcastle-master
│       ├───ADWS
│       ├───Data
│       ├───Graph
│       │   ├───Database
│       │   ├───Export
│       │   ├───Reporting
│       │   └───Rules
│       ├───Healthcheck
│       │   └───Rules
│       ├───misc
│       ├───Properties
│       ├───Report
│       ├───RPC
│       ├───Rules
│       ├───Scanners
│       ├───shares
│       └───template
├───Piper
├───PocketBeagle
├───PortForward
│   └───PSPortForward
├───PortScanning
│   └───agile-hacking
├───PostExploit
│   ├───DarkSpiritz
│   ├───GoodList
│   ├───Nishang
│   ├───ObfuscatedEmpire
│   ├───Orc
│   ├───SharpSploit
│   └───SilentTrinity
├───PowerOpsFDiskYou
├───Powershell
│   ├───CreateCSharpObject
│   ├───CreateExeFromPs1
│   ├───CSharpInPowershell
│   ├───ExecuteAsLoggedInUser
│   ├───FIndAllDomainComputers
│   ├───FindFruitAndMore
│   ├───FlorianRoth
│   ├───GeneralSecurityScript
│   │   └───Misc-Powershell-Scripts-master
│   ├───GetAllMacAddresses
│   ├───Harmj0yPowerUp
│   │   └───PowerSploit
│   ├───InsecurePowershell
│   ├───InsecurePowershellHost
│   ├───Install
│   │   └───Server2003
│   ├───Kmkz
│   ├───NetworkSecurity
│   ├───NoPowerShell
│   ├───Obfuscation
│   │   └───Invoke-Obfuscation
│   ├───P0wnedshell
│   ├───Piper
│   ├───PostExploit
│   │   ├───LogRM
│   │   └───Windows
│   ├───PowerAvails
│   ├───Powermad
│   ├───PowerMemory_GetMemoryCreds
│   ├───PowerOps
│   ├───PowerShdll
│   ├───PowershellArsenal
│   ├───PowershellBasicAuth
│   ├───PowershellFilelessAttacks
│   ├───PowershellGeneral
│   │   ├───JsonParse
│   │   ├───OffensivePowershell
│   │   └───SplitString
│   ├───PowershellInMemoryMagicUnicorn
│   ├───PowershellReverseShell
│   ├───PowershellScripts
│   │   ├───ADEverything
│   │   ├───CheckIfCredentialGuardIsEnabled
│   │   ├───GetAuthenticodes
│   │   ├───GetLoggedOnUsers
│   │   ├───GetShellContent
│   │   ├───Misc-Powershell-Scripts-master
│   │   └───MiscScripts
│   ├───PowershellToExe
│   │   └───GUI
│   ├───PowershellVeryLess
│   ├───PowerSploit
│   ├───PowerThief
│   ├───PowerTools
│   ├───PSKernel-Primitives
│   ├───RedTeamPowershellScripts
│   │   └───RedTeamPowershellScripts-master
│   │       └───scripts
│   ├───SelfEleveating
│   ├───Set-TokenPriv
│   ├───SMBScannerFromPingCastle
│   └───WithoutPowershell
│       ├───PowerlessShell
│       ├───Powershdll
│       ├───PowerShellAsCSharpScript
│       └───READTHIS
├───Powersploit
├───Precompiled_exploits
│   ├───KernelExploits
│   └───WindowsExploits
├───Printer
│   ├───PRET
│   └───Pretty
├───PrivEscalation
│   ├───ExploitPacks
│   │   ├───AusJock_PrivEscalation1
│   │   ├───WHP_WindowsHackingPack
│   │   ├───WindowsKernelExploits
│   │   └───www_bha 
│   │   ├───GetCatalogHashes
│   │   ├───GetPeFeaturr
│   │   ├───LoadInMemoryModule_ps1
│   │   ├───MS_SMBShell
│   │   ├───PowerShellDSCLateralMovement
│   │   ├───PowershellHostFinder
│   │   ├───RemoteCertTrust
│   │   ├───Remote_AT_job
│   │   ├───SignatureVerificationAttack
│   │   ├───TrustedHashes
│   │   ├───UACBypass
│   │   ├───WMINamespaces
│   │   ├───WMIPersistemce
│   │   └───WMIReconandAttack
│   ├───SubTee
│   │   ├───AddInProcess Mimikatz In AddInProcess
│   │   ├───AppDomainManagerHijack
│   │   ├───BatFilePwn
│   │   ├───BuildInMemoryCSharp
│   │   ├───CSharpShellCode
│   │   ├───CsharpStartProcessOnRDP
│   │   ├───Derbycon2019
│   │   ├───DotNetToJScript
│   │   ├───DotNetToJScriptBuildWalkthrough
│   │   ├───DynamicCallRunPE
│   │   ├───DynamicWrapperXDropperCodeRegistrationExample
│   │   ├───enigma0x3 _ Red Teamer and Security Addict
│   │   ├───enigma0x3 _ Red Teamer and Security Addict_files
│   │   ├───GetSystemPS
│   │   ├───HookMessageboxRootCertInstall
│   │   ├───HyperV
│   │   ├───InterceptWebTraffic
│   │   ├───InvokeMinikatzCsharp
│   │   ├───JankyAF
│   │   ├───JavascriptCallExe
│   │   ├───Katz
│   │   ├───LoadMethodScanner
│   │   ├───LoadsDotNETAssemblyIntoScriptHostFromCurrentPath
│   │   ├───LocalKernelDebugger
│   │   ├───MimikatzJS
│   │   ├───MimikatzSct
│   │   ├───MouseKeyLogger
│   │   ├───MsBuildLSAASProcessDump
│   │   ├───msbuildXSLTExecuteFromURL
│   │   ├───Neat
│   │   ├───NeatLittleTrick
│   │   ├───ObfuscatedXSL
│   │   ├───Powershell_Suite
│   │   ├───PoweshellWebshell
│   │   ├───ProcessCommandLineParameters
│   │   ├───RecommendReadingOnDotNet
│   │   ├───RemoteSCT
│   │   ├───ScareTheJitOuttaDefenders
│   │   ├───SCT
│   │   ├───Service
│   │   ├───ShellcodeJS
│   │   ├───ShellcodeStuffedIntoNumeric
│   │   ├───ShellcodeViaXSL
│   │   ├───SubTeeBackupFromSomeone
│   │   ├───SyscallExtractNtDll
│   │   ├───Tasks
│   │   ├───TLSC2
│   │   ├───WMIKatz
│   │   ├───Workflow
│   │   └───XML
│   └───Vysec
│       ├───Cactus
│       ├───RDPInception
│       └───Sharpshooter
├───Hooking
│   └───InfinityHook
├───Hunter
├───ICACLS
├───IIS_LogParser
├───Image
│   ├───BinaryImageWitbPayload
│   └───InvokePsImage
├───InMemoryPowershellWebDavServer
├───Interesting
│   ├───CopyNetCatByteByByte
│   ├───CrlInject
│   ├───FirstBite
│   ├───Hmm
│   ├───MarkBaggett
│   ├───Msf-Autoshell
│   ├───Narsil_SpyAgencyTeasing
│   ├───PandorasBox
│   ├───Sheepl
│   └───WebTTY
├───InterviewQuestions
├───IOC
│   ├───Fenrir
│   └───LOKI
│       └───Install
├───IOT
│   └───DNSRebind
├───IPhoneTesting
│   └───IGoat
├───IPv6
│   ├───Enyx_SNMP_IPV6_Enum
│   ├───IPv6_checker
│   ├───PythonNmap
│   └───TermColor
├───Java
│   ├───Barmie_java_RMI_test
│   ├───JavaScriptDeserialization
│   │   └───GadgetInspector
│   └───New folder
├───Javascript
│   ├───HermesJavaScriptEngine
│   ├───NodeJSSimpleHttpServer
│   └───SimpleSerialize
├───Jenkins
│   ├───Jenkins-Pillage
│   └───JenkinsPasswordSpray
├───JSDotNet
├───JSON
│   ├───JQ_ToMakeJSON_EASY
│   ├───JWTCrack
│   ├───JWT_Attack_Playbook
│   ├───JWT_Toolkit
│   └───The JSON Web Token Toolkit
├───Kalitorify
├───Kerberoasting
├───Keylogger
│   ├───PowershellKeylogger
│   └───SpyKeogger
├───KeyStone
├───LABS
│   ├───EquationGroup
│   └───PurpleLabs
│       └───DanderSpritz Lab
├───LAPS
│   └───LapsToolkit
├───Laptop
├───LateralMovement
│   ├───Invoke-SocksProxy
│   ├───LethalHTA
│   ├───SCShell
│   ├───SharpExec
│   ├───SocatForWindows
│   ├───SSHuttle
│   └───WMISploit
├───LeakScraper
├───Linux
│   ├───DirtyCow
│   ├───FindCredentials
│   ├───FireWalker
│   ├───GetKerberos-KeyTab
│   ├───Hardening
│   │   ├───LinuxHardeningChecklist
│   │   └───Lynis
│   ├───LinEnum
│   ├───LinuxFirewalls
│   ├───LinuxKernalExploits
│   ├───LinuxSwapDigger
│   ├───Linux_rootkit_example
│   └───MaSSH-Enum
├───LOL
│   ├───CMDs
│   │   ├───Appvlp
│   │   ├───AT
│   │   ├───ATBroker
│   │   ├───Bash
│   │   ├───Bginfo
│   │   ├───BitsAdmin
│   │   ├───Cdb
│   │   ├───CertUtil
│   │   ├───CL_Invocation
│   │   ├───CL_Mutexverifiers
│   │   ├───CMD
│   │   ├───CMDKey
│   │   ├─── 
ver
├───Docker
│   ├───Gorsair
│   └───ListOfSecurityTools
├───DomainController
│   ├───DcShadow
│   ├───DumpNTDS.dit
│   └───SMBExec
├───Donut
│   └───DevBrach
├───DonutCS
├───DotNetInterop
├───DotNetToJScript
├───ElasticSearch
├───Encryption
│   └───EncryptStringTool
├───Entropy
│   └───EntroPY
├───Enumeration
│   ├───CommandLists
│   ├───General
│   │   └───AList
│   ├───Linux
│   │   ├───Enum4Linux
│   │   ├───Jalesc
│   │   ├───LinEnum
│   │   ├───LinuxExploitSuggester
│   │   └───PerlLinuxExploitSuggester
│   ├───RidRelay
│   └───Windows
│       ├───BloodHound
│       │   ├───BloodHound
│       │   ├───BloodHoundBinaries
│       │   ├───BloodHoundTools
│       │   ├───BoodHound.Py
│       │   └───SharpHound
│       ├───CrackmapExec
│       ├───DetectExploit
│       ├───GetSharePermissions
│       ├───HostEnum
│       │   └───SharpShared
│       ├───LDAPDomainDump
│       ├───ListDomainStuff
│       ├───NetView
│       ├───PowerSploit
│       ├───Powerview
│       ├───SensitiveDataSearch
│       │   └───SauronEye
│       ├───SMBMap
│       ├───TestAntivirus
│       ├───UserEnum
│       ├───VBSListAllComputersIntheDomain
│       └───WindowsEnum
├───EventLog
│   └───Invoke-Phant0m
├───EvilClippy
├───Exfiltration
│   ├───CloakifyFactory
│   ├───DET
│   ├───DNSExfiltration
│   │   ├───DNSExfiltratorArnox
│   │   ├───PacketWhisper
│   │   └───ReflectiveDnsExfiltration
│   ├───DNSlivery
│   ├───DNSStealv2
│   ├───PowershellAzeriaLabs
│   └───Sharpbox
├───Exploitdb
│   ├───BinSploits
│   ├───ExploitsAndShellcode
│   └───Papers
├───ExploitFolders
│   ├───0x27
│   └───Meltdown
├───FindBufferOverflows
│   └───ZeraTool
├───FIndMyHash
├───FolderPermissions
│   └───Set-permission
├───ForkBombs
├───FREE_VMS
├───Fuzz
│   ├───FuzzBuilder
│   ├───FuzzBunch
│   ├───Fuzzowski
│   └───Unicorefuzz
├───GatherDeviceInfoFromWebsite
│   └───Seeker
├───General
│   └───DonkeysRedTeamScritps
├───GeneratePasswordsFromWebScrape
├───GenerateWordlist
│   └───TheMentalist
├───GetGP-Trashfire
├───Git
│   ├───GitGot
│   └───GitSecrets
├───Gobuster
├───GoldImageScanning
├───Hak5
│   ├───BashBunny
│   ├───LanTurtle
│   ├───PacketSquirrel
│   └───WifiPineapple
├───Heros
│   ├───Arnox
│   │   ├───CSharp
│   │   └───XLL
│   ├───ClappyMonkey
│   ├───DanielBonhannon
│   │   ├───DevSec-Defense
│   │   ├───Invoke-DOSFuscation
│   │   ├───InvokeCradleCrafter
│   │   ├───InvokeObfuscation
│   │   ├───Out-FINcodedCommand
│   │   └───Revoke-Obfuscation
│   ├───FlorianRoth
│   │   └───Sigma
│   ├───FuzzySecurity
│   │   ├───PowershellKernalPrivs
│   │   ├───PowershellMusings
│   │   ├───Sharpsuite
│   │   └───UnixPrivEsc
│   ├───Hasherezade
│   │   ├───Demos
│   │   ├───HollowsHunter
│   │   └───Pe-Sieve
│   ├───Mattifestation
│   │   ├───3076EventExtractor_ps1
│   │   ├───Build
│   │   ├───CertificateCloning
│   │   ├───ConvertSIDtoUsername
│   │   ├───CopyAuthenticode
│   │   ├───DorNetRuntimeManifest
│   │   ├───DotNetDataCollectot
│   │   ├───DropBinaryInCMD
│   │   ├───GetCatalogHashes
│   │   ├───GetPeFeaturr
│   │   ├───LoadInMemoryModule_ps1
│   │   ├───MS_SMBShell
│   │   ├───PowerShellDSCLateralMovement
│   │   ├───PowershellHostFinder
│   │   ├───RemoteCertTrust
│   │   ├───Remote_AT_job
│   │   ├───SignatureVerificationAttack
│   │   ├───TrustedHashes
│   │   ├───UACBypass
│   │   ├───WMINamespaces
│   │   ├───WMIPersistemce
│   │   └───WMIReconandAttack
│   ├───SubTee
│   │   ├───AddInProcess Mimikatz In AddInProcess
│   │   ├───AppDomainManagerHijack
│   │   ├───BatFilePwn
│   │   ├───BuildInMemoryCSharp
│   │   ├───CSharpShellCode
│   │   ├───CsharpStartProcessOnRDP
│   │   ├───Derbycon2019
│   │   ├───DotNetToJScript
│   │   ├───DotNetToJScriptBuildWalkthrough
│   │   ├───DynamicCallRunPE
│   │   ├───DynamicWrapperXDropperCodeRegistrationExample
│   │   ├───enigma0x3 _ Red Teamer and Security Addict
│   │   ├───enigma0x3 _ Red Teamer and Security Addict_files
│   │   ├───GetSystemPS
│   │   ├───HookMessageboxRootCertInstall
│   │   ├───HyperV
│   │   ├───InterceptWebTraffic
│   │   ├───InvokeMinikatzCsharp
│   │   ├───JankyAF
│   │   ├───Javascript 
at2
│   ├───DnsShell
│   ├───DockerDBC2
│   ├───DockerDNSCat
│   ├───DOHC2
│   ├───dropboxC2_DBC2
│   ├───External_c2_framework
│   ├───FudgeC2
│   ├───GCat
│   ├───Gorsh
│   ├───HRShell_httpShell
│   ├───ICMPSH
│   ├───ICMPTunnel
│   ├───ICMP_Tunnel_Python
│   ├───Invoke-PipeShell
│   ├───MacSwiftShell
│   ├───Merlin
│   ├───Nuages
│   ├───OneLogicalMyth_Shell
│   ├───Ping-Pwn
│   ├───PoshC2
│   ├───PowerCat
│   ├───PowerHub
│   ├───PowershellExample
│   ├───Prismatica
│   ├───Pupy
│   ├───RedPeanut
│   ├───ReUseExistingConnectionOneWayStager
│   ├───ReverseShellGen
│   ├───ReverseTCPEncrptedPowershell
│   ├───RSH
│   ├───SharpSocks
│   ├───SilentTrinity
│   ├───Slackor
│   ├───Throwback
│   ├───ThunderShell
│   ├───TinkerShell
│   ├───Tiny-SHell
│   ├───TrevorC2
│   ├───Tunna
│   ├───Udp2Raw
│   ├───UndetectableCSharpShell
│   ├───Websocket-Smuggle
│   ├───WebSocketC2
│   ├───WheresMyImplant
│   └───WinSpy
├───Calculator
├───Cars
│   ├───CANalyzator
│   └───CanZator
├───Certs
│   ├───CarbonCopy
│   ├───CertCheck
│   ├───CertExp
│   └───MkCert
├───Chrome
├───CIRCL_AIL_Framework
├───Cisco
│   └───CCat
├───Clippy
├───Cloud
│   ├───AWS
│   │   ├───Barq
│   │   ├───BucketFinder
│   │   ├───MasS3
│   │   ├───MetaDataService
│   │   ├───Pacu
│   │   ├───PowershelleryS3Finder
│   │   ├───s3Monster
│   │   ├───S3Scanner
│   │   └───TakeFullControl
│   ├───Azure
│   │   └───Microburst
│   ├───CloudBunny
│   └───Google
│       └───BruteBucket
├───CloudFlare
│   └───CloudUnflare
├───CMS
│   ├───CMSeek
│   ├───CMSMap
│   ├───JenikinsPillage
│   ├───malicious-wordpress-plugin
│   └───VulnX
├───CobaltStrike
│   └───SharpCompile
├───CodeInjection
│   ├───AtomBombing
│   ├───Cave_miner
│   ├───DNCI - Dot Net Code Injector
│   ├───Gargoyle
│   ├───GhostHook
│   └───PROPagate
├───ComHijacking
│   ├───Enigma0x3_MessageBox
│   │   └───MiscPowershell_getTasks
│   ├───OleView
│   ├───OleViewDotNet
│   └───PS1Jacker
├───CommandoVM
│   └───MetasploitWindowsInstall
├───Containers
│   └───Trivy
├───Conversion
│   ├───Bin2Hex
│   ├───DLL_to_exe
│   ├───LibPeConv
│   ├───PE_to_Shellcode
│   └───shellconv
├───CradleTest
│   ├───BLueCradleTest
│   └───CradleTest
├───CredentialDumping
│   ├───ADStuff
│   ├───AndrewSpecial
│   ├───AsRepRoast
│   ├───ATPMinidump
│   ├───AzureDumpDomainHashes
│   ├───BadODF
│   ├───BadPdf
│   ├───CaptureEdgeAndIECreds
│   ├───CaptureHashesWithURLFile
│   ├───CheckLocalAdminHash
│   ├───ChromePasswords
│   ├───CloudCopy_DumpAWSDomainHashes
│   ├───CMinidump
│   ├───CompileFromBatch
│   ├───Comsvcs
│   ├───CookieMonster
│   ├───Copy-VSS
│   ├───Crackmapexec
│   ├───CreateMiniDump
│   ├───CreateMiniDumpCPP
│   ├───Cred-Ninja
│   ├───CredCatcher
│   ├───CredentialPhisher
│   │   └───Invoke-CredentialPhisher-master
│   ├───CredentialsFileView
│   ├───CredKing
│   ├───CSharpClipboardWatcher
│   ├───CSharpMimikatz
│   │   └───Subtee
│   ├───CsharpMinidump
│   ├───CSharpPowershellCipboardWatcher
│   ├───DCOM DCERPC Local NTLM Reflection Elevation of Privilege
│   ├───DetectPasswordViaNTLMinFlow
│   ├───DomainPasswordSpray
│   ├───DSInternals
│   ├───Dumpert
│   ├───EFSFiles
│   ├───EternalRelax
│   ├───Evil-SsDp
│   ├───FGDump
│   ├───FindRiskySPNs
│   ├───Get-PasswordFile
│   ├───GetCurrentUsersPassword
│   ├───GetUserSPNs
│   ├───GhostPotato
│   ├───GoldenTicket
│   ├───GrabDump
│   ├───Impacket
│   ├───ImpacketStandAloneWindowExes
│   │   └───impacketWindowsExes
│   ├───ImpacketStaticBinaries
│   ├───ImpDump
│   ├───InternalMonologue
│   ├───InternalMonologueAttack
│   ├───Inveigh
│   ├───InveighZero
│   ├───Invoke-CredentialPhish
│   │   └───PoshWinRT
│   ├───Invoke-DCSync
│   ├───Invoke-TokenManipulation
│   ├───Invoke-WCMDump
│   ├───InvokeKerberoastHarmJoy
│   ├───InvokePasswordAudit
│   ├───InvokePasswordPrompt
│   ├───JenkinsDecrypt
│   ├───KeeThief
│   ├───Kekeo
│   ├───KerberoastingFromSetupToCracking
│   ├───KerberoastNidem
│   ├───KrbRelayx
│   ├───LaZagne
│   ├───LDAPSearch
│   ├───LSASS
│   ├───MailPasswordView
│   ├───MakeMeEnterpriseAdmin
│   ├───MicrosoftOffice NTLMHashesviaFrameset
│   ├───Mimikatz
│   │   ├─ 
├───rcsi
│   │   ├───Reg
│   │   ├───Regasm
│   │   ├───Regedit
│   │   ├───Register-cimprovider
│   │   ├───Regsvcs
│   │   ├───Regsvr32
│   │   ├───Replace
│   │   ├───Rpcping
│   │   ├───Rundll32
│   │   ├───Runonce
│   │   ├───Runscripthelper
│   │   ├───Sc
│   │   ├───Schtasks
│   │   ├───Scriptrunner
│   │   ├───Setupapi
│   │   ├───Shdocvw
│   │   ├───Shell32
│   │   ├───Slmgr
│   │   ├───Sqldumper
│   │   ├───Sqlps
│   │   ├───SQLToolsPS
│   │   ├───Squirrel
│   │   ├───SyncAppvPublishingServer
│   │   ├───Syssetup
│   │   ├───te
│   │   ├───Tracker
│   │   ├───Tttracer
│   │   ├───Update
│   │   ├───Url
│   │   ├───Verclsid
│   │   ├───vsjitdebugger
│   │   ├───Wab
│   │   ├───winrm
│   │   ├───Winword
│   │   ├───Wmic
│   │   ├───Wscript
│   │   ├───Wsreset
│   │   ├───Xwizard
│   │   └───Zipfldr
│   ├───GTFOBLookup
│   ├───LOLBins_OLD
│   └───LOL_new
├───Magecart_check
├───MalwareAnalysis
│   ├───AutopsyAndSleuthKith
│   ├───De4Dot_ NETDeobfuscatorandUnpacker
│   ├───DecodeVBE_DidierStevens
│   ├───DrlTrace
│   ├───Fatt
│   ├───FNord
│   ├───MalTrail
│   ├───PowerShellArsenal
│   ├───RegiiPy
│   ├───SimpleStaticMalwareAnalysis
│   ├───UniPacker
│   ├───Virii_OldVirusSource
│   ├───Volatility
│   │   └───InstallInfo
│   ├───WindowsProcessFundamentals
│   ├───YaraGenerator
│   └───YarGen
├───MemoryInjection
│   ├───CoffeeShot
│   └───PCILeech
├───Misc
│   └───CrashCast
├───MITM
│   ├───Bettercap
│   ├───InjectionArticle
│   ├───Mitm6
│   ├───MITMf
│   ├───Seth_RDP_mitm
│   └───WSUSpectProxy
├───Mobile
│   ├───ApiKeyExractor
│   ├───BypassCertificatePinning
│   ├───EmpireMobile
│   ├───Genymotion
│   │   └───ARM_Translation
│   ├───InSSIDIous
│   ├───PhoneSploit
│   └───TrueGaze
├───MouseJack
├───MovingFiles
│   ├───Bits
│   └───SetupSimpleWebdavServer
├───MsBuild
│   └───MsBuildMacroGenerator
├───NamedPipes
├───NessusScripts
├───New folder
├───NGrok
├───NTFS_permissions
├───NTLMHashCalculator
│   ├───CalculateNTLMHash
│   ├───Microsoft
│   ├───NTLM
│   └───WinHash
├───O365
│   ├───ImpersonatingOffice365UsersWithMimikatz
│   └───UhOh365
├───OAuth
│   ├───OAuthHunting
│   └───PwnAuth
├───Obfuscation
│   ├───AutoIt-Obfuscation_Awsome
│   ├───Basfuscator
│   ├───Bin2Hex
│   ├───CallObfuscator_lookHere
│   ├───CuteIt
│   ├───Demiguise
│   ├───ExeToVBS
│   ├───Gif2xslt_excel
│   ├───HideHTAInHTML
│   ├───Invisi-Shell
│   ├───InvisiShell
│   ├───Invoke-DOSFuscation
│   ├───Ipfuscator
│   ├───IPFuscator (1)
│   ├───Noisy
│   ├───Out-EncodedCommand
│   ├───Out-EncryptedScript
│   ├───Out_compressedDll
│   ├───PEUnion
│   ├───ProcessHide
│   ├───RemoveComments
│   └───StunnexCCodePro_Obfuscator
├───OffensiveDLR
├───Office
│   ├───ADB
│   ├───excel
│   │   └───Excel4Dcom
│   ├───ExcelCellExectionPayload
│   ├───ExcelPasswordCracking
│   ├───Exchange
│   │   ├───EWSToolKit
│   │   ├───ExchangeRelayX
│   │   ├───Invoke_ExchangePrivEsc
│   │   ├───MailSniper
│   │   ├───PrivExchange
│   │   ├───Ruler_exchange_remote_acces
│   │   └───SharpExchange
│   ├───Invoke-NoShell
│   ├───LyncSniper
│   ├───MacroCall
│   ├───MacroCreator
│   ├───MacroPack
│   ├───MacroShop
│   ├───MaliciousMacroMSBuild
│   ├───Ms-Content
│   ├───NotePadExploitFranework
│   ├───Outlook
│   │   ├───OutlookBruteForcer
│   │   └───OutlookToolbox
│   ├───PersistentVTSO_VSToolsForOffice
│   ├───SharePoint
│   │   └───Spartan
│   ├───Skype
│   │   └───LyncSmash
│   ├───VBARunPE
│   └───VBA_ASR_RulesBypass
├───OleView
├───OptOut
├───Oracle
│   ├───Metasploit
│   ├───ODAT
│   └───SQLPlus
├───OSCP
│   ├───AnotherRepo
│   └───OscpRepo
├───OSQuery
│   ├───MitreOSQueries
│   └───MoreWithFleet
├───PacketCapture
│   ├───Clumsy
│   ├───GoodbyeDPI
│   ├───HcxDumptool
│   ├───MicrosoftMessageAnalyzer
│   ├───NetCap
│   ├───NetRipper
│   ├───NmCap
│   ├───PhanTap
│   ├───Raw-Socket-Sniffer
│   ├───RawSocketSniffer
│   ├───SharpPCAP
│   ├───Snifter
│   ├───TCPReplay
│   ├───WinDivert
│   ├───WindivertSharp
│   └───WiresharkPortable
│       └───WiresharkPortable
├───PassTheHash_passCreds
│   ├───Cr3dov3r
│   ├───CredNinja
│   ├───InvokeTheHash
│   ├───PassHuntFindDevicesW

```
