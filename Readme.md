# [所有收集类项目](https://github.com/alphaSeclab/all-my-collection-repos)




# Obfuscate


- 源码混淆和二进制混淆，包括多种语言和多个平台。250+工具和600+文章
- [English Version](https://github.com/alphaSeclab/obfuscation-stuff/blob/master/Readme_en.md)


# 目录
- [C/C++](#a2c94541e733dc4166fe521723fd7c6c)
    - [advobfuscator](#fd70575410bcb9be603da4ba98a90d25) ->  [(1)工具](#f1f170331704c576aae1e098f0536207) [(1)文章](#be4c569839c5a792ee8064cf719559f3)
    - [(5) 工具](#1b245f51ff55d7555771f6f7fc898d9b)
- [dotNet](#84c03c34128be291e0eb12ad0077d463)
    - [de4dot](#c71a6f960ce8f44b0c57a702d37bc62e) ->  [(2)工具](#bba0578aff98faeaa63a64270eeefd70) [(2)文章](#b8e2b8b6b8de8b1efeaa73615af96da9)
    - [obfuscar](#ea08f203ed7f87206ebad95ca3839c9a) ->  [(1)工具](#edf4e9a6332261c63567b43fb268170b)
    - [confuserex](#cc94a1b81d3a80ae7b14dc89bc0099a1) ->  [(3)工具](#99d1eb9438dc7041f9f3c8c295e8697c) [(6)文章](#872cfe60ef217b4f256f1a8cae75b76c)
    - [(7) 工具](#ddbbfd6185056c550c66b7ebb96ff1e3)
    - [(10) 文章](#61b574ca3dfbaad3735d0439ee178369)
- [PowerShell](#30080561801b17f95ec33f3e9c55d207)
    - [invoke-obfuscation](#cdbcb10be06d54ebf90abd82ff0c09a2) ->  [(1)工具](#2da46403d168dd32c2e334a944ceab58) [(7)文章](#0d49b3282f2af5712568ec4c3eb5267b)
    - [(9) 工具](#c3c5478b6d8cedce40ff35a282323b28)
    - [(33) 文章](#8ff1250f3de2e32e3091204bccb98cb9)
- [JavaScript](#577bc949bc0fe3b90ecb3a9c0b1c1ed5)
    - [javascript-obfuscator](#ae1e799313605fde936a5df7fc840791) ->  [(7)工具](#aaf0bc80064e2b45b47ea105845170eb)
    - [baffle](#1c0dcabc5b79a2d8f4899a8e9ca2f36b) ->  [(1)工具](#d15b1412b27cdc2c1e8500ea4f1c4349)
    - [jstillery](#cd762c212e2232c1fd546ee849389e4c) ->  [(1)工具](#349caa785e37967df92949298672c895)
    - [(16) 工具](#2d5d6380eecf903466ebcaf5c05f19b8)
    - [(64) 文章](#7b882dac0338cd3b78b1d2863dd61f4b)
- [LLVM](#d4d25fcc4b3c99e23d0057b7b16b9c31)
    - [obfuscator](#85d98a2a3d190ff4a881fb9fee756981) ->  [(7)工具](#d7e2adf8a51047f3d3cfa9ba79917cd5)
    - [armariris](#245340b4b00837dba6574ffb7b30fbbd) ->  [(1)工具](#b2c0d5760dc0d1049ea3c9f19b8e421c) [(1)文章](#76c686c5eff38ffc4ac7cdc7de5a3e53)
    - [tigress](#6b9473302b708b7d1d113da799f07caa) ->  [(1)工具](#7bef6a80765d31fd23f41c83b88fdfbe)
    - [(10) 工具](#9769f77c9be1d1a84c70892ed86a1b69)
    - [(18) 文章](#f6d3af2c0d95023e3bb1136dc15f1760)
- [Shellcode](#0328c02993be94615d01d76523e36181) ->  [(6)工具](#b5e505df69ad535815bc8de542a3de1d) [(7)文章](#51bac3d27fdaecd233193017ce3d4d63)
- [Bash](#c8158811d160a448a6e6a6882f0264de)
    - [bashfuscator](#f389d3f7f415b93580a50575af01fc6e) ->  [(1)工具](#206537811e24bd1f3cd8b6500a27fb6b) [(1)文章](#7ee0b9cda87c045044c9dfa652d0ffb6)
    - [(2) 工具](#3e62e2c37b74248c36b27d9c4aec23b7)
    - [(3) 文章](#cb790718e94e549a264a6fa6b5c4bfa6)
- [PHP](#f9bf00d928effb18d2a237b5b2e3d5be)
    - [php-obfuscator](#c53e3f5adb0a0312666a2b0a75afc0a7) ->  [(1)工具](#7b9b1b71da2ba028093266e3a5e13f1d)
    - [yakpro-po](#bd9e590d98dbbad1ba3e1578fb60ac17) ->  [(1)工具](#74c2beb1b94aa72829a9eef190c0448b)
    - [optimus](#531f45736bfe4f930def4c40029af8d8) ->  [(2)工具](#5fa6b1a17d15dacdd357631f392762de)
    - [(11) 工具](#3b5533d8ba7e27c1cae2993919aca8a2)
    - [(9) 文章](#b340e8a1c2de74fb198271d3a14e962f)
- [Go](#3ef488c941a5684f3336975b7df1d9b7)
    - [gobfuscate](#3ba2cf7fe57eaa3a81129e99e70fd77b) ->  [(1)工具](#09d794248c8032a5baf2e26147bf78cf)
    - [(1) 工具](#33c1998f141ab7b059ee273fec12f0f7)
- [Office](#2c434d33f0dc3e0b8291a1173d4c863a)
    - [macro_pack](#a675e8b1cf8bafb2abf40ffe1cda6130) ->  [(1)工具](#6695a309cb7dd5c8819776479c0a729f) [(4)文章](#e132b5a30c0eaf8dad0103b5e17dbb54)
    - [maliciousmacrogenerator](#393c2d829a1a1edfb7c804373b8b27d6) ->  [(1)工具](#f9882cc1b17c8003597d7ea53306f505)
    - [(2) 工具](#57f22eded50566be7e5f37c260f42c58)
    - [(16) 文章](#e03c9dba02b3d4e48678bc865877f3c1)
- [Python](#c8be8cbc9e92418ec4eb91a15608969f)
    - [pyminifier](#96c7873e76e7825abcea18eeafdc2afa) ->  [(1)工具](#6037ed842fe61659d01d8d32a1a9170b)
    - [pyarmor](#bab1b5a63fc4e3e2379fad4f45653ef4) ->  [(1)工具](#153179ac6f717a249d21dbba08571bba)
    - [neopi](#710ad15004534cfe5f939655e055b3df) ->  [(1)工具](#fe2b5593a8909ffd901de8cb9861a149) [(2)文章](#4a4963766e96524479d6da2fafc75602)
    - [intensio-obfuscator](#00354d933f4c483d011b1a891e4765c6) ->  [(1)工具](#4db25e79c2c40899d30dbf80d1731c40) [(1)文章](#22a022e9e7d4d4e2f1cee842b1ae8586)
    - [(15) 工具](#b2d59d57c43592a88b115dfb8cc41eb4)
    - [(10) 文章](#eab89cedf1706e7fa90dc6530899c968)
- [Android](#4169178cfbac7e4e03c182600d58d40e)
    - [simplify](#263fb2577d8c578768f677ca34d517bd) ->  [(1)工具](#98a46d73a2511e58cf348049e1c33e5f)
    - [(14) 工具](#5c67e3ac71ff94cd820ed382f96d359f)
    - [(36) 文章](#b8bd64107751a6e271414bd1db39dad1)
- [Apple](#beb0e19614fb8044452ae90b74138f2d)
    - [stcobfuscator](#c9bdd398b84c5ddfede6e2b1a78492aa) ->  [(1)工具](#61ba58d5e151bbeabb078767f437dff5)
    - [(13) 工具](#5c8857ae3e654bd79d8257595e05e229)
    - [(11) 文章](#e9ed9f70cf4150a9f8eb4c2983ea4f6d)
- [Java](#8a996fdcd6ee02c19fd55b09fcd7f9c0)
    - [nullproguard](#96942f90fddd05d4c70ce45a3b3cafb7) ->  [(1)工具](#23fb4af31b14c09156b20c85f7d05953)
    - [(12) 工具](#77ab5d96e4ca64cb5913c61540baa0a6)
    - [(11) 文章](#85a8cd8871da13161f05993c1029e867)
- [CMD](#193bfef38cb82179a6115c52799286fa)
    - [invoke-dosfuscation](#63a2b1b7b26fa06579654d2e39cc2f33) ->  [(1)工具](#9d707b82be5392b16016bfee435f8bf6) [(2)文章](#0b5910871dcca88d837fed60e2de27b1)
    - [(1) 文章](#0738123add9a88b1b717696ad5e3dee5)
- [其他](#978ec8680ae0965ce50c6948e6c740fa)
    - [flare-floss](#3df7c00560baca22e97aa3842646f208) ->  [(1)工具](#da84308c817371ee9a7168afd8c08879) [(1)文章](#524722c4a4090595c6aeb0e245793c2b)
    - [demovfuscator](#816c07719bc43d5fbdb096c357fa52cd) ->  [(1)工具](#be0c014ea3736628b4f9278b5291ac41)
    - [hexraysdeob](#c9354b20e62e3781b0e194d7ac7b2b1a) ->  [(2)工具](#25deb9c341c4f5d5b2c165f85bdc7cb8)
    - [callobfuscator](#a5243005269510c9270b86faaaa708f0) ->  [(1)工具](#1aac846077f425c1c6d557d9b0e9e3b0)
- [恶意代码](#ac6cc2eb18f961bdbfb16151e1f9f686) ->  [(83)文章](#1006f3d956b3a62601532cccb9ef1f8d)
- [新添加-混淆](#48905dbcdd16a4b3ca77dc0193723720) ->  [(78)工具](#40f09a7bfb3cb928c2f912aa6634c775) [(262)文章](#d90fb43c51f97711585f6906a045de96)
- [新添加-反混淆](#b3551c683c83f36d15d84d207f2b1c9b) ->  [(33)工具](#ac795f859fb0f410e2fbda2ef60f407f) [(43)文章](#6b28f0c3d5bfab275e21b6e943063a17)


# <a id="a2c94541e733dc4166fe521723fd7c6c"></a>C/C++


***


## <a id="fd70575410bcb9be603da4ba98a90d25"></a>advobfuscator


### <a id="f1f170331704c576aae1e098f0536207"></a>工具


- [**551**星][13d] [C++] [andrivet/advobfuscator](https://github.com/andrivet/advobfuscator) Obfuscation library based on C++11/14 and metaprogramming


### <a id="be4c569839c5a792ee8064cf719559f3"></a>文章


- 2019.10 [vkremez] [Let's Learn: Dissecting Lazarus Windows x86 Loader Involved in Crypto Trading App Distribution: "snowman" & ADVObfuscator](https://www.vkremez.com/2019/10/lets-learn-dissecting-lazarus-windows.html)




***


## <a id="1b245f51ff55d7555771f6f7fc898d9b"></a>工具


- [**303**星][4y] [C++] [kgretzky/obfusion](https://github.com/kgretzky/obfusion) bfusion - C++ X86 Code Obfuscation Library
- [**182**星][12d] [C++] [fritzone/obfy](https://github.com/fritzone/obfy) A tiny C++ obfuscation framework
- [**130**星][2y] [C++] [urshadow/stringobfuscator](https://github.com/urshadow/stringobfuscator) Compile-time string obfuscation (C++14)
- [**126**星][6m] [C++] [adamyaxley/obfuscate](https://github.com/adamyaxley/obfuscate) Guaranteed compile-time string literal obfuscation header-only library for C++14
- [**39**星][3y] [Assembly] [macmade/obfuscate](https://github.com/macmade/obfuscate) C/C++ machine code obfuscation.


# <a id="84c03c34128be291e0eb12ad0077d463"></a>dotNet


***


## <a id="c71a6f960ce8f44b0c57a702d37bc62e"></a>de4dot


### <a id="bba0578aff98faeaa63a64270eeefd70"></a>工具


- [**4114**星][12d] [C#] [0xd4d/de4dot](https://github.com/0xd4d/de4dot) .NET 反混淆和脱壳
- [**256**星][18d] [C#] [brianhama/de4dot](https://github.com/brianhama/de4dot) .NET deobfuscator and unpacker.


### <a id="b8e2b8b6b8de8b1efeaa73615af96da9"></a>文章


- 2018.01 [MalwareAnalysisForHedgehogs] [Malware Analysis - When De4dot fails, Removing Anti Tamper from NullShield](https://www.youtube.com/watch?v=1RNcZpBLZHs)
- 2018.01 [MalwareAnalysisForHedgehogs] [Malware Analysis - Deobfuscating .NET Assemblies with De4Dot](https://www.youtube.com/watch?v=0DV1bhnnOyM)




***


## <a id="ea08f203ed7f87206ebad95ca3839c9a"></a>obfuscar


### <a id="edf4e9a6332261c63567b43fb268170b"></a>工具


- [**811**星][12d] [C#] [obfuscar/obfuscar](https://github.com/obfuscar/obfuscar) Open source obfuscation tool for .NET assemblies




***


## <a id="cc94a1b81d3a80ae7b14dc89bc0099a1"></a>confuserex


### <a id="99d1eb9438dc7041f9f3c8c295e8697c"></a>工具


- [**312**星][13d] [C#] [xenocoderce/neo-confuserex](https://github.com/xenocoderce/neo-confuserex) Updated ConfuserEX, an open-source, free obfuscator for .NET applications
- [**207**星][4m] [C#] [bedthegod/confuserex-mod-by-bed](https://github.com/bedthegod/confuserex-mod-by-bed) Beds Protector | Best free obfuscation out right now
- [**196**星][4y] [C#] [codeshark-dev/nofuserex](https://github.com/codeshark-dev/nofuserex) Free deobfuscator for ConfuserEx.


### <a id="872cfe60ef217b4f256f1a8cae75b76c"></a>文章


- 2019.08 [markmotig] [I am loving ConfuserEx/Neo-ConfuserEx for C# obfuscation](https://medium.com/p/eb7d7eb0e4d1)
- 2019.08 [markmotig] [Neo-ConfuserEX the successor of ConfuserEX for obfuscation](https://medium.com/p/b8a208aff923)
- 2019.08 [markmotig] [Quick Introduction to ConfuserEX](https://medium.com/p/ce373553138f)
- 2017.12 [360] [Recam终极版：如何一步步脱掉ConfuserEx保护壳（下）](https://www.anquanke.com/post/id/90174/)
- 2017.12 [360] [Recam终极版：如何一步步脱掉ConfuserEx保护壳（上）](https://www.anquanke.com/post/id/89730/)
- 2017.12 [talosintelligence] [脱自定义 ConfuserEx 壳, 分析其 Payload](http://blog.talosintelligence.com/2017/12/recam-redux-deconfusing-confuserex.html)




***


## <a id="ddbbfd6185056c550c66b7ebb96ff1e3"></a>工具


- [**131**星][2y] [C#] [xenocoderce/noisette-obfuscator](https://github.com/xenocoderce/noisette-obfuscator) An Obfuscator for .NET assembly
- [**73**星][16d] [C#] [holly-hacker/dnspy.extension.holly](https://github.com/holly-hacker/dnspy.extension.holly) A dnSpy extension to aid reversing of obfuscated assemblies
- [**47**星][5m] [rustemsoft/skater-.net-obfuscator](https://github.com/rustemsoft/skater-.net-obfuscator) 一个用于.net代码保护的混淆工具
- [**37**星][2y] [C#] [codeofdark/panda-obfuscator](https://github.com/codeofdark/panda-obfuscator) PandaObfuscator an simple Obfuscator, free, OpenSource for .Net Applications
- [**24**星][4y] [C#] [tum-i22/vot4cs](https://github.com/tum-i22/vot4cs) C#虚拟化混淆工具
- [**19**星][4m] [C#] [dentrax/z00bfuscator](https://github.com/dentrax/z00bfuscator) Z00bfuscator is the simple, open-source, cross-platform obfuscator for .NET Assemblies built on .NET Core
- [**None**星][notprab/.net-deobfuscator](https://github.com/notprab/.net-deobfuscator) Lists of .NET Deobfuscator and Unpacker (Open Source)


***


## <a id="61b574ca3dfbaad3735d0439ee178369"></a>文章


- 2016.12 [securityblog] [Open source .NET deobfuscator and unpacker](http://securityblog.gr/3883/open-source-net-deobfuscator-and-unpacker/)
- 2013.11 [digitaloperatives] [Programmatic String Deobfuscation in .NET Malware](https://www.digitaloperatives.com/2013/11/27/programmatic-string-deobfuscation-in-net-malware/)
- 2013.11 [digitaloperatives] [Programmatic String Deobfuscation in .NET Malware](https://digitaloperatives.blogspot.com/2013/11/DotNet-String-Deobfuscation.html)
- 2013.10 [forcepoint] [PHP.net compromised, serving up obfuscated content](https://www.forcepoint.com/blog/security-labs/phpnet-compromised-serving-obfuscated-content)
- 2013.04 [pediy] [[翻译].NET混淆器Dotfuscator的五大看点](https://bbs.pediy.com/thread-168353.htm)
- 2013.03 [pediy] [[原创].Net 下的混淆器作用原理](https://bbs.pediy.com/thread-163781.htm)
- 2010.09 [pediy] [[原创]DotNet混淆后程序的破解](https://bbs.pediy.com/thread-120805.htm)
- 2006.12 [pediy] [从reflector实现看.net的混淆与反混淆技术[原创]](https://bbs.pediy.com/thread-37217.htm)
- 2006.11 [pediy] [[原创]数据结构在.net反流程混淆中的应用[看雪学院2006金秋读书季]](https://bbs.pediy.com/thread-34505.htm)
- 2004.10 [sans] [Microsoft ASP.NET vulnerability, URL obfuscation, more MD5](https://isc.sans.edu/forums/diary/Microsoft+ASPNET+vulnerability+URL+obfuscation+more+MD5/329/)


# <a id="30080561801b17f95ec33f3e9c55d207"></a>PowerShell


***


## <a id="cdbcb10be06d54ebf90abd82ff0c09a2"></a>invoke-obfuscation


### <a id="2da46403d168dd32c2e334a944ceab58"></a>工具


- [**1450**星][1y] [PS] [danielbohannon/invoke-obfuscation](https://github.com/danielbohannon/invoke-obfuscation) PowerShell Obfuscator


### <a id="0d49b3282f2af5712568ec4c3eb5267b"></a>文章


- 2018.08 [cqureacademy] [Going Undercover With Invoke-Obfuscation](https://cqureacademy.com/blog/penetration-testing/invoke-obfuscation)
- 2017.12 [danielbohannon] [The Invoke-Obfuscation Usage Guide :: Part 2](http://www.danielbohannon.com/blog-1/2017/12/2/the-invoke-obfuscation-usage-guide-part-2)
- 2017.12 [danielbohannon] [Invoke-Obfuscation 使用指南(Part 1)](http://www.danielbohannon.com/blog-1/2017/12/2/the-invoke-obfuscation-usage-guide)
- 2017.11 [pcsxcetrasupport3] [De-obfuscating a PowerShell Script Obfuscated by Invoke-Obfuscation](https://pcsxcetrasupport3.wordpress.com/2017/11/11/de-obfuscating-a-powershell-script-obfuscated-by-invoke-obfuscation/)
- 2017.01 [trustedsec] [TrustedSec Security Podcast Ep: 2.5 – Mirai, Rudy Cyber head, ransomware, Invoke-Obfuscation and more!](https://www.trustedsec.com/2017/01/trustedsec-security-podcast-ep-2-5-mirai-rudy-cyber-head-ransomware-invoke-obfuscation/)
- 2016.10 [danielbohannon] [Invoke-Obfuscation v1.1 (coming Sunday, Oct 9)](http://www.danielbohannon.com/blog-1/2016/10/1/invoke-obfuscation-v11-release-sunday-oct-9)
- 2016.09 [danielbohannon] [Invoke-Obfuscation :: Public Release](http://www.danielbohannon.com/blog-1/2016/9/25/invoke-obfuscation-public-release)




***


## <a id="c3c5478b6d8cedce40ff35a282323b28"></a>工具


- [**505**星][2y] [PS] [danielbohannon/invoke-cradlecrafter](https://github.com/danielbohannon/invoke-cradlecrafter) PowerShell Remote Download Cradle Generator & Obfuscator
- [**451**星][2y] [PS] [danielbohannon/revoke-obfuscation](https://github.com/danielbohannon/revoke-obfuscation) PowerShell Obfuscation Detection Framework
- [**204**星][5m] [PS] [r3mrum/psdecode](https://github.com/r3mrum/psdecode) PowerShell script for deobfuscating encoded PowerShell scripts
- [**143**星][4m] [Py] [cbhue/pyfuscation](https://github.com/cbhue/pyfuscation) Obfuscate powershell scripts by replacing Function names, Variables and Parameters.
- [**89**星][3y] [PS] [danielbohannon/out-fincodedcommand](https://github.com/danielbohannon/out-fincodedcommand) POC Highlighting Obfuscation Techniques used by FIN threat actors based on cmd.exe's replace functionality and cmd.exe/powershell.exe's stdin command invocation capabilities
- [**42**星][11d] [Py] [cwolff411/powerob](https://github.com/cwolff411/powerob) An on-the-fly Powershell script obfuscator meant for red team engagements. Built out of necessity.
- [**13**星][6m] [PS] [gh0x0st/invoke-psobfuscation](https://github.com/gh0x0st/invoke-psobfuscation) A Red and Blue team introduction into PowerShell obfuscation
- [**3**星][1y] [Py] [3nc0d/powershell-obfuscator](https://github.com/3nc0d/powershell-obfuscator) Powerful script for logical obfuscation of powershell scripts
- [**1**星][11m] [Py] [secureyourself7/powershell_code_basic_obfuscation](https://github.com/secureyourself7/powershell_code_basic_obfuscation) Simple PowerShell Script Code Obfuscator written in Python


***


## <a id="8ff1250f3de2e32e3091204bccb98cb9"></a>文章


- 2019.11 [freebuf] [分析银行木马的恶意快捷方式及混淆的Powershell](https://www.freebuf.com/articles/network/215898.html)
- 2019.11 [4hou] [Unit42发布powershell自动反混淆工具](https://www.4hou.com/tools/21411.html)
- 2019.10 [HackersOnBoard] [Black Hat USA 2017 Revoke Obfuscation PowerShell Obfuscation Detection And Evasion Using Science](https://www.youtube.com/watch?v=7gBkczIWvUo)
- 2019.07 [PowerShellConferenceEU] [Daniel Bohannon - PesterSec: Using Pester & ScriptAnalyzer to Detect Obfuscated PowerShell](https://www.youtube.com/watch?v=qYgCLzBaVaw)
- 2019.06 [beny] [Weaponization: Howto Fully Undetectable Empire Powershell MS macro (VBA obfuscation & Stomping)](https://www.peerlyst.com/posts/weaponization-howto-fully-undetectable-empire-powershell-ms-macro-vba-obfuscation-and-stomping-beny-bertin)
- 2019.04 [arxiv] [[1904.10270] PowerDrive: Accurate De-Obfuscation and Analysis of PowerShell Malware](https://arxiv.org/abs/1904.10270)
- 2019.03 [xednaps] [WannaMine dropper – Powershell Obfuscation](https://www.xednaps.com/2019/03/26/wannamine-dropper-powershell-obfuscation/)
- 2019.02 [4hou] [Powershell混淆——使用安全字符串](http://www.4hou.com/technology/13672.html)
- 2019.01 [sans] ["Invoke Obfuscation: PowerShell obFUsk8tion Techniques & How To (Try To) D""e'Tec'T 'Th'+'em' "](https://www.sans.org/cyber-security-summit/archives/file/summit_archive_1492186586.pdf)
- 2018.12 [4hou] [尝试根据字符频度检测Powershell混淆](http://www.4hou.com/web/15163.html)
- 2018.11 [yoroi] [Dissecting the Mindscrew-Powershell Obfuscation](https://blog.yoroi.company/research/dissecting-the-mindscrew-powershell-obfuscation/)
- 2018.11 [pediy] [[翻译]Powershell 代码反混淆技术研究](https://bbs.pediy.com/thread-248034.htm)
- 2018.10 [aliyun] [反混淆powershell](https://xz.aliyun.com/t/2923)
- 2018.10 [endgame] [Deobfuscating PowerShell: Putting the Toothpaste Back in the Tube](https://www.endgame.com/blog/technical-blog/deobfuscating-powershell-putting-toothpaste-back-tube)
- 2018.08 [aliyun] [反混淆Emotet powershell payload](https://xz.aliyun.com/t/2517)
- 2018.08 [360] [解混淆Emotet powershell payload](https://www.anquanke.com/post/id/153537/)
- 2018.06 [PowerShellConferenceEU] [Revoke-Obfuscation: PowerShell Obfuscation Detection (And Evasion) Using Science - Daniel Bohannon](https://www.youtube.com/watch?v=UVbbpZiYnTs)
- 2018.02 [dissectmalware] [Obfuscated PowerShell Script 2 – Emotet](https://dissectmalware.wordpress.com/2018/02/24/obfuscated-powershell-script-2-emotet/)
- 2017.12 [4hou] [PSAmsi：四两拨千斤实现PowerShell代码混淆隐藏](http://www.4hou.com/penetration/8915.html)
- 2017.12 [4hou] [基于AST抽象语法树的PowerShell代码混淆技术](http://www.4hou.com/penetration/9002.html)
- 2017.11 [360] [基于抽象语法树的PowerShell混淆技术](https://www.anquanke.com/post/id/87329/)
- 2017.11 [cobbr] [AbstractSyntaxTree-Based PowerShell Obfuscation](https://cobbr.io/AbstractSyntaxTree-Based-PowerShell-Obfuscation.html)
- 2017.09 [jaapbrasser] [Decipher obfuscated URLs with PowerShell](https://www.jaapbrasser.com/decipher-obfuscated-urls-with-powershell/)
- 2017.09 [softscheck] [Deobfuscating VBA & PowerShell Scripts of an Emotet Trojan Downloader](https://www.softscheck.com/en/deobfuscating-vba-powershell-scripts-of-an-emotet-trojan-downloader/)
- 2017.08 [360] [根据powershell语言的特性来混淆代码的方法与原理](https://www.anquanke.com/post/id/86637/)
- 2017.08 [n0where] [PowerShell Obfuscation Detection Framework: Revoke-Obfuscation](https://n0where.net/powershell-obfuscation-detection-framework-revoke-obfuscation)
- 2017.07 [fireeye] [Revoke-Obfuscation: PowerShell Obfuscation Detection Using Science](https://www.fireeye.com/blog/threat-research/2017/07/revoke-obfuscation-powershell.html)
- 2017.06 [] [无文件应用程序白名单绕过以及 Powershell 混淆](https://4n6ir.com/2017/06/21/fileless-application-whitelist-bypass-and-powershell-obfuscation/)
- 2017.06 [mikefrobbins] [Simple Obfuscation with PowerShell using Base64 Encoding](http://mikefrobbins.com/2017/06/15/simple-obfuscation-with-powershell-using-base64-encoding/)
- 2017.06 [freebuf] [Powershell编码与混淆](http://www.freebuf.com/sectool/136328.html)
- 2017.04 [cobbr] [Trying to Detect PowerShell Obfuscation Through Character Frequency](https://cobbr.io/ObfuscationDetection.html)
- 2017.03 [danielbohannon] [PowerShell执行参数混淆](http://www.danielbohannon.com/blog-1/2017/3/12/powershell-execution-argument-obfuscation-how-it-can-make-detection-easier)
- 2017.03 [cobbr] [ObfuscatedEmpire - Use an obfuscated, in-memory PowerShell C2 channel to evade AV signatures](https://cobbr.io/ObfuscatedEmpire.html)


# <a id="577bc949bc0fe3b90ecb3a9c0b1c1ed5"></a>JavaScript


***


## <a id="ae1e799313605fde936a5df7fc840791"></a>javascript-obfuscator


### <a id="aaf0bc80064e2b45b47ea105845170eb"></a>工具


- [**4393**星][12d] [TS] [javascript-obfuscator/javascript-obfuscator](https://github.com/javascript-obfuscator/javascript-obfuscator) 一个强大的JavaScript和Node.js模糊器，包含为源代码提供保护的各种特性
- [**355**星][9d] [TS] [javascript-obfuscator/webpack-obfuscator](https://github.com/javascript-obfuscator/webpack-obfuscator) javascript-obfuscator plugin for Webpack
- [**107**星][4m] [JS] [javascript-obfuscator/javascript-obfuscator-ui](https://github.com/javascript-obfuscator/javascript-obfuscator-ui) A web UI to the JavaScript Obfuscator node.js package.
- [**70**星][1m] [JS] [javascript-obfuscator/gulp-javascript-obfuscator](https://github.com/javascript-obfuscator/gulp-javascript-obfuscator) Gulp plugin for javascript-obfuscator package.
- [**40**星][12d] [JS] [javascript-obfuscator/obfuscator-loader](https://github.com/javascript-obfuscator/obfuscator-loader) A webpack loader for obfuscating single modules using javascript-obfuscator
- [**33**星][8m] [JS] [tomasz-oponowicz/grunt-javascript-obfuscator](https://github.com/tomasz-oponowicz/grunt-javascript-obfuscator) Obfuscates JavaScript files using amazing javascript-obfuscator.
- [**16**星][4m] [JS] [javascript-obfuscator/grunt-contrib-obfuscator](https://github.com/javascript-obfuscator/grunt-contrib-obfuscator) Grunt plugin for the javascript-obfuscator package.




***


## <a id="1c0dcabc5b79a2d8f4899a8e9ca2f36b"></a>baffle


### <a id="d15b1412b27cdc2c1e8500ea4f1c4349"></a>工具


- [**1665**星][3y] [JS] [camwiegert/baffle](https://github.com/camwiegert/baffle) 一个用于混淆和显示DOM元素中的文本的小型javascript库。




***


## <a id="cd762c212e2232c1fd546ee849389e4c"></a>jstillery


### <a id="349caa785e37967df92949298672c895"></a>工具


- [**530**星][1y] [JS] [mindedsecurity/jstillery](https://github.com/mindedsecurity/jstillery) Advanced JavaScript Deobfuscation via Partial Evaluation




***


## <a id="2d5d6380eecf903466ebcaf5c05f19b8"></a>工具


- [**314**星][10m] [JS] [hynekpetrak/malware-jail](https://github.com/hynekpetrak/malware-jail) 半自动Javascript恶意软件分析的沙箱，去混淆和Payload提取
- [**269**星][12d] [JS] [lelinhtinh/de4js](https://github.com/lelinhtinh/de4js) JavaScript Deobfuscator and Unpacker
- [**207**星][30d] [JS] [chichou/etacsufbo](https://github.com/chichou/etacsufbo) 基于 AST 变换的简易 Javascript 反混淆辅助工具
- [**85**星][29d] [JS] [rapid7/jsobfu](https://github.com/rapid7/jsobfu) Obfuscate JavaScript (beyond repair) with Ruby
- [**83**星][4m] [JS] [zswang/jfogs](https://github.com/zswang/jfogs) JavaScript Obfuscator
- [**79**星][5m] [HTML] [szimeus/evalyzer](https://github.com/szimeus/evalyzer) Using WinDBG to tap into JavaScript and help with deobfuscation and browser exploit detection
- [**73**星][17d] [TS] [geeksonsecurity/illuminatejs](https://github.com/geeksonsecurity/illuminatejs) IlluminateJs is a static JavaScript deobfuscator
- [**40**星][14d] [JS] [anseki/gnirts](https://github.com/anseki/gnirts) Obfuscate string literals in JavaScript code.
- [**35**星][7m] [PHP] [propaganistas/email-obfuscator](https://github.com/propaganistas/email-obfuscator) A text filter for automatic email obfuscation using the well-established Javascript and a CSS fallback:
- [**26**星][1y] [JS] [alexhorn/defendjs](https://github.com/alexhorn/defendjs) A free and open source JavaScript and Node.js obfuscator.
- [**26**星][4m] [Py] [aurore54f/jast](https://github.com/aurore54f/jast) Syntactic detection of malicious (obfuscated) JavaScript files
- [**23**星][1y] [JS] [veggiedefender/marveloptics_malware](https://github.com/veggiedefender/marveloptics_malware) Deobfuscated + reverse engineered javascript malware
- [**10**星][7y] [Py] [lucianogiuseppe/js-auto-deobfuscator](https://github.com/lucianogiuseppe/js-auto-deobfuscator) JSADO automatically deobfuscates javascript scripts which use eval or some other function
- [**2**星][8m] [Haskell] [prate658/hajas](https://github.com/prate658/hajas) JavaScript deobfuscator
- [**2**星][3m] [JS] [filipemgs/poisonjs](https://github.com/filipemgs/poisonjs) PoisonJS - De-obfuscate eval-based JavaScript obfuscation with monkey-patched eval(-like) functions.
- [**1**星][2y] [JS] [enzou/javascript2img_decoder](https://github.com/enzou/javascript2img_decoder) Decoder for JavaScript code which was obfuscated by JavaScript2img


***


## <a id="7b882dac0338cd3b78b1d2863dd61f4b"></a>文章


- 2019.09 [antoinevastel] [Benchmarking our JavaScript obfuscator](https://antoinevastel.com/javascript/2019/09/10/benchmarking-obfuscator.html)
- 2019.09 [antoinevastel] [Improving our homemade JavaScript obfuscator](https://antoinevastel.com/javascript/2019/09/09/improving-obfuscator.html)
- 2019.09 [antoinevastel] [A simple homemade JavaScript obfuscator](https://antoinevastel.com/javascript/2019/09/04/home-made-obfuscator.html)
- 2019.09 [bromium] [Deobfuscating Ostap: TrickBot’s 34,000 Line JavaScript Downloader](https://www.bromium.com/deobfuscating-ostap-trickbots-javascript-downloader/)
- 2019.08 [SecurityWeekly] [Deobfuscating JavaScript to Investigate Phishing Domains - PSW #617](https://www.youtube.com/watch?v=e0Dd0znmNas)
- 2019.04 [freebuf] [如何使用JavaScript混淆来躲避AV](https://www.freebuf.com/articles/web/199060.html)
- 2019.04 [netsparker] [Announcing the Deobfuscating JavaScript White Paper](https://www.netsparker.com/blog/web-security/announcing-deobfuscating-javascript-white-paper/)
- 2019.03 [360] [恶意代码使用JavaScript混淆规避反病毒程序](https://www.anquanke.com/post/id/172984/)
- 2019.03 [yoroi] [Evading AV with JavaScript Obfuscation](https://blog.yoroi.company/research/evading-av-with-javascript-obfuscation/)
- 2019.01 [fuzzysecurity] [Angler EK JavaScript Deobfuscation: The Emperor Has No Clothes](http://fuzzysecurity.com/tutorials/22.html)
- 2018.10 [sucuri] [Obfuscated JavaScript Cryptominer](https://blog.sucuri.net/2018/10/obfuscated-javascript-cryptominer.html)
- 2018.04 [pediy] [[翻译]通过Javascript中的CFI实现混淆阻止解密分析](https://bbs.pediy.com/thread-225748.htm)
- 2017.07 [freebuf] [从javascript脚本混淆说起](http://www.freebuf.com/articles/system/140062.html)
- 2017.06 [vkremez] ["Amazon Order Cancelled": Weight Loss Spam Campaign via Obfuscated JavaScript](https://www.vkremez.com/2017/06/amazon-order-cancelled-weight-loss-spam.html)
- 2017.05 [netskope] [Obfuscated Javascript Malware using Cloud Services](https://www.netskope.com/blog/obfuscated-javascript-malware-using-cloud-services/)
- 2017.05 [intrinsec] [Malware : désobfuscation d’un Javascript encodé](https://securite.intrinsec.com/2017/05/16/exercice-de-desobfuscation-dun-jse-par-le-cert-intrinsec/)
- 2017.04 [ColinHardy] [Emotet JavaScript dropper deobfuscation and analysis](https://www.youtube.com/watch?v=13rX3cLUHhU)
- 2017.03 [sans] [Nicely Obfuscated JavaScript Sample ](https://isc.sans.edu/forums/diary/Nicely+Obfuscated+JavaScript+Sample/22227/)
- 2017.02 [metabrik] [Deobfuscate JavaScript from the command line made easy](https://www.metabrik.org/blog/2017/02/14/deobfuscate-javascript-from-the-command-line-made-easy/)
- 2017.01 [CodeColoristX] [一例简易静态 Javascript 反混淆](https://blog.chichou.me/%E4%B8%80%E4%BE%8B%E7%AE%80%E6%98%93%E9%9D%99%E6%80%81-javascript-%E5%8F%8D%E6%B7%B7%E6%B7%86-d856f6e5a9b4)
- 2016.11 [netskope] [Manually Deobfuscating Strings Obfuscated in Malicious JavaScript Code](https://www.netskope.com/blog/manually-deobfuscating-strings-obfuscated-malicious-javascript-code/)
- 2016.08 [sans] [Spam with Obfuscated Javascript](https://isc.sans.edu/forums/diary/Spam+with+Obfuscated+Javascript/21415/)
- 2016.07 [doyler] [JavaScript Deobfuscation (ABCTF2016 – JS Pls)](https://www.doyler.net/security-not-included/javascript-deobfuscation-abctf)
- 2016.06 [] [Automatically deobfuscate eval packed javascript with node.js](https://medium.com/p/664af9c2d62)
- 2016.06 [mcafee] [Locky Ransomware Hides Under Multiple Obfuscated Layers of JavaScript](https://www.mcafee.com/blogs/other-blogs/mcafee-labs/locky-ransomware-hides-under-multiple-obfuscated-layers-of-javascript/)
- 2016.06 [mcafee] [Locky Ransomware Hides Under Multiple Obfuscated Layers of JavaScript](https://securingtomorrow.mcafee.com/mcafee-labs/locky-ransomware-hides-under-multiple-obfuscated-layers-of-javascript/)
- 2016.05 [jeffsoh] [Excellent Manual Javascript Deobfuscation Walk through](http://jeffsoh.blogspot.com/2016/05/excellent-manual-javascript.html)
- 2016.05 [theevilbit] [JavaScript deobfuscation: criminal case against you.wsf](http://theevilbit.blogspot.com/2016/05/javascript-deobfuscation-criminal-case.html)
- 2016.03 [freebuf] [技术分享：几种常见的JavaScript混淆和反混淆工具分析实战](http://www.freebuf.com/articles/web/97945.html)
- 2016.02 [jeffsoh] [JavaScript Deobfuscation Update](http://jeffsoh.blogspot.com/2016/02/javascript-deobfuscation-update.html)
- 2016.02 [sans] [Locky: JavaScript Deobfuscation](https://isc.sans.edu/forums/diary/Locky+JavaScript+Deobfuscation/20749/)
- 2016.02 [sans] [More Malicious JavaScript Obfuscation](https://isc.sans.edu/forums/diary/More+Malicious+JavaScript+Obfuscation/20703/)
- 2016.01 [sans] [JavaScript Deobfuscation Tool](https://isc.sans.edu/forums/diary/JavaScript+Deobfuscation+Tool/20619/)
- 2016.01 [360] [Javascript Deobfuscator：JavaScript反混淆工具更新](https://www.anquanke.com/post/id/83275/)
- 2015.12 [] [estools 辅助反混淆 Javascript](http://www.91ri.org/14876.html)
- 2015.09 [trustwave] [Lessons in Spam JavaScript Obfuscation Layers](https://www.trustwave.com/Resources/SpiderLabs-Blog/Lessons-in-Spam-JavaScript-Obfuscation-Layers/)
- 2015.08 [knownsec] [使用 estools 辅助反混淆 Javascript](http://blog.knownsec.com/2015/08/use-estools-aid-deobfuscate-javascript/)
- 2013.09 [pwndizzle] [How not to Obfuscate your Javascript](http://pwndizzle.blogspot.com/2013/09/how-not-to-obfuscate-your-javascript.html)
- 2013.02 [jeffsoh] [JavaScript Deobfuscation](http://jeffsoh.blogspot.com/2013/02/javascript-deobfuscation.html)
- 2012.10 [defensecode] [Diving into recent 0day Javascript obfuscations](http://blog.defensecode.com/2012/10/diving-into-recent-0day-javascript.html)
- 2012.09 [techyzilla] [Better Javascript Obfuscating Method To Protect Your Code](https://techyzilla.blogspot.com/2012/09/better-javascript-obfuscating-method-to-protect-your-code.html)
- 2012.07 [jeffsoh] [JavaScript unescape obfuscated code](http://jeffsoh.blogspot.com/2012/07/javascript-unescape-obfuscated-code.html)
- 2012.06 [sans] [Using JSDetox to Analyze and Deobfuscate Javascript](https://isc.sans.edu/forums/diary/Using+JSDetox+to+Analyze+and+Deobfuscate+Javascript/13558/)
- 2012.04 [hiddenillusion] [Deobfuscating JavaScript with Malzilla](http://hiddenillusion.blogspot.com/2012/04/deobfuscating-javascript-with-malzilla.html)
- 2012.04 [sans] [Blacole's obfuscated JavaScript](https://isc.sans.edu/forums/diary/Blacoles+obfuscated+JavaScript/13051/)
- 2012.03 [sans] [Phishing with obfuscated javascript, shellcode and malware](https://isc.sans.edu/forums/diary/Phishing+with+obfuscated+javascript+shellcode+and+malware/12700/)
- 2012.01 [sans] [The tale of obfuscated JavaScript continues](https://isc.sans.edu/forums/diary/The+tale+of+obfuscated+JavaScript+continues/12313/)
- 2011.12 [sans] [V8 as an Alternative to SpiderMonkey for JavaScript Deobfuscation](https://isc.sans.edu/forums/diary/V8+as+an+Alternative+to+SpiderMonkey+for+JavaScript+Deobfuscation/12157/)
- 2011.07 [rapid7] [Javascript Obfuscation in Metasploit](https://blog.rapid7.com/2011/07/08/jsobfu/)
- 2011.03 [talosintelligence] [Attack Obfuscation - Not Just For JavaScript](https://blog.talosintelligence.com/2011/03/attack-obfuscation-not-just-for.html)
- 2010.12 [talosintelligence] [Detecting Obfuscated Malicious JavaScript with Snort and Razorback](https://blog.talosintelligence.com/2010/12/detecting-obfuscated-malicious.html)
- 2010.09 [kkotowicz] [Creating, obfuscating and analyzing malware JavaScript](https://www.slideshare.net/kkotowicz/owaspmaliciousjavascripten)
- 2010.06 [trustedsec] [Anti-Virus Evasion through JavaScript Obfuscation](https://www.trustedsec.com/2010/06/anti-virus-evasion-through-javascript-obfuscation/)
- 2010.04 [forcepoint] [Multi-layer Obfuscated JavaScript Using Twitter API](https://www.forcepoint.com/blog/security-labs/multi-layer-obfuscated-javascript-using-twitter-api)
- 2010.04 [sans] [JavaScript obfuscation in PDF: Sky is the limit](https://isc.sans.edu/forums/diary/JavaScript+obfuscation+in+PDF+Sky+is+the+limit/8587/)
- 2009.05 [talosintelligence] [Gumblar and More On Javascript Obfuscation](https://blog.talosintelligence.com/2009/05/gumblar-and-more-on-javascript.html)
- 2009.04 [sans] [Advanced JavaScript obfuscation (or why signature scanning is a failure)](https://isc.sans.edu/forums/diary/Advanced+JavaScript+obfuscation+or+why+signature+scanning+is+a+failure/6142/)
- 2009.02 [talosintelligence] [Detecting Silly Javascript Obfuscation Techniques](https://blog.talosintelligence.com/2009/02/detecting-silly-javascript-obfuscation.html)
- 2008.07 [sans] [Obfuscated JavaScript Redux](https://isc.sans.edu/forums/diary/Obfuscated+JavaScript+Redux/4724/)
- 2008.04 [sans] [Advanced obfuscated JavaScript analysis](https://isc.sans.edu/forums/diary/Advanced+obfuscated+JavaScript+analysis/4246/)
- 2008.04 [sans] [Mixed (VBScript and JavaScript) obfuscation](https://isc.sans.edu/forums/diary/Mixed+VBScript+and+JavaScript+obfuscation/4231/)
- 2007.10 [sans] [Deobfuscating javascript](https://isc.sans.edu/forums/diary/Deobfuscating+javascript/3484/)
- 2007.08 [sans] [Raising the bar: dynamic JavaScript obfuscation](https://isc.sans.edu/forums/diary/Raising+the+bar+dynamic+JavaScript+obfuscation/3219/)
- 2006.07 [sans] [Browser *does* matter, not only for vulnerabilities - a story on JavaScript deobfuscation](https://isc.sans.edu/forums/diary/Browser+does+matter+not+only+for+vulnerabilities+a+story+on+JavaScript+deobfuscation/1519/)


# <a id="d4d25fcc4b3c99e23d0057b7b16b9c31"></a>LLVM


***


## <a id="85d98a2a3d190ff4a881fb9fee756981"></a>obfuscator


### <a id="d7e2adf8a51047f3d3cfa9ba79917cd5"></a>工具


- [**2113**星][12d] [obfuscator-llvm/obfuscator](https://github.com/obfuscator-llvm/obfuscator) Obfuscator-LLVM 
- [**1182**星][4m] [hikariobfuscator/hikari](https://github.com/HikariObfuscator/Hikari) LLVM Obfuscator
- [**249**星][12d] [Py] [rpisec/llvm-deobfuscator](https://github.com/rpisec/llvm-deobfuscator) Performs the inverse operation of the control flow flattening pass performed by LLVM-Obfuscator
- [**71**星][12d] [C++] [qtfreet00/llvm-obfuscator](https://github.com/qtfreet00/llvm-obfuscator) ollvm based on llvm 5.0 release
- [**39**星][6m] [Shell] [lawliet89/llvm-obfuscator](https://github.com/lawliet89/llvm-obfuscator) LLVM Obfuscator
- [**32**星][4m] [C++] [exorxw/kylin-llvm-obfuscator](https://github.com/exorxw/kylin-llvm-obfuscator) based on llvm 5.0.1 release with ollvm
- [**28**星][19d] [C++] [tsarpaul/llvm-string-obfuscator](https://github.com/tsarpaul/llvm-string-obfuscator) LLVM String Obfuscator




***


## <a id="245340b4b00837dba6574ffb7b30fbbd"></a>armariris


### <a id="b2c0d5760dc0d1049ea3c9f19b8e421c"></a>工具


- [**691**星][12m] [C++] [gossip-sjtu/armariris](https://github.com/gossip-sjtu/armariris) 由上海交通大学密码与计算机安全实验室维护的LLVM混淆框架


### <a id="76c686c5eff38ffc4ac7cdc7de5a3e53"></a>文章


- 2019.06 [360] [使用unicorn engin还原Armariris字符串混淆](https://www.anquanke.com/post/id/181051/)




***


## <a id="6b9473302b708b7d1d113da799f07caa"></a>tigress


### <a id="7bef6a80765d31fd23f41c83b88fdfbe"></a>工具


- [**475**星][7m] [LLVM] [jonathansalwan/tigress_protection](https://github.com/jonathansalwan/tigress_protection) Playing with the Tigress binary protection. Break some of its protections and solve some of its challenges. Automatic deobfuscation using symbolic execution, taint analysis and LLVM.




***


## <a id="9769f77c9be1d1a84c70892ed86a1b69"></a>工具


- [**199**星][4y] [Py] [f8left/decllvm](https://github.com/f8left/decllvm) IDA plugin for OLLVM analysis
- [**178**星][11d] [Py] [amimo/ollvm-breaker](https://github.com/amimo/ollvm-breaker) 使用Binary Ninja去除ollvm流程平坦混淆
- [**158**星][6y] [C] [fuzion24/androidobfuscation-ndk](https://github.com/fuzion24/androidobfuscation-ndk) Example of obfuscating an Android NDK project using O-LLVM
- [**101**星][12d] [amimo/goron](https://github.com/amimo/goron) Yet another llvm based obfuscator
- [**52**星][4m] [Py] [sfwishes/ollvm_de_fla](https://github.com/sfwishes/ollvm_de_fla) deobfuscation ollvm's fla
- [**29**星][15d] [C++] [allocandinit/ollvm5.0.1](https://github.com/allocandinit/ollvm5.0.1) obfuscator 基于 llvm 5.0.1 版本
- [**16**星][1m] [Py] [get1t/deollvm64](https://github.com/get1t/deollvm64) deobfuscator llvm arm64 script
- [**14**星][15d] [Shell] [nickdiego/docker-ollvm](https://github.com/nickdiego/docker-ollvm) Easily build and package Obfuscator-LLVM into Android NDK.
- [**10**星][2m] [Py] [get1t/deollvm](https://github.com/get1t/deollvm) deollvm arm64 based unicorn
- [**None**星][Py] [maiyao1988/deobf](https://github.com/maiyao1988/deobf) An arm32 ollvm like deofuscator,aim to remove obfuscation made by ollvm like compiler


***


## <a id="f6d3af2c0d95023e3bb1136dc15f1760"></a>文章


- 2019.11 [aliyun] [使用IDA microcode去除ollvm混淆(下)](https://xz.aliyun.com/t/6795)
- 2019.11 [zimperium] [SATURN Software deobfuscation framework based on LLVM](https://blog.zimperium.com/saturn-software-deobfuscation-framework-based-on-llvm/)
- 2019.11 [aliyun] [使用IDA microcode去除ollvm混淆(上)](https://xz.aliyun.com/t/6749)
- 2019.09 [quarkslab] [Obfuscating Java bytecode with LLVM and Epona](https://blog.quarkslab.com/obfuscating-java-bytecode-with-llvm-and-epona.html)
- 2019.08 [mediacccde] [LO! An LLVM Obfuscator - deutsche Übersetzung](https://www.youtube.com/watch?v=VJL4MvYB-Qw)
- 2019.08 [mediacccde] [LO! An LLVM Obfuscator](https://www.youtube.com/watch?v=k1UfE6Bp5Ck)
- 2019.08 [BornHack] [BornHack 2019 - Klondike - LO! An LLVM Obfuscator](https://www.youtube.com/watch?v=CoZGtwBSwlg)
- 2019.05 [SecurityFest] [Calle Svensson - Software Obfuscation with LLVM - SecurityFest 2019](https://www.youtube.com/watch?v=bQpPdT7RDqQ)
- 2019.01 [pediy] [[原创]ollvm字符混淆修复](https://bbs.pediy.com/thread-249071.htm)
- 2018.10 [pediy] [[原创] obfuscator-llvm-3.6.1 的 VS2017 win32 修正编译](https://bbs.pediy.com/thread-247231.htm)
- 2018.04 [pediy] [[原创]ollvm快速学习](https://bbs.pediy.com/thread-225756.htm)
- 2018.02 [pediy] [[翻译]LLVM代码混淆分析及逻辑还原](https://bbs.pediy.com/thread-224484.htm)
- 2017.07 [360] [为OLLVM添加字符串混淆功能](https://www.anquanke.com/post/id/86384/)
- 2017.05 [pediy] [[原创]ollvm的混淆反混淆和定制修改](https://bbs.pediy.com/thread-217727.htm)
- 2017.03 [freebuf] [反混淆：恢复被OLLVM保护的程序](http://www.freebuf.com/articles/terminal/130142.html)
- 2016.07 [pediy] [基于LLVM IR的源代码混淆的实现](https://bbs.pediy.com/thread-211717.htm)
- 2015.05 [yurichev] [16-May-2015: Tweaking LLVM Obfuscator + quick look into some of LLVM internals.](https://yurichev.com/blog/llvm/)
- 2014.12 [quarkslab] [Deobfuscation: recovering an OLLVM-protected program](https://blog.quarkslab.com/deobfuscation-recovering-an-ollvm-protected-program.html)


# <a id="0328c02993be94615d01d76523e36181"></a>Shellcode


***


## <a id="b5e505df69ad535815bc8de542a3de1d"></a>工具


- [**506**星][21d] [Py] [zdresearch/owasp-zsc](https://github.com/zdresearch/OWASP-ZSC) Shellcode/混淆代码生成器
- [**195**星][2y] [Py] [mr-un1k0d3r/unibyav](https://github.com/mr-un1k0d3r/unibyav)  a simple obfuscator that take raw shellcode and generate executable that are Anti-Virus friendly.
- [**148**星][4y] [Py] [kgretzky/python-x86-obfuscator](https://github.com/kgretzky/python-x86-obfuscator) This is a **WIP** tool that performs shellcode obfuscation in x86 instruction set.
- [**45**星][20d] [Py] [eteissonniere/elidecode](https://github.com/ETeissonniere/EliDecode) The tool to decode obfuscated shellcodes using the unicorn and capstone engine
- [**44**星][4m] [Py] [offsecginger/pythonaesobfuscate](https://github.com/offsecginger/pythonaesobfuscate) Obfuscates a Python Script and the accompanying Shellcode.
- [**13**星][4m] [C++] [hoodoer/enneos](https://github.com/hoodoer/enneos) Evolutionary Neural Network Encoder of Shenanigans. Obfuscating shellcode with an encoder that uses genetic algorithms to evolve neural networks to contain and output the shellcode on demand.


***


## <a id="51bac3d27fdaecd233193017ce3d4d63"></a>文章


- 2020.04 [morphisec] [Lokibot with AutoIt Obfuscator + Frenchy Shellcode](https://blog.morphisec.com/lokibot-with-autoit-obfuscator-frenchy-shellcode)
- 2017.08 [zerosum0x0] [在线版 混淆字符串/Shellcode 生成器](https://zerosum0x0.blogspot.com/2017/08/obfuscatedencrypted-cc-online-string.html)
- 2017.02 [csyssec] [X86 Shellcode代码混淆(一)](http://www.csyssec.org/20170223/obfuscation1/)
- 2016.06 [breakdev] [X86 Shellcode Obfuscation - Part 3](https://breakdev.org/x86-shellcode-obfuscation-part-3/)
- 2016.05 [breakdev] [X86 Shellcode Obfuscation - Part 2](https://breakdev.org/x86-shellcode-obfuscation-part-2/)
- 2016.05 [breakdev] [X86 Shellcode Obfuscation - Part 1](https://breakdev.org/x86-shellcode-obfuscation-part-1/)
- 2014.03 [zairon] [Obfuscated shellcode inside a malicious RTF document](https://zairon.wordpress.com/2014/03/06/obfuscated-shellcode-inside-a-malicious-rtf-document/)


# <a id="c8158811d160a448a6e6a6882f0264de"></a>Bash


***


## <a id="f389d3f7f415b93580a50575af01fc6e"></a>bashfuscator


### <a id="206537811e24bd1f3cd8b6500a27fb6b"></a>工具


- [**495**星][8m] [Py] [bashfuscator/bashfuscator](https://github.com/bashfuscator/bashfuscator) 一个完全可配置和可扩展的Bash混淆框架。


### <a id="7ee0b9cda87c045044c9dfa652d0ffb6"></a>文章


- 2018.12 [0x00sec] [Yes, Bash Can Get Uglier: Introducing Bashfuscator, A Bash Obfuscation Framework](https://0x00sec.org/t/yes-bash-can-get-uglier-introducing-bashfuscator-a-bash-obfuscation-framework/10216/)




***


## <a id="3e62e2c37b74248c36b27d9c4aec23b7"></a>工具


- [**80**星][9m] [PHP] [rizer0/blind-bash](https://github.com/rizer0/blind-bash) Obfuscate your Bash Code
- [**19**星][2m] [JS] [willshiao/node-bash-obfuscate](https://github.com/willshiao/node-bash-obfuscate) A Node.js CLI tool and library to heavily obfuscate bash scripts.


***


## <a id="cb790718e94e549a264a6fa6b5c4bfa6"></a>文章


- 2018.11 [ironcastle] [Obfuscated bash script targeting QNap boxes, (Mon, Nov 26th)](https://www.ironcastle.net/obfuscated-bash-script-targeting-qnap-boxes-mon-nov-26th/)
- 2018.11 [sans] [Obfuscated bash script targeting QNap boxes](https://isc.sans.edu/forums/diary/Obfuscated+bash+script+targeting+QNap+boxes/24348/)
- 2014.10 [f5] [Shellshock: Malicious Bash, Obfuscated perlb0t, Echo Probes, and More](https://f5.com/labs/articles/threat-intelligence/malware/shellshock-malicious-bash-obfuscated-perlb0t-echo-probes-and-more-22438)


# <a id="f9bf00d928effb18d2a237b5b2e3d5be"></a>PHP


***


## <a id="c53e3f5adb0a0312666a2b0a75afc0a7"></a>php-obfuscator


### <a id="7b9b1b71da2ba028093266e3a5e13f1d"></a>工具


- [**417**星][4m] [PHP] [naneau/php-obfuscator](https://github.com/naneau/php-obfuscator) A parsing PHP obfuscator




***


## <a id="bd9e590d98dbbad1ba3e1578fb60ac17"></a>yakpro-po


### <a id="74c2beb1b94aa72829a9eef190c0448b"></a>工具


- [**551**星][9d] [PHP] [pk-fr/yakpro-po](https://github.com/pk-fr/yakpro-po) YAK Pro - Php Obfuscator




***


## <a id="531f45736bfe4f930def4c40029af8d8"></a>optimus


### <a id="5fa6b1a17d15dacdd357631f392762de"></a>工具


- [**1001**星][12d] [PHP] [jenssegers/optimus](https://github.com/jenssegers/optimus) 根据Knuth的整数散列将内部id转换为模糊整数。它类似于hashid，但将生成整数而不是随机字符串。它也非常快
- [**100**星][4m] [PHP] [cybercog/laravel-optimus](https://github.com/cybercog/laravel-optimus) Transform your internal id's to obfuscated integers based on Knuth's integer hash. Laravel wrapper for the Optimus Library by Jens Segers with multiple connections support.




***


## <a id="3b5533d8ba7e27c1cae2993919aca8a2"></a>工具


- [**96**星][4m] [PHP] [ph-7/obfuscator-class](https://github.com/ph-7/obfuscator-class) Simple and effective Obfuscator PHP class (this is not a stupid base64 encoding script, but a real and effective obfuscation script)
- [**72**星][18d] [PHP] [bediger4000/php-malware-analysis](https://github.com/bediger4000/php-malware-analysis) Deobfuscation and analysis of PHP malware captured by a WordPress honey pot
- [**70**星][3y] [Py] [antelox/fopo-php-deobfuscator](https://github.com/antelox/fopo-php-deobfuscator) A simple script to deobfuscate PHP file obfuscated with FOPO Obfuscator -
- [**49**星][5m] [PHP] [bediger4000/reverse-php-malware](https://github.com/bediger4000/reverse-php-malware) De-obfuscate and reverse engineer PHP malware
- [**25**星][1m] [Py] [zigzag2050/mzphp2-deobfuscator](https://github.com/zigzag2050/mzphp2-deobfuscator) A de-obfuscate tool for code generated by mzphp2. 用于解混淆mzphp2加密的php文件的工具。
- [**22**星][5m] [coldev/coldevprolayer](https://github.com/coldev/coldevprolayer) Protect your PHP code with obfuscation and encryption
- [**18**星][3m] [PHP] [darsyn/obfuscator](https://github.com/darsyn/obfuscator) Obfuscate PHP source files with basic XOR encryption in userland code at runtime.
- [**12**星][1m] [PHP] [ammarfaizi2/php-integral-obfuscator](https://github.com/ammarfaizi2/php-integral-obfuscator) PHP Integral Obfuscator
- [**10**星][4y] [PHP] [k0u5uk3/obfuscated-php-webshell-detector](https://github.com/k0u5uk3/obfuscated-php-webshell-detector) obfuscated-php-webshell-detector - Detect PHP Webshell in obfusucation
- [**10**星][12m] [PHP] [th1k404/unishell](https://github.com/th1k404/unishell) A piece of php webshell which are using khmer unicode and yak obfuscator to be undetectable and silently.
- [**9**星][1m] [PHP] [simon816/phpdeobfuscator](https://github.com/simon816/phpdeobfuscator) Advanced PHP deobfuscator


***


## <a id="b340e8a1c2de74fb198271d3a14e962f"></a>文章


- 2020.03 [aliyun] [开发简单的PHP混淆器与解混淆器](https://xz.aliyun.com/t/7363)
- 2019.08 [0x00sec] [Reverse Obfuscated PHP Code](https://0x00sec.org/t/reverse-obfuscated-php-code/15459)
- 2019.05 [detectify] [How-to Tutorial: PHP Webshell De-Obfuscation](https://labs.detectify.com/2019/05/24/how-to-tutorial-php-webshell-de-obfuscation/)
- 2014.07 [coder] [PHP script deobfuscation for dummies](https://coder.pub/2014/07/php-script-deobfuscation-for-dummies/)
- 2012.05 [freebuf] [php的代码混淆工具-carbylamine](http://www.freebuf.com/sectool/1606.html)
- 2012.01 [coder] [PHP script deobfuscation for dummies](https://kaimi.io/en/2012/01/php-script-deobfuscation-for-dummies/)
- 2010.11 [e] [php code obfuscator](http://e-omidfar.blogspot.com/2010/11/php-code-obfuscator.html)
- 2010.04 [coder] [PHP Obfuscator by dx](https://coder.pub/2010/04/php-obfuscator-by-dx/)
- 2009.06 [gamelinux] [Obfuscating php code with base64](https://gamelinux.wordpress.com/2009/06/23/obfuscating-php-code-with-base64/)


# <a id="3ef488c941a5684f3336975b7df1d9b7"></a>Go


***


## <a id="3ba2cf7fe57eaa3a81129e99e70fd77b"></a>gobfuscate


### <a id="09d794248c8032a5baf2e26147bf78cf"></a>工具


- [**404**星][11d] [Go] [unixpickle/gobfuscate](https://github.com/unixpickle/gobfuscate) Obfuscate Go binaries and packages




***


## <a id="33c1998f141ab7b059ee273fec12f0f7"></a>工具


- [**201**星][13d] [Go] [mvdan/garble](https://github.com/mvdan/garble) Obfuscate Go builds


# <a id="2c434d33f0dc3e0b8291a1173d4c863a"></a>Office


***


## <a id="a675e8b1cf8bafb2abf40ffe1cda6130"></a>macro_pack


### <a id="6695a309cb7dd5c8819776479c0a729f"></a>工具


- [**817**星][15d] [Py] [sevagas/macro_pack](https://github.com/sevagas/macro_pack) 自动生成并混淆MS 文档, 用于渗透测试、演示、社会工程评估等


### <a id="e132b5a30c0eaf8dad0103b5e17dbb54"></a>文章


- 2019.09 [freebuf] [Macro_Pack中的宏代码混淆方法分析](https://www.freebuf.com/sectool/211592.html)
- 2019.08 [4hou] [Macro_Pack中的宏代码混淆方法分析](https://www.4hou.com/info/news/19640.html)
- 2018.05 [freebuf] [Macro_Pack：一款用于自动化混淆和生成Office文档等文件格式的工具](http://www.freebuf.com/sectool/170695.html)
- 2017.12 [n0where] [Automatize Obfuscation and Generation of MS Office Documents: macro_pack](https://n0where.net/automatize-obfuscation-and-generation-of-ms-office-documents-macro_pack)




***


## <a id="393c2d829a1a1edfb7c804373b8b27d6"></a>maliciousmacrogenerator


### <a id="f9882cc1b17c8003597d7ea53306f505"></a>工具


- [**524**星][1y] [Visual Basic .NET] [mr-un1k0d3r/maliciousmacrogenerator](https://github.com/mr-un1k0d3r/maliciousmacrogenerator) 生成混淆的宏，可进行AV /沙箱逃逸




***


## <a id="57f22eded50566be7e5f37c260f42c58"></a>工具


- [**355**星][3y] [Py] [pepitoh/vbad](https://github.com/pepitoh/vbad) VBA Obfuscation Tools combined with an MS office document generator
- [**29**星][8d] [Py] [bonnetn/vba-obfuscator](https://github.com/bonnetn/vba-obfuscator) 2018 School project - PoC of malware code obfuscation in Word macros


***


## <a id="e03c9dba02b3d4e48678bc865877f3c1"></a>文章


- 2020.02 [rootshell] [[SANS ISC] Simple but Efficient VBScript Obfuscation](https://blog.rootshell.be/2020/02/22/sans-isc-simple-but-efficient-vbscript-obfuscation/)
- 2020.01 [freebuf] [Office控件钓鱼：混淆拼接篇](https://www.freebuf.com/articles/es/224347.html)
- 2019.09 [dylankatz] [Deobfuscating And Analyzing A Vbs Dropper](https://dylankatz.com/deobfuscating-and-analyzing-a-vbs-dropper/)
- 2018.11 [ironcastle] [ViperMonkey: VBA maldoc deobfuscation, (Mon, Nov 26th)](https://www.ironcastle.net/vipermonkey-vba-maldoc-deobfuscation-mon-nov-26th/)
- 2018.08 [cofense] [Recent Geodo Malware Campaigns Feature Heavily Obfuscated Macros](https://cofense.com/recent-geodo-malware-campaigns-feature-heavily-obfuscated-macros/)
- 2018.08 [ColinHardy] [Analysing Obfuscated VBA - Extracting indicators from a Trickbot downloader](https://www.youtube.com/watch?v=auB7mkwfHrk)
- 2017.12 [sans] [Microsoft Office VBA Macro Obfuscation via Metadata](https://isc.sans.edu/forums/diary/Microsoft+Office+VBA+Macro+Obfuscation+via+Metadata/23139/)
- 2017.07 [sans] [A VBScript with Obfuscated Base64 Data](https://isc.sans.edu/forums/diary/A+VBScript+with+Obfuscated+Base64+Data/22590/)
- 2017.05 [malwaretracker] [恶意 Office 文档使用基于EPS 的混淆技术，躲避检测](http://blog.malwaretracker.com/2017/05/eps-obfuscation-for-ms-office-exploits.html)
- 2016.10 [cysinfo] [Cyber Security with Amit Malik – Episode 2 – Macro Code De-obfuscation using Vbscript Debugger](https://cysinfo.com/cyber-security-amit-malik-episode-2-macro-code-de-obfuscation-using-vbscript-debugger/)
- 2016.04 [mcafee] [Macro Malware Employs Advanced Obfuscation to Avoid Detection](https://www.mcafee.com/blogs/other-blogs/mcafee-labs/macro-malware-employs-advanced-obfuscation-to-avoid-detection/)
- 2016.04 [mcafee] [Macro Malware Employs Advanced Obfuscation to Avoid Detection](https://securingtomorrow.mcafee.com/mcafee-labs/macro-malware-employs-advanced-obfuscation-to-avoid-detection/)
- 2016.02 [malwarebytes] [De-obfuscating malicious Vbscripts](https://blog.malwarebytes.com/cybercrime/2016/02/de-obfuscating-malicious-vbscripts/)
- 2014.08 [securelist] [Obfuscated malicious office documents adopted by cybercriminals around the world](https://securelist.com/obfuscated-malicious-office-documents-adopted-by-cybercriminals-around-the-world/65414/)
- 2013.09 [pwndizzle] [How not to Obfuscate your VBScript](http://pwndizzle.blogspot.com/2013/09/how-not-to-obfuscate-your-malware.html)
- 2007.09 [sans] [Deobfuscating VBScript](https://isc.sans.edu/forums/diary/Deobfuscating+VBScript/3351/)


# <a id="c8be8cbc9e92418ec4eb91a15608969f"></a>Python


***


## <a id="96c7873e76e7825abcea18eeafdc2afa"></a>pyminifier


### <a id="6037ed842fe61659d01d8d32a1a9170b"></a>工具


- [**912**星][4m] [Py] [liftoff/pyminifier](https://github.com/liftoff/pyminifier) Pyminifier is a Python code minifier, obfuscator, and compressor.




***


## <a id="bab1b5a63fc4e3e2379fad4f45653ef4"></a>pyarmor


### <a id="153179ac6f717a249d21dbba08571bba"></a>工具


- [**449**星][4m] [Py] [dashingsoft/pyarmor](https://github.com/dashingsoft/pyarmor) A tool used to obfuscate python scripts, bind obfuscated scripts to fixed machine or expire obfuscated scripts.




***


## <a id="710ad15004534cfe5f939655e055b3df"></a>neopi


### <a id="fe2b5593a8909ffd901de8cb9861a149"></a>工具


- [**348**星][6y] [Py] [neohapsis/neopi](https://github.com/neohapsis/neopi) a Python script that uses a variety of statistical methods to detect obfuscated and encrypted content within text/script files


### <a id="4a4963766e96524479d6da2fafc75602"></a>文章


- 2020.04 [oshpark] [Neopixel Rotary Encoder](http://blog.oshpark.com/2020/04/18/neopixel-rotary-encoder/)
- 2017.05 [particle] [Heads up – WS2812B NeoPixels are about to change!](https://blog.particle.io/2017/05/11/ws2812b-neopixels-are-about-to-change/)




***


## <a id="00354d933f4c483d011b1a891e4765c6"></a>intensio-obfuscator


### <a id="4db25e79c2c40899d30dbf80d1731c40"></a>工具


- [**302**星][4m] [Py] [hnfull/intensio-obfuscator](https://github.com/hnfull/intensio-obfuscator) Obfuscate a python code 2.x and 3.x


### <a id="22a022e9e7d4d4e2f1cee842b1ae8586"></a>文章


- 2019.06 [freebuf] [Intensio-Obfuscator：一款专业Python代码混淆处理工具](https://www.freebuf.com/sectool/205926.html)




***


## <a id="b2d59d57c43592a88b115dfb8cc41eb4"></a>工具


- [**340**星][12d] [Py] [astrand/pyobfuscate](https://github.com/astrand/pyobfuscate) Python源码混淆: 使得Python源代码对于人类来说难以阅读，而对于Python解释器来说仍然是可执行的
- [**123**星][9d] [Py] [felamos/weirdhta](https://github.com/felamos/weirdhta) A python tool to create obfuscated HTA script.
- [**82**星][2m] [Java] [enovella/jebscripts](https://github.com/enovella/jebscripts) A set of JEB Python/Java scripts for reverse engineering Android obfuscated code
- [**75**星][7m] [Py] [anvilventures/lookinsidethebox](https://github.com/anvilventures/lookinsidethebox) Breaks the encryption and obfuscation layers that Dropbox applies to their modified Python interpreter.
- [**74**星][4m] [Py] [pyobfx/pyobfx](https://github.com/pyobfx/pyobfx) Python Obfuscator & Packer
- [**72**星][22d] [Py] [chris-rands/emojify](https://github.com/chris-rands/emojify) Obfuscate your python script by converting it to emoji icons
- [**68**星][1m] [Py] [plantdaddy/fuzzap](https://github.com/PlantDaddy/FuzzAP) A python script for obfuscating wireless networks
- [**50**星][1m] [Py] [bwall/markovobfuscate](https://github.com/bwall/markovobfuscate) Python library and tools to obfuscate data based on Markov models built off shared data
- [**48**星][3m] [YARA] [decalage2/balbuzard](https://github.com/decalage2/balbuzard) Balbuzard is a package of malware analysis tools in python to extract patterns of interest from suspicious files (IP addresses, domain names, known file headers, interesting strings, etc). It can also crack malware obfuscation such as XOR, ROL, etc by bruteforcing and checking for those patterns.
- [**42**星][23d] [Py] [extremecoders-re/bytecode_simplifier](https://github.com/extremecoders-re/bytecode_simplifier) A generic deobfuscator for PjOrion obfuscated python scripts
- [**39**星][3y] [Py] [extremecoders-re/pjorion-deobfuscator](https://github.com/extremecoders-re/pjorion-deobfuscator) A deobfuscator for PjOrion, python cfg generator and more
- [**38**星][1m] [Py] [lasq88/deobfuscate](https://github.com/lasq88/deobfuscate) Python script to automatically deobfuscate malware code
- [**31**星][4m] [Py] [alberties/ghostfuscator](https://github.com/alberties/ghostfuscator) The Python Password-Protected Obfuscator
- [**9**星][4m] [PHP] [chrissy-morgan/php-webshell-deobfuscator](https://github.com/chrissy-morgan/php-webshell-deobfuscator) A Tool written in Python to help de-obfuscate the $GLOBALS type malware.
- [**8**星][7m] [Py] [thngkaiyuan/mynaim](https://github.com/thngkaiyuan/mynaim) Nymaim 家族样本反混淆插件


***


## <a id="eab89cedf1706e7fa90dc6530899c968"></a>文章


- 2019.03 [thief] [Python代码加密混淆](https://thief.one/2019/03/21/1/)
- 2018.02 [0x00sec] [Plain Obfuscate Python script as malware](https://0x00sec.org/t/plain-obfuscate-python-script-as-malware/5545/)
- 2016.07 [doyler] [Deobfuscate Python (ABCTF2016 –  Obfuscated 1)](https://www.doyler.net/security-not-included/deobfuscate-python-abctf)
- 2016.05 [freebuf] [用Python和Smali模拟器搞定一个加混淆、防篡改的APK逆向](http://www.freebuf.com/articles/web/103980.html)
- 2016.04 [evilsocket] [How I Defeated an Obfuscated and Anti-Tamper APK With Some Python and a Home-Made Smali Emulator.](https://www.evilsocket.net/2016/04/18/how-i-defeated-an-obfuscated-and-anti-tamper-apk-with-some-python-and-a-home-made-smali-emulator/)
- 2016.04 [aassfxxx] [Breaking Cerber strings obfuscation with Python and radare2](http://aassfxxx.infos.st/article26/breaking-cerber-strings-obfuscation-with-python-and-radare2)
- 2016.04 [aassfxxx] [Breaking Cerber strings obfuscation with Python and radare2](http://aassfxxx.infos.st/breaking-cerber-strings-obfuscation-with-python-and-radare2.html)
- 2014.05 [quarkslab] [Building an obfuscated Python interpreter: we need more opcodes](https://blog.quarkslab.com/building-an-obfuscated-python-interpreter-we-need-more-opcodes.html)
- 2013.12 [HackersSecurity] [DEFCON 18: Obfuscated Python](https://www.youtube.com/watch?v=1bJoZ-O0QS0)
- 2012.06 [trustwave] [使用IDAPython对Flame的字符串进行反混淆](https://www.trustwave.com/Resources/SpiderLabs-Blog/Defeating-Flame-String-Obfuscation-with-IDAPython/)


# <a id="4169178cfbac7e4e03c182600d58d40e"></a>Android


***


## <a id="263fb2577d8c578768f677ca34d517bd"></a>simplify


### <a id="98a46d73a2511e58cf348049e1c33e5f"></a>工具


- [**3296**星][11d] [Java] [calebfenton/simplify](https://github.com/calebfenton/simplify) Android虚拟机和deobfuscator




***


## <a id="5c67e3ac71ff94cd820ed382f96d359f"></a>工具


- [**745**星][5m] [YARA] [rednaga/apkid](https://github.com/rednaga/apkid) Android应用程序标识符，用于包装器、保护器、混淆器和奇怪的东西
- [**370**星][12d] [Ruby] [calebfenton/dex-oracle](https://github.com/calebfenton/dex-oracle) A pattern based Dalvik deobfuscator which uses limited execution to improve semantic analysis
- [**314**星][9m] [C] [shadowsocks/simple-obfs-android](https://github.com/shadowsocks/simple-obfs-android) 一个简单的Android混淆工具
- [**258**星][2m] [Java] [godlikewangjun/dexknife-wj](https://github.com/godlikewangjun/dexknife-wj) apk加固插件 带签名校验、dex加密、资源混淆
- [**230**星][4y] [Ruby] [strazzere/apkfuscator](https://github.com/strazzere/apkfuscator) A generic DEX file obfuscator and munger
- [**196**星][4m] [Py] [claudiugeorgiu/obfuscapk](https://github.com/claudiugeorgiu/obfuscapk) A black-box obfuscation tool for Android apps
- [**165**星][3y] [ysrc/androidobfusedictionary](https://github.com/ysrc/androidobfusedictionary) Android ProGuard变态混淆字典
- [**119**星][5m] [Java] [stringcare/androidlibrary](https://github.com/stringcare/androidlibrary) Android library to reveal or obfuscate strings and assets at runtime
- [**94**星][6m] [Py] [thuxnder/dalvik-obfuscator](https://github.com/thuxnder/dalvik-obfuscator) a set of tools/scripts to obfuscate and manipulate dex files
- [**90**星][1m] [Py] [necst/aamo](https://github.com/necst/aamo) Another Android Malware Obfuscator
- [**61**星][5y] [Py] [hamiltoniancycle/classnamedeobfuscator](https://github.com/hamiltoniancycle/classnamedeobfuscator) Simple script to parse through the .smali files produced by apktool and extract the .source annotation lines.
- [**25**星][5y] [Py] [burningcodes/dexconfuse](https://github.com/burningcodes/dexconfuse) 简易dex混淆器
- [**17**星][12d] [Py] [omirzaei/androdet](https://github.com/omirzaei/androdet) AndrODet: An Adaptive Android Obfuscation Detector
- [**15**星][12d] [Java] [miwong/tiro](https://github.com/miwong/tiro) TIRO - A hybrid iterative deobfuscation framework for Android applications


***


## <a id="b8bd64107751a6e271414bd1db39dad1"></a>文章


- 2020.02 [freebuf] [Obfuscapk：一款针对Android应用程序的黑盒混淆工具](https://www.freebuf.com/sectool/226391.html)
- 2020.02 [hakin9] [Obfuscapk - A black-box obfuscation tool for Android apps](https://hakin9.org/obfuscapk-a-black-box-obfuscation-tool-for-android-apps/)
- 2019.12 [hakin9] [Quark Engine - An Obfuscation-Neglect Android Malware Scoring System](https://hakin9.org/quark-engine-an-obfuscation-neglect-android-malware-scoring-system/)
- 2019.10 [aliyun] [apk混淆工具Obfuscapk原理探究](https://xz.aliyun.com/t/6438)
- 2019.05 [arxiv] [[1905.09136] DaDiDroid: An Obfuscation Resilient Tool for Detecting Android Malware via Weighted Directed Call Graph Modelling](https://arxiv.org/abs/1905.09136)
- 2019.03 [virusbulletin] [VB2018 paper and video: Android app deobfuscation using static-dynamic cooperation](https://www.virusbulletin.com/blog/2019/03/vb2018-paper-and-video-android-app-deobfuscation-using-static-dynamic-cooperation/)
- 2018.10 [securitygossip] [Tackling Runtime-based Obfuscation in Android With TIRO](https://securitygossip.com/blog/2018/10/08/tackling-runtime-based-obfuscation-in-android-with-tiro/)
- 2018.10 [sjtu] [Tackling Runtime-based Obfuscation in Android With TIRO](https://loccs.sjtu.edu.cn/gossip/blog/2018/10/08/tackling-runtime-based-obfuscation-in-android-with-tiro/)
- 2018.04 [360] [对混淆的Android应用进行渗透测试](https://www.anquanke.com/post/id/104794/)
- 2018.03 [guardsquare] [Decompiling obfuscated Android applications](https://www.guardsquare.com/en/blog/decompiling-obfuscated-android-applications)
- 2018.03 [pediy] [[原创]御安全浅析安卓开发代码混淆技术](https://bbs.pediy.com/thread-224966.htm)
- 2018.02 [tinyhack] [Pentesting obfuscated Android App](http://tinyhack.com/2018/02/05/pentesting-obfuscated-android-app/)
- 2018.02 [pnfsoftware] [A new APK Resources Decoder with de-Obfuscation Capabilities](https://www.pnfsoftware.com/blog/a-new-apk-resources-decoder-with-de-obfuscation-capabilities/)
- 2018.01 [arxiv] [[1801.01633] Understanding Android Obfuscation Techniques: A Large-Scale Investigation in the Wild](https://arxiv.org/abs/1801.01633)
- 2017.10 [360] [如何使用dex-oracle对抗混淆后的Android恶意软件](https://www.anquanke.com/post/id/87120/)
- 2017.10 [rednaga] [Hacking with dex-oracle for Android Malware Deobfuscation](https://rednaga.io/2017/10/28/hacking-with-dex-oracle-for-android-malware-deobfuscation/)
- 2017.04 [360] [Android代码混淆技术总结（一）](https://www.anquanke.com/post/id/85843/)
- 2017.03 [360] [Android 字符串及字典混淆开源实现](https://www.anquanke.com/post/id/85637/)
- 2017.01 [360] [Android程序反混淆利器——Simplify工具](https://www.anquanke.com/post/id/85388/)
- 2016.12 [securitygossip] [Statistical Deobfuscation of Android Applications](http://securitygossip.com/blog/2016/12/16/2016-12-16/)
- 2016.12 [sjtu] [Statistical Deobfuscation of Android Applications](https://loccs.sjtu.edu.cn/gossip/blog/2016/12/16/2016-12-16/)
- 2016.11 [arxiv] [[1611.10231] Android Code Protection via Obfuscation Techniques: Past, Present and Future Directions](https://arxiv.org/abs/1611.10231)
- 2016.11 [deepsec] [DeepSec 2016 Talk: Obfuscated Financial Fraud Android Malware: Detection And Behavior Tracking – Inseung Yang](http://blog.deepsec.net/deepsec-2016-talk-obfuscated-financial-fraud-android-malware-detection-behavior-tracking-inseung-yang/)
- 2016.04 [n0where] [Generic Android Deobfuscator: Simplify](https://n0where.net/generic-android-deobfuscator-simplify)
- 2016.03 [pnfsoftware] [Deobfuscating Android Triada malware](https://www.pnfsoftware.com/blog/deobfuscating-android-triada-malware/)
- 2016.01 [freebuf] [Oracle：安卓反混淆工具](http://www.freebuf.com/sectool/92545.html)
- 2015.03 [Roland] [用ProGuard混淆Android代码](https://blog.csdn.net/Roland_Sun/article/details/44629319)
- 2015.02 [arxiv] [[1502.01625] A Self-Compiling Android Data Obfuscation Tool](https://arxiv.org/abs/1502.01625)
- 2014.12 [androidcracking] [Simplify - Android Deobfuscator / Decryptor](http://androidcracking.blogspot.com/2014/12/simplify-android-deobfuscator-decryptor.html)
- 2014.07 [virusbulletin] [Paper: Obfuscation in Android malware, and how to fight back](https://www.virusbulletin.com/blog/2014/07/paper-obfuscation-android-malware-and-how-fight-back/)
- 2013.08 [pediy] [[原创]Android分析之路（二）——代码混淆分析研究1](https://bbs.pediy.com/thread-176457.htm)
- 2013.06 [pediy] [apkprotect（免费android代码混淆、加密保护工具）版本v0.3.8 2013.10.22更新](https://bbs.pediy.com/thread-172733.htm)
- 2013.04 [xyz] [android应用安全——代码安全（android代码混淆）](https://blog.csdn.net/xyz_lmn/article/details/8802785)
- 2012.12 [pediy] [[原创]一个简单的判断APK文件是否混淆的方法](https://bbs.pediy.com/thread-159959.htm)
- 2011.07 [pediy] [[原创]APK反破解之一：Android Java混淆(ProGuard)](https://bbs.pediy.com/thread-137112.htm)
- 2008.10 [ysl] [請為你的 Android 程式加上 obfuscation 吧！](http://ysl-paradise.blogspot.com/2008/10/android-obfuscation.html)


# <a id="beb0e19614fb8044452ae90b74138f2d"></a>Apple


***


## <a id="c9bdd398b84c5ddfede6e2b1a78492aa"></a>stcobfuscator


### <a id="61ba58d5e151bbeabb078767f437dff5"></a>工具


- [**663**星][1y] [ObjC] [chenxiancai/stcobfuscator](https://github.com/chenxiancai/stcobfuscator) iOS全局自动化 代码混淆 工具！支持cocoapod组件代码一并 混淆，完美避开hardcode方法、静态库方法和系统库方法！




***


## <a id="5c8857ae3e654bd79d8257595e05e229"></a>工具


- [**1500**星][12d] [ObjC] [polidea/ios-class-guard](https://github.com/polidea/ios-class-guard) Simple Objective-C obfuscator for Mach-O executables.
- [**1205**星][11d] [Swift] [rockbruno/swiftshield](https://github.com/rockbruno/swiftshield) 为你的iOS项目的类型和方法(包括第三方库和故事板)生成不可逆加密名称的工具，以保护你的应用程序免受iOS逆向工程工具，如类转储和Cycript。
- [**520**星][4y] [ObjC] [pjebs/obfuscator-ios](https://github.com/pjebs/obfuscator-ios) Secure your app by obfuscating all the hard-coded security-sensitive strings.
- [**500**星][2m] [Ruby] [kaich/codeobscure](https://github.com/kaich/codeobscure) 方便强大的OC工程代码自动混淆工具
- [**358**星][2y] [C] [codermjlee/mjcodeobfuscation](https://github.com/codermjlee/mjcodeobfuscation) 一个用于代码混淆和字符串加密的Mac小Demo
- [**334**星][2y] [C++] [polidea/siriusobfuscator](https://github.com/polidea/siriusobfuscator) a tool for performing source-to-source obfuscation of Swift projects
- [**265**星][9m] [ObjC] [preemptive/ppios-rename](https://github.com/preemptive/ppios-rename) Symbol obfuscator for iOS apps
- [**216**星][5m] [Py] [lennonchin/code-confuse-plugin](https://github.com/lennonchin/code-confuse-plugin) iOS代码混淆插件
- [**144**星][22d] [Swift] [danleechina/mixplaintext](https://github.com/danleechina/mixplaintext) 可对 Xcode 项目工程所有的 objective-c 文件内包含的明文进行加密混淆，提高逆向分析难度。
- [**44**星][15d] [Swift] [pabloroca/obfuscateapi](https://github.com/pabloroca/obfuscateapi) Mac OSX, Command line Swift 4 Utility for obfuscate / defuscate strings (API endpoints) in AES128 format.
- [**38**星][6y] [C] [x43x61x69/mach-o-prettifier](https://github.com/x43x61x69/mach-o-prettifier) A Mach-O Load Command deobfuscator.
- [**27**星][2m] [C++] [cuitche/code-obfuscation](https://github.com/cuitche/code-obfuscation) 一款iOS代码混淆工具(A code obfuscation tool for iOS.)
- [**3**星][1m] [Java] [maxpixelstudios/minecraftdecompiler](https://github.com/maxpixelstudios/minecraftdecompiler) A useful tool to decompile and deobfuscate Minecraft by CFR/FernFlower and Proguard/SRG/CSRG/TSRG mappings


***


## <a id="e9ed9f70cf4150a9f8eb4c2983ea4f6d"></a>文章


- 2019.10 [freebuf] [Swiftshield：SwiftOBJ-C 代码混淆工具](https://www.freebuf.com/sectool/213922.html)
- 2019.06 [h2hconference] [Android Game of Obfuscation - Jurriaan Bremer and Rodrigo Chiossi - H2HC 2013](https://www.youtube.com/watch?v=VGJTubBspJA)
- 2019.06 [hitbsecconf] [#HITB2019AMS D1T1 - Deobfuscate UEFI/BIOS Malware And Virtualized Packers - Alexandre Borges](https://www.youtube.com/watch?v=bCaMuHAJcHw)
- 2018.11 [ironcastle] [More obfuscated shell scripts: Fake MacOS Flash update, (Tue, Nov 27th)](https://www.ironcastle.net/more-obfuscated-shell-scripts-fake-macos-flash-update-tue-nov-27th/)
- 2018.11 [sans] [More obfuscated shell scripts: Fake MacOS Flash update](https://isc.sans.edu/forums/diary/More+obfuscated+shell+scripts+Fake+MacOS+Flash+update/24352/)
- 2018.09 [pediy] [[原创]尝试解下fairplayd(苹果|ios)的混淆(块调度)](https://bbs.pediy.com/thread-247018.htm)
- 2018.09 [4hou] [用于保护iOS应用程序的开源代码混淆工具Sirius发布（二）](http://www.4hou.com/tools/13362.html)
- 2018.09 [4hou] [用于保护iOS应用程序的开源代码混淆工具Sirius发布（一）](http://www.4hou.com/mobile/13352.html)
- 2017.11 [pnfsoftware] [Having Fun with Obfuscated Mach-O Files](https://www.pnfsoftware.com/blog/having-fun-with-obfuscated-mach-o-files/)
- 2015.04 [securityintelligence] [CVE-2015-1097: Deobfuscating iOS Kernel Pointers With an IBM X-Force-Discovered Vulnerability](https://securityintelligence.com/cve-2015-1097-deobfuscating-ios-kernel-pointers-with-an-ibm-x-force-discovered-vulnerability/)
- 2012.02 [reverse] [Anti-disassembly & obfuscation #1: Apple doesn’t follow their own Mach-O specifications?](https://reverse.put.as/2012/02/02/anti-disassembly-obfuscation-1-apple-doesnt-follow-their-own-mach-o-specifications/)


# <a id="8a996fdcd6ee02c19fd55b09fcd7f9c0"></a>Java


***


## <a id="96942f90fddd05d4c70ce45a3b3cafb7"></a>nullproguard


### <a id="23fb4af31b14c09156b20c85f7d05953"></a>工具


- [**273**星][4m] [Java] [w296488320/nullproguard](https://github.com/w296488320/nullproguard) 空白混淆 源码




***


## <a id="77ab5d96e4ca64cb5913c61540baa0a6"></a>工具


- [**615**星][13d] [Java] [java-deobfuscator/deobfuscator](https://github.com/java-deobfuscator/deobfuscator) Java 代码反混淆工具
- [**172**星][4m] [Java] [superblaubeere27/obfuscator](https://github.com/superblaubeere27/obfuscator) A java obfuscator (GUI)
- [**165**星][5m] [Java] [itzsomebody/radon](https://github.com/itzsomebody/radon) A crappy Java bytecode obfuscator (meaning: not for production use)
- [**142**星][12d] [Java] [graxcode/threadtear](https://github.com/graxcode/threadtear) Multifunctional java deobfuscation tool suite
- [**92**星][13d] [Java] [yworks/yguard](https://github.com/yworks/yguard) The open-source Java obfuscation tool working with Ant and Gradle by yWorks - the diagramming experts
- [**82**星][19d] [Java] [ysrc/obfusesmalitext](https://github.com/ysrc/obfusesmalitext) smali文件，jar包字符串混淆，支持gradle插件
- [**65**星][1m] [Java] [calebwhiting/java-asm-obfuscator](https://github.com/calebwhiting/java-asm-obfuscator) Obfuscates compiled java code to make it harder to reverse engineer.
- [**56**星][4m] [Java] [johnjohndoe/proguard](https://github.com/johnjohndoe/proguard) Java class file shrinker, optimizer, obfuscator, and preverifier
- [**23**星][19d] [Java] [alpheratzteam/obfuscator](https://github.com/alpheratzteam/obfuscator) Java Obfuscator
- [**18**星][25d] [Java] [damianszczepanik/silencio](https://github.com/damianszczepanik/silencio) Silencio is a Java library for transforming and converting XML, JSON, YAML, Properties and other formats. It is applicable for most operations such as obfuscation, encryption, minimisation (minifying), anonymous. Library is fully customizable and extensible.
- [**14**星][9m] [Java] [graxcode/stringer-verification-bypass](https://github.com/graxcode/stringer-verification-bypass) Patch java archives obfuscated and signed by stringer 3.x - 9.0 (
- [**9**星][4m] [Java] [mjvl/uniobfuscator](https://github.com/mjvl/uniobfuscator) Java obfuscator that hides code in comment tags and Unicode garbage by making use of Java's Unicode escapes.


***


## <a id="85a8cd8871da13161f05993c1029e867"></a>文章


- 2020.04 [hakin9] [Threadtear - Multifunctional java deobfuscation tool suite](https://hakin9.org/threadtear-multifunctional-java-deobfuscation-tool-suite/)
- 2018.09 [arxiv] [[1809.11037] A Systematic Study on Static Control Flow Obfuscation Techniques in Java](https://arxiv.org/abs/1809.11037)
- 2017.09 [360] [基于ASM的Java字符串混淆工具实现](https://www.anquanke.com/post/id/86941/)
- 2016.07 [MalwareAnalysisForHedgehogs] [Malware Analysis - Java Malware Deobfuscation](https://www.youtube.com/watch?v=SFaDTQiiiww)
- 2015.02 [contextis] [Automating Removal of Java Obfuscation](https://www.contextis.com/blog/automating-removal-of-java-obfuscation)
- 2013.07 [netspi] [Java Obfuscation Tutorial with Zelix Klassmaster](https://blog.netspi.com/java-obfuscation-tutorial-with-zelix-klassmaster/)
- 2013.02 [security] [Deobfuscating Java 7u11 Exploit from Cool Exploit Kit (CVE-2013-0431)](http://security-obscurity.blogspot.com/2013/02/deobfuscating-java-7u11-exploit-from.html)
- 2013.01 [quequero] [Malicious Java Applet Deobfuscation](https://quequero.org/2013/01/malicious-java-applet-deobfuscation/)
- 2012.11 [security] [Java Exploit Code Obfuscation and Antivirus Bypass/Evasion (CVE-2012-4681)](http://security-obscurity.blogspot.com/2012/11/java-exploit-code-obfuscation-and.html)
- 2008.09 [arxiv] [[0809.3503] JDATATRANS for Array Obfuscation in Java Source Code to Defeat Reverse Engineering from Decompiled Codes](https://arxiv.org/abs/0809.3503)
- 2008.07 [arxiv] [[0807.4309] Array Based Java Source Code Obfuscation Using Classes with Restructured Arrays](https://arxiv.org/abs/0807.4309)


# <a id="193bfef38cb82179a6115c52799286fa"></a>CMD


***


## <a id="63a2b1b7b26fa06579654d2e39cc2f33"></a>invoke-dosfuscation


### <a id="9d707b82be5392b16016bfee435f8bf6"></a>工具


- [**416**星][2y] [PS] [danielbohannon/invoke-dosfuscation](https://github.com/danielbohannon/invoke-dosfuscation) Cmd.exe Command Obfuscation Generator & Detection Test Harness


### <a id="0b5910871dcca88d837fed60e2de27b1"></a>文章


- 2018.10 [NorthSec] [Daniel Bohannon - Invoke-DOSfuscation: Techniques FOR %F IN (-style) DO (S-level CMD Obfuscation)](https://www.youtube.com/watch?v=StmzEvO3H-Q)
- 2018.07 [pcsxcetrasupport3] [A look at a Word document macro using Invoke-DOSfuscation](https://pcsxcetrasupport3.wordpress.com/2018/07/28/a-look-at-a-word-document-macro-using-invoke-dosfuscation/)




***


## <a id="0738123add9a88b1b717696ad5e3dee5"></a>文章


- 2018.03 [fireeye] [DOSfuscation: Exploring the Depths of Cmd.exe Obfuscation and Detection Techniques](https://www.fireeye.com/blog/threat-research/2018/03/dosfuscation-exploring-obfuscation-and-detection-techniques.html)


# <a id="978ec8680ae0965ce50c6948e6c740fa"></a>其他


***


## <a id="3df7c00560baca22e97aa3842646f208"></a>flare-floss


### <a id="da84308c817371ee9a7168afd8c08879"></a>工具


- [**1497**星][12d] [Py] [fireeye/flare-floss](https://github.com/fireeye/flare-floss) 自动从恶意代码中提取反混淆后的字符串
    - [floss](https://github.com/fireeye/flare-floss/tree/master/floss) 
    - [IDA插件](https://github.com/fireeye/flare-floss/blob/master/scripts/idaplugin.py) 


### <a id="524722c4a4090595c6aeb0e245793c2b"></a>文章


- 2016.05 [freebuf] [火眼实验室恶意软件开源分析工具Flare-floss](http://www.freebuf.com/sectool/105252.html)




***


## <a id="816c07719bc43d5fbdb096c357fa52cd"></a>demovfuscator


### <a id="be0c014ea3736628b4f9278b5291ac41"></a>工具


- [**516**星][12d] [C++] [kirschju/demovfuscator](https://github.com/kirschju/demovfuscator) 对抗控制流线性化的工具，反混淆器。




***


## <a id="c9354b20e62e3781b0e194d7ac7b2b1a"></a>hexraysdeob


### <a id="25deb9c341c4f5d5b2c165f85bdc7cb8"></a>工具


- [**318**星][9m] [C++] [rolfrolles/hexraysdeob](https://github.com/rolfrolles/hexraysdeob) 利用Hex-Rays microcode API破解编译器级别的混淆
- [**40**星][4m] [C++] [carbonblack/hexraysdeob](https://github.com/carbonblack/hexraysdeob) Hex-Rays microcode API plugin for breaking an obfuscating compiler




***


## <a id="a5243005269510c9270b86faaaa708f0"></a>callobfuscator


### <a id="1aac846077f425c1c6d557d9b0e9e3b0"></a>工具


- [**272**星][4m] [C++] [d35ha/callobfuscator](https://github.com/d35ha/callobfuscator) 使用不同的Windows API混淆指定的Windows API




# <a id="ac6cc2eb18f961bdbfb16151e1f9f686"></a>恶意代码


***


## <a id="1006f3d956b3a62601532cccb9ef1f8d"></a>文章


- 2020.05 [vmray] [Move Fast and Don’t Break Things (Part 2): Automated Malware De-obfuscation by Accurate API Monitoring](https://www.vmray.com/cyber-security-blog/automated-malware-de-obfuscation-by-accurate-api-monitoring-part-2/)
- 2020.05 [talosintelligence] [Threat Spotlight: Astaroth — Maze of obfuscation and evasion reveals dark stealer](https://blog.talosintelligence.com/2020/05/astaroth-analysis.html)
- 2020.04 [rootshell] [[SANS ISC] Malicious Excel With a Strong Obfuscation and Sandbox Evasion](https://blog.rootshell.be/2020/04/24/sans-isc-malicious-excel-with-a-strong-obfuscation-and-sandbox-evasion/)
- 2020.03 [welivesecurity] [Stantinko’s new cryptominer features unique obfuscation techniques | WeLiveSecurity](https://www.welivesecurity.com/2020/03/19/stantinko-new-cryptominer-unique-obfuscation-techniques/)
- 2020.02 [infosecinstitute] [What is Malware Obfuscation?](https://resources.infosecinstitute.com/category/certifications-training/malware-analysis-reverse-engineering/malware-obfuscation-encoding-encryption/malware-obfuscation/)
- 2019.11 [trendmicro] [More than a Dozen Obfuscated APT33 Botnets Used for Extreme Narrow Targeting](https://blog.trendmicro.com/trendlabs-security-intelligence/more-than-a-dozen-obfuscated-apt33-botnets-used-for-extreme-narrow-targeting/)
- 2019.11 [umbrella] [Obfuscation: The Abracadabra of Malware Authors](https://umbrella.cisco.com:443/blog/2019/11/01/obfuscation-the-abracadabra-of-malware-authors/)
- 2019.10 [HackersOnBoard] [Black Hat USA 2016 Next Generation of Exploit Kit Detection By Building Simulated Obfuscators](https://www.youtube.com/watch?v=DBjN6EVizc8)
- 2019.07 [freebuf] [教你使用Cutter和Radare2对APT32恶意程序流程图进行反混淆处理](https://www.freebuf.com/articles/network/208019.html)
- 2019.07 [arxiv] [[1907.01445] Extended Report on the Obfuscated Integration of Software Protections](https://arxiv.org/abs/1907.01445)
- 2019.06 [trendmicro] [CVE-2019-2725 Exploited and Certificate Files Used for Obfuscation to Deliver Monero Miner](https://blog.trendmicro.com/trendlabs-security-intelligence/cve-2019-2725-exploited-and-certificate-files-used-for-obfuscation-to-deliver-monero-miner/)
- 2019.05 [360] [使用Cutter和Radare2对APT32恶意程序流程图进行反混淆处理](https://www.anquanke.com/post/id/178047/)
- 2019.04 [trendmicro] [Phishing Attack Uses Browser Extension Tool SingleFile to Obfuscate Malicious Log-in Pages](https://blog.trendmicro.com/trendlabs-security-intelligence/phishing-attack-uses-browser-extension-tool-singlefile-to-obfuscate-malicious-log-in-pages/)
- 2019.03 [sucuri] [Uncommon Radixes Used in Malware Obfuscation](https://blog.sucuri.net/2019/03/uncommon-radixes-used-in-malware-obfuscation.html)
- 2019.02 [carbonblack] [Defeating Compiler-Level Obfuscations Used in APT10 Malware](https://www.carbonblack.com/2019/02/25/defeating-compiler-level-obfuscations-used-in-apt10-malware/)
- 2019.02 [4hou] [见招拆招分析银行木马：揭开恶意LNK真面目+逐步拆解混淆后Dropper](http://www.4hou.com/technology/16214.html)
- 2019.01 [4hou] [一种新型恶意软件混淆技术的逆向分析](http://www.4hou.com/reverse/15824.html)
- 2019.01 [sans] [FLOSS Every Day - Automatically Extracting Obfuscated Strings from Malware](https://www.sans.org/cyber-security-summit/archives/file/summit_archive_1492113968.pdf)
- 2018.10 [4hou] [GandCrab勒索软件的最新版本中开始引入加密和混淆功能](http://www.4hou.com/typ/14042.html)
- 2018.10 [mcafee] [Rapidly Evolving Ransomware GandCrab Version 5 Partners With Crypter Service for Obfuscation](https://securingtomorrow.mcafee.com/other-blogs/mcafee-labs/rapidly-evolving-ransomware-gandcrab-version-5-partners-with-crypter-service-for-obfuscation/)
- 2018.10 [mcafee] [Rapidly Evolving Ransomware GandCrab Version 5 Partners With Crypter Service for Obfuscation](https://www.mcafee.com/blogs/other-blogs/mcafee-labs/rapidly-evolving-ransomware-gandcrab-version-5-partners-with-crypter-service-for-obfuscation/)
- 2018.10 [mcafee] [Rapidly Evolving Ransomware GandCrab Version 5 Partners With Crypter Service for Obfuscation](https://securingtomorrow.mcafee.com/mcafee-labs/rapidly-evolving-ransomware-gandcrab-version-5-partners-with-crypter-service-for-obfuscation/)
- 2018.10 [NorthSec] [Thaís aka barbie Moreira Hamasaki - Logic against sneak obfuscated malware](https://www.youtube.com/watch?v=Zps-nz0f3qE)
- 2018.10 [checkpoint] [Labeless Part 6: How to Resolve Obfuscated API Calls in the Ngioweb Proxy Malware - Check Point Research](https://research.checkpoint.com/labeless-part-6-how-to-resolve-obfuscated-api-calls-in-the-ngioweb-proxy-malware/)
- 2018.09 [tencent] [MyKings僵尸网络最新变种突袭，攻击代码多次加密混淆，难以检测](https://s.tencent.com/research/report/531.html)
- 2018.08 [4hou] [后门混淆和反检测技术](http://www.4hou.com/technology/12718.html)
- 2018.08 [sans] [Dealing with numeric obfuscation in malicious scripts](https://isc.sans.edu/forums/diary/Dealing+with+numeric+obfuscation+in+malicious+scripts/23954/)
- 2018.07 [MalwareAnalysisForHedgehogs] [Malware Analysis - DOSfuscation Deobfuscation](https://www.youtube.com/watch?v=EBVhX_1vaoE)
- 2018.07 [aliyun] [后门混淆和反检测技术](https://xz.aliyun.com/t/2472)
- 2018.07 [360] [后门混淆和逃避技术](https://www.anquanke.com/post/id/152244/)
- 2018.07 [imperva] [The Trickster Hackers – Backdoor Obfuscation and Evasion Techniques](https://www.imperva.com/blog/2018/07/the-trickster-hackers-backdoor-obfuscation-and-evasion-techniques/)
- 2018.07 [360] [Malwarebytes 对使用混淆 Coinhive 短链接进行浏览器挖矿的调查分析](https://www.anquanke.com/post/id/150636/)
- 2018.07 [malwarebytes] [Obfuscated Coinhive shortlink reveals larger mining operation](https://blog.malwarebytes.com/threat-analysis/2018/07/obfuscated-coinhive-shortlink-reveals-larger-mining-operation/)
- 2018.06 [freebuf] [技术讨论 | NjRAT通过base64编码加密混淆Code免杀绕过360杀毒实验](http://www.freebuf.com/articles/rookie/174776.html)
- 2018.06 [serhack] [Deobfuscating and Understanding a Trojan JScript](https://serhack.me/articles/deobfuscate-understand-trojan-jscript-en)
- 2018.04 [360] [深入分析恶意软件Formbook：混淆和进程注入（下）](https://www.anquanke.com/post/id/103429/)
- 2018.04 [360] [深入分析恶意软件Formbook：混淆和进程注入（上）](https://www.anquanke.com/post/id/103403/)
- 2018.01 [trendmicro] [以俄罗斯银行为目标的恶意 Android App FakeBank 使用新的混淆技巧](https://blog.trendmicro.com/trendlabs-security-intelligence/new-mobile-malware-uses-layered-obfuscation-targets-russian-banks/)
- 2017.08 [360] [分析一款代码经过混淆处理的勒索软件下载器](https://www.anquanke.com/post/id/86707/)
- 2017.08 [ringzerolabs] [分析多层混淆的 HTML 文档（Locky勒索软件的下载器）](https://www.ringzerolabs.com/2017/08/analyzing-several-layers-of-obfuscation.html)
- 2017.08 [MalwareAnalysisForHedgehogs] [Malware Analysis - Deobfuscating Loyeetro Trojan-Spy](https://www.youtube.com/watch?v=YuWuE-qy2pg)
- 2017.08 [netskope] [Adwind RAT employs new obfuscation techniques](https://www.netskope.com/blog/adwind-rat-employs-new-obfuscation-techniques/)
- 2017.04 [ixiacom] [Deobfuscating Malicious Actor Intentions for Your Web Server](https://www.ixiacom.com/company/blog/deobfuscating-malicious-actor-intentions-your-web-server)
- 2017.03 [itsjack] [Deobfuscating API Call Strings In A ‘Banker’](https://itsjack.cc/blog/2017/03/deobfuscating-api-call-strings-in-a-banker/)
- 2017.03 [adelmas] [Analyzing and Deobfuscating FlokiBot Banking Trojan](http://adelmas.com/blog/flokibot.php)
- 2017.02 [vkremez] [Trojan-Downloader:JS/Locky: Deobfuscate and Extract IOCs](https://www.vkremez.com/2017/02/trojan-downloaderjslocky-deobfuscate.html)
- 2016.12 [rsa] [How to deobfuscate malicious browser scripts using a script debugger](https://community.rsa.com/community/products/netwitness/blog/2016/12/31/how-to-deobfuscate-malicious-browser-scripts-using-a-script-debugger)
- 2016.11 [securityblog] [Automatically extract obfuscated strings from malware](http://securityblog.gr/3879/automatically-extract-obfuscated-strings-from-malware/)
- 2016.10 [4hou] [恶意代码最新混淆技术分析](http://www.4hou.com/technology/1668.html)
- 2016.10 [broadanalysis] [EiTest campaign drops flash gate for obfuscated script sending GootKit banking malware](http://www.broadanalysis.com/2016/10/03/eitest-campaign-drops-flash-gate-for-obfuscated-script-sending-gootkit-banking-malware/)
- 2016.09 [quarkslab] [Arybo: cleaning obfuscation by playing with mixed boolean and arithmetic operations](https://blog.quarkslab.com/arybo-cleaning-obfuscation-by-playing-with-mixed-boolean-and-arithmetic-operations.html)
- 2016.08 [8090] [代码战争：伪装和狙杀，从“壳”到“病毒混淆器](http://www.8090-sec.com/archives/3159)
- 2016.08 [freebuf] [代码战争：伪装和狙杀，从“壳”到“病毒混淆器”](http://www.freebuf.com/articles/system/112631.html)
- 2016.08 [mcafee] [Obfuscated Malware Discovered on Google Play](https://www.mcafee.com/blogs/other-blogs/mcafee-labs/obfuscated-malware-discovered-google-play/)
- 2016.08 [mcafee] [Obfuscated Malware Discovered on Google Play](https://securingtomorrow.mcafee.com/mcafee-labs/obfuscated-malware-discovered-google-play/)
- 2016.07 [ixiacom] [MALWARE DELIVERY SECRETS: RTF OBFUSCATION](https://www.ixiacom.com/company/blog/malware-delivery-secrets-rtf-obfuscation)
- 2016.07 [malwarenailed] [Locky Ransomware - Obfuscated Weaponry](http://malwarenailed.blogspot.com/2016/07/locky-ransomware-obfuscated-weaponry.html)
- 2016.06 [fireeye] [Automatically Extracting Obfuscated Strings from Malware using the
FireEye Labs Obfuscated String Solver (FLOSS)](https://www.fireeye.com/blog/threat-research/2016/06/automatically-extracting-obfuscated-strings.html)
- 2016.06 [fortinet] [Obfuscated Bitcoin Miner Propagates Through FTP Using Password Dictionary](https://www.fortinet.com/blog/threat-research/obfuscated-bitcoin-miner-propagates-through-ftp-using-password-dictionary.html)
- 2016.05 [jeffsoh] [Heavy Obfuscation != Malicious](http://jeffsoh.blogspot.com/2016/05/heavy-obfuscation-malicious.html)
- 2016.04 [freebuf] [恶意软件混淆检测算法分析](http://www.freebuf.com/articles/terminal/102984.html)
- 2015.09 [freebuf] [一种在恶意软件中常见的字符串和Payload混淆技术](http://www.freebuf.com/articles/system/77244.html)
- 2015.09 [securityintelligence] [An Example of Common String and Payload Obfuscation Techniques in Malware](https://securityintelligence.com/an-example-of-common-string-and-payload-obfuscation-techniques-in-malware/)
- 2015.06 [malwarebytes] [Complex Method of Obfuscation Found in Dropper RealShell](https://blog.malwarebytes.com/cybercrime/2015/06/complex-method-of-obfuscation-found-in-dropper-realshell/)
- 2015.02 [arxiv] [[1502.03245] FEEBO: An Empirical Evaluation Framework for Malware Behavior Obfuscation](https://arxiv.org/abs/1502.03245)
- 2014.05 [mcafee] [Necurs, Zbot Droppers Use Obfuscated Windows XP Detection to Bypass Automated Analysis](https://www.mcafee.com/blogs/other-blogs/mcafee-labs/necurs-zbot-droppers-use-obfuscated-windows-xp-detection-bypass-automated-analysis/)
- 2014.05 [mcafee] [Necurs, Zbot Droppers Use Obfuscated Windows XP Detection to Bypass Automated Analysis](https://securingtomorrow.mcafee.com/mcafee-labs/necurs-zbot-droppers-use-obfuscated-windows-xp-detection-bypass-automated-analysis/)
- 2014.03 [k7computing] [Volume III: Who aM I? Confessions of an Obfuscated JS Worm](https://blog.k7computing.com/?p=2304)
- 2014.03 [k7computing] [Volume III: Who aM I? Confessions of an Obfuscated JS Worm](http://blog.k7computing.com/2014/03/volume-iii-who-am-i-confessions-of-an-obfuscated-js-worm/)
- 2014.03 [k7computing] [Volume II: Who aM I? Confessions of an Obfuscated JS Worm](https://blog.k7computing.com/?p=2242)
- 2014.03 [k7computing] [Volume II: Who aM I? Confessions of an Obfuscated JS Worm](http://blog.k7computing.com/2014/03/volume-ii-who-am-i-confessions-of-an-obfuscated-js-worm/)
- 2014.03 [k7computing] [Volume I: Who aM I? Confessions of an Obfuscated JS Worm](https://blog.k7computing.com/?p=2156)
- 2014.03 [k7computing] [Volume I: Who aM I? Confessions of an Obfuscated JS Worm](http://blog.k7computing.com/2014/03/volume-i-who-am-i-confessions-of-an-obfuscated-js-worm/)
- 2013.05 [sans] [Tools for Examining XOR Obfuscation for Malware Analysis](https://digital-forensics.sans.org/blog/2013/05/14/tools-for-examining-xor-obfuscation-for-malware-analysis)
- 2013.03 [malwarebytes] [Obfuscation: Malware’s best friend](https://blog.malwarebytes.com/threat-analysis/2013/03/obfuscation-malwares-best-friend/)
- 2013.01 [checkpoint] [Tales from the Crypter: Thwarting Malware Obfuscation with Threat Emulation | Check Point Software Blog](https://blog.checkpoint.com/2013/01/30/tales-crypter-thwarting-malware-obfuscation-threat-emulation/)
- 2012.12 [forcepoint] [Sharing the Experience of Deobfuscating a Trojan](https://www.forcepoint.com/blog/security-labs/sharing-experience-deobfuscating-trojan)
- 2012.06 [sans] [Decoding Common XOR Obfuscation in Malicious Code](https://isc.sans.edu/forums/diary/Decoding+Common+XOR+Obfuscation+in+Malicious+Code/13354/)
- 2011.08 [webroot] [Trojans Employ Misdirection Instead of Obfuscation](https://www.webroot.com/blog/2011/08/25/trojans-employ-misdirection-instead-of-obfuscation/)
- 2010.12 [yurichev] [7-Dec-2010: Making C compiler generate obfuscated code](https://yurichev.com/blog/58/)
- 2010.03 [securelist] [New Brazilian banking Trojans recycle old URL obfuscation tricks](https://securelist.com/new-brazilian-banking-trojans-recycle-old-url-obfuscation-tricks/29558/)
- 2008.04 [secshoggoth] [Obfuscating Malware for Fun and Prizes](http://secshoggoth.blogspot.com/2008/04/obfuscating-malware-for-fun-and-prizes.html)
- 2006.12 [pediy] [[翻译]注入 动态生成及混淆的恶意代码的检测](https://bbs.pediy.com/thread-35766.htm)


# <a id="48905dbcdd16a4b3ca77dc0193723720"></a>新添加-混淆


***


## <a id="40f09a7bfb3cb928c2f912aa6634c775"></a>工具


- [**215**星][1y] [Java] [neo23x0/fnord](https://github.com/neo23x0/fnord) 一种用于混淆代码的模式提取器
- [**185**星][3y] [PS] [cobbr/obfuscatedempire](https://github.com/cobbr/obfuscatedempire) Empire的Fork，集成了Invoke-Obfuscation
- [**165**星][2m] [JS] [zsoltszabo/node-uglifier](https://github.com/zsoltszabo/node-uglifier) 完全自动合并和混淆(丑化)整个NodeJs项目到一个文件与外部文件选项
- [**161**星][17d] [Py] [z0noxz/powerstager](https://github.com/z0noxz/powerstager) 创建可执行文件，用于下载PowerShell Payload，将其加载到内存，并使用混淆的EC方法运行
- [**152**星][26d] [Go] [znly/strobfus](https://github.com/znly/strobfus) String obfuscation
- [**142**星][2y] [Py] [gumblex/ptproxy](https://github.com/gumblex/ptproxy) Turn any pluggable transport for Tor into an obfuscating TCP tunnel.
- [**132**星][8m] [C#] [nyan-x-cat/lime-crypter](https://github.com/nyan-x-cat/lime-crypter) Simple obfuscation tool
- [**131**星][9m] [C] [changeofpace/overwatch-dump-fix](https://github.com/changeofpace/overwatch-dump-fix) x64dbg plugin which removes anti-dumping and obfuscation techniques from the popular FPS game Overwatch.
- [**131**星][6m] [PHP] [propaganistas/laravel-fakeid](https://github.com/propaganistas/laravel-fakeid) Automatic model ID obfuscation in routes for Laravel 5
- [**120**星][4m] [we5ter/flerken](https://github.com/we5ter/flerken) A Solution For Cross-Platform Obfuscated Commands Detection
- [**114**星][4m] [Py] [ekultek/graffiti](https://github.com/ekultek/graffiti) A tool to generate obfuscated one liners to aid in penetration testing
- [**106**星][16d] [C] [vmonaco/kloak](https://github.com/vmonaco/kloak) Keystroke-level online anonymization kernel: obfuscates typing behavior at the device level.
- [**101**星][3y] [Py] [mr-un1k0d3r/sct-obfuscator](https://github.com/mr-un1k0d3r/sct-obfuscator) Cobalt Strike SCT payload obfuscator
- [**100**星][2m] [C] [elfmaster/dsym_obfuscate](https://github.com/elfmaster/dsym_obfuscate) Obfuscates dynamic symbol table
- [**93**星][4y] [C] [osandamalith/ipobfuscator](https://github.com/osandamalith/ipobfuscator) A simple tool to convert the IP to a DWORD IP
- [**90**星][19d] [C++] [koemeet/rtti-obfuscator](https://github.com/koemeet/rtti-obfuscator) Obfuscates all RTTI (Run-time type information) inside a binary
- [**88**星][2y] [C] [lloydlabs/windows-api-hashing](https://github.com/lloydlabs/windows-api-hashing) 通过哈希混淆API
- [**76**星][11d] [Java] [radioegor146/native-obfuscator](https://github.com/radioegor146/native-obfuscator) Java .class to .cpp converter for use with JNI
- [**73**星][2y] [C++] [nickcano/relocbonus](https://github.com/nickcano/relocbonus) An obfuscation tool for Windows which instruments the Windows Loader into acting as an unpacking engine.
- [**71**星][4y] [Py] [kkar/vbs-obfuscator-in-python](https://github.com/kkar/vbs-obfuscator-in-python) VBScript混淆允许pentester绕过对策
- [**71**星][24d] [TS] [javascript-obfuscator/react-native-obfuscating-transformer](https://github.com/javascript-obfuscator/react-native-obfuscating-transformer) Obfuscation for React Native bundles
- [**66**星][2m] [Py] [nullhypothesis/scramblesuit](https://github.com/nullhypothesis/scramblesuit) The ScrambleSuit traffic obfuscation protocol.
- [**59**星][3y] [Py] [amoulu/tinysmaliemulator](https://github.com/amoulu/tinysmaliemulator) A very minimalist smali emulator that could be used to "decrypt" obfuscated strings
- [**58**星][12d] [JS] [coston/react-obfuscate](https://github.com/coston/react-obfuscate) An intelligent React component to obfuscate any contact link!
- [**57**星][14d] [C++] [haidragon/study_obscure](https://github.com/haidragon/study_obscure) 混淆反混淆
- [**55**星][2y] [PS] [mr-un1k0d3r/base64-obfuscator](https://github.com/mr-un1k0d3r/base64-obfuscator) Simple PowerShell Base64 encoder to avoid detection of your malicious payload
- [**54**星][1m] [Py] [mushorg/oschameleon](https://github.com/mushorg/oschameleon) OS Fingerprint Obfuscation for modern Linux Kernels
- [**47**星][23d] [C++] [thebabush/dumb-obfuscator](https://github.com/thebabush/dumb-obfuscator) Tutorial on how to write the dumbest obfuscator I could think of.
- [**46**星][4m] [C++] [timelifeczy/sheller](https://github.com/timelifeczy/sheller) 一键加壳/脱壳，混淆，花指令，反调试等
- [**45**星][4m] [Assembly] [martinvelez/w32evol](https://github.com/martinvelez/w32evol) An obfuscation engine which obfuscates Intel x86 32-bit binary code.
- [**43**星][2y] [Py] [nikshepsvn/scatterfly](https://github.com/nikshepsvn/scatterfly) An attempt to improve user privacy by intelligent data obfuscation.
- [**43**星][12d] [C] [tum-i22/obfuscation-benchmarks](https://github.com/tum-i22/obfuscation-benchmarks) A set of programs used for benchmarking the strength of obfuscation
- [**42**星][4y] [Py] [cylance/markovobfuscate](https://github.com/cylance/MarkovObfuscate) Use Markov Chains to obfuscate data as other data
- [**39**星][1m] [Shell] [dlshad/openvpn-shapeshifter](https://github.com/dlshad/openvpn-shapeshifter) This script will automatically guide you to install and configure your OpenVPN server with Shapeshifter Dispatcher (obfuscation) which will allow you to bypass the DPI blockage on OpenVPN. This setup will offer the users the freedom to choose between regular OpenVPN connection or obfuscated one, they actually can use both! OpenVPN is the VPN pro…
- [**37**星][4m] [Shell] [hromie/obfs4proxy-openvpn](https://github.com/hromie/obfs4proxy-openvpn) Obfuscating OpenVPN traffic using obfs4proxy
- [**36**星][4m] [Visual Basic] [doctorlai/vbscript_obfuscator](https://github.com/doctorlai/vbscript_obfuscator) The VBScript Obfuscator written in VBScript
- [**33**星][1y] [C] [mmyydd/relative-pattern](https://github.com/mmyydd/relative-pattern) Recover control flow graph from obfuscated codes
- [**33**星][1m] [C++] [hikariobfuscator/core](https://github.com/hikariobfuscator/core) Shared Obfuscation Core
- [**31**星][1y] [C] [segnolin/vobfus](https://github.com/segnolin/vobfus) virtualization obfuscator inspired by juhajong/vm-obfuscator
- [**29**星][5m] [Java] [rabrg/refactored-client](https://github.com/rabrg/refactored-client) Refactoring the obfuscated v317 of the RuneScape (RuneTek 3) client.
- [**29**星][6m] [Java] [guardianproject/pluto](https://github.com/guardianproject/pluto) Pluggable Library (for) Using Traffic Obfuscation: DEPRECATED - SEE LINK FOR NEW PROJECT
- [**28**星][2y] [Py] [mgeeky/visualbasicobfuscator](https://github.com/mgeeky/visualbasicobfuscator) Visual Basic Code universal Obfuscator intended to be used during penetration testing assignments.
- [**27**星][9m] [PS] [danmcinerney/invoke-cats](https://github.com/danmcinerney/invoke-cats) Obfuscated Invoke-Mimikatz
- [**27**星][4m] [Go] [getlantern/lampshade](https://github.com/getlantern/lampshade) Obfuscated encrypted network protocol for Lantern
- [**26**星][8m] [PHP] [krowinski/tinyid](https://github.com/krowinski/tinyid) Shorten and obfuscate IDs
- [**24**星][12d] [C++] [d35ha/xobf](https://github.com/d35ha/xobf) Simple x86/x86_64 instruction level obfuscator based on a basic SBI engine
- [**21**星][16d] [HTML] [guillac/jsbatchobfuscator](https://github.com/guillac/jsbatchobfuscator) JSBatchobfuscator is a simple obfuscator for batch script
- [**19**星][11d] [Jupyter Notebook] [antoinevastel/simplejsobfuscator](https://github.com/antoinevastel/simplejsobfuscator) Example of a simple JS obfuscator
- [**19**星][2m] [maxfong/obfuscatorxcplugin](https://github.com/maxfong/obfuscatorxcplugin) 逻辑混淆XCode插件
- [**18**星][7m] [Py] [transferwise/pg_ninja](https://github.com/transferwise/pg_ninja) The ninja elephant obfuscation and replica tool
- [**17**星][10m] [Py] [twisteroidambassador/udpack](https://github.com/twisteroidambassador/udpack) UDPack is an extensible generic UDP packet obfuscator.
- [**16**星][11m] [Haxe] [markknol/hxobfuscator](https://github.com/markknol/hxobfuscator) Shortens names for smaller output and better gzip compression in Haxe/JavaScript builds
- [**16**星][19d] [Py] [c0cc/code_obfuscate](https://github.com/c0cc/code_obfuscate) python 字节码混淆工具
- [**14**星][6m] [PHP] [networkteam/networkteam.neos.mailobfuscator](https://github.com/networkteam/networkteam.neos.mailobfuscator) Email address obfuscation for Neos CMS
- [**14**星][3m] [Go] [potato-industries/gohide](https://github.com/potato-industries/gohide) tunnel port to port traffic over an obfuscated channel with AES-GCM encryption.
- [**13**星][5m] [PHP] [pelock/autoit-obfuscator](https://github.com/pelock/autoit-obfuscator) AutoIt Obfuscator lets you protect AutoIt script source code against analysis, reverse engineering and decompilation using advanced obfuscation techniques and polymorphic encryption.
- [**13**星][1y] [Swift] [mrigankgupta/mgobfuscator](https://github.com/mrigankgupta/mgobfuscator) An easy encryptor / decryptor for iOS
- [**10**星][6m] [C#] [kendtimothy/obfuscation](https://github.com/kendtimothy/obfuscation) Obfuscation / Integer Masking library to encrypt numeric id to short string, generating a similar result to YouTube video id.
- [**9**星][2y] [Py] [d00rt/easy_way_nymaim](https://github.com/d00rt/easy_way_nymaim) IDA脚本, 用于去除恶意代码nymaim的混淆,创建干净的idb
- [**9**星][2m] [C] [olbat/binsh](https://github.com/olbat/binsh) Shell script obfuscation tool (compile, encrypt and passphrase-protect)
- [**8**星][4m] [C] [mickdec/haremg0.b-cl](https://github.com/mickdec/haremg0.b-cl) Fully obfuscated trojan generator for windows.
- [**7**星][3y] [F#] [enkomio/mealyobfuscator](https://github.com/enkomio/mealyobfuscator) String obfuscator based on the Mealy automata
- [**7**星][1y] [PHP] [mattiasgeniar/encoder](https://github.com/mattiasgeniar/encoder) Encoding, Decoding and Obfuscating strings.
- [**6**星][5m] [Java] [itemic/rotacsufbo](https://github.com/itemic/rotacsufbo) did u know the name of the repo is obfuscator backwards?
- [**5**星][2y] [C++] [polidea/siriusobfuscator-symbolextractorandrenamer](https://github.com/polidea/siriusobfuscator-symbolextractorandrenamer) 
- [**4**星][2y] [Py] [jamcut/obfuscate_launcher](https://github.com/jamcut/obfuscate_launcher) Simple script for obfuscating payload launchers
- [**4**星][6m] [Py] [pwnslinger/smc](https://github.com/pwnslinger/smc) Self-modifying Code de-obfuscation
- [**3**星][2y] [Swift] [polidea/siriusobfuscator-verificationsuite](https://github.com/polidea/siriusobfuscator-verificationsuite) 
- [**3**星][4m] [Java] [tedstardev/mojang2tsrg](https://github.com/tedstardev/mojang2tsrg) A small tool that converts Mojang's ProGuard obfuscation map to TSRG format, for use by SpecialSource
- [**2**星][2y] [ObjC] [jacksujunjie/safedemo](https://github.com/jacksujunjie/safedemo) Objective-C代码混淆(网络安全)
- [**2**星][1y] [Py] [nlog2n/pyobfuscator](https://github.com/nlog2n/pyobfuscator) Python code obfuscator
- [**2**星][2y] [Ruby] [polidea/siriusobfuscator-fileextractor](https://github.com/polidea/siriusobfuscator-fileextractor) 
- [**1**星][2y] [Jupyter Notebook] [s-mohammad-hashemi/sst](https://github.com/s-mohammad-hashemi/sst) Stochastic Substitute Training: A Gray-box Approach to Craft Adversarial Examples Against Gradient Obfuscation Defenses
- [**1**星][2y] [C] [ryanlederman/huhu.c](https://github.com/ryanlederman/huhu.c) My attempt at C obfuscation (and a running joke on IRC) - yes, it works!
- [**0**星][1y] [PS] [irq8/obfpsh](https://github.com/irq8/obfpsh) Preobfuscated Empire module source with Invoke-Obfuscation for easy cloning. /data/obfuscated_module_source
- [**0**星][4y] [Py] [zonksec/dakotacon-ctf-extension-crusher](https://github.com/zonksec/dakotacon-ctf-extension-crusher) quick and dirty script to decode and extract obfuscated files.
- [**None**星][C++] [eaglx/vmprotect](https://github.com/eaglx/vmprotect) Obfuscation method using virtual machines.
- [**None**星][C++] [meme/hellscape](https://github.com/meme/hellscape) GIMPLE obfuscator for C, C++, Go, ... all supported GCC targets and front-ends that use GIMPLE.


***


## <a id="d90fb43c51f97711585f6906a045de96"></a>文章


- 2020.04 [blackhillsinfosec] [Getting Started With ROT Obfuscation](https://www.blackhillsinfosec.com/getting-started-with-rot-obfuscation/)
- 2020.04 [rootshell] [[SANS ISC] Obfuscated with a Simple 0x0A](https://blog.rootshell.be/2020/04/03/sans-isc-obfuscated-with-a-simple-0x0a/)
- 2020.03 [virusbulletin] [VB2019 paper: Defeating APT10 compiler-level obfuscations](https://www.virusbulletin.com/blog/2020/03/vb2019-paper-defeating-apt10-compiler-level-obfuscations/)
- 2020.01 [aliyun] [X86指令混淆之函数分析和代码块粉碎](https://xz.aliyun.com/t/7091)
- 2019.12 [t00ls] [CMD命令混淆浅析](https://www.t00ls.net/articles-54517.html)
- 2019.12 [trendmicro] [Obfuscation Tools Found in the Capesand Exploit Kit Possibly Used in “KurdishCoder” Campaign](https://blog.trendmicro.com/trendlabs-security-intelligence/obfuscation-tools-found-in-the-capesand-exploit-kit-possibly-used-in-kurdishcoder-campaign/)
- 2019.11 [p0w3rsh3ll] [Hunting for obfuscation](https://p0w3rsh3ll.wordpress.com/2019/11/15/hunting-for-obfuscation/)
- 2019.11 [freebuf] [猫鼠游戏: 持续渗透中的高级命令混淆对抗 | CIS 2019议题前瞻](https://www.freebuf.com/fevents/219126.html)
- 2019.11 [binarydefense] [Revenge is a Dish Best Served... Obfuscated? - Binary Defense](https://www.binarydefense.com/revenge-is-a-dish-best-served-obfuscated/)
- 2019.10 [Cooper] [Defeating APT10 Compiler-level Obfuscations - Takahiro Haruyama](https://www.youtube.com/watch?v=e_uLcgHRs1Y)
- 2019.10 [shaurya] [Obfuscated/Polyglot XSS Payloads Simplified with references.](https://medium.com/p/157e95b1d601)
- 2019.09 [quarkslab] [Epona and the Obfuscation Paradox: Transparent for Users, a Pain for Reversers](https://blog.quarkslab.com/epona-and-the-obfuscation-paradox-transparent-for-users-a-pain-for-reversers.html)
- 2019.08 [proofpoint] [Phishing Actor Using XOR Obfuscation Graduates to Enterprise Cloud Storage on AWS](https://www.proofpoint.com/us/threat-insight/post/phishing-actor-using-xor-obfuscation-graduates-enterprise-cloud-storage-aws)
- 2019.08 [trendmicro] [Latest Trickbot Campaign Delivered via Highly Obfuscated JS File](https://blog.trendmicro.com/trendlabs-security-intelligence/latest-trickbot-campaign-delivered-via-highly-obfuscated-js-file/)
- 2019.08 [infosecinstitute] [MITRE ATT&CK vulnerability spotlight: Obfuscated files or information](https://resources.infosecinstitute.com/mitre-attck-vulnerability-spotlight-obfuscated-files-or-information/)
- 2019.07 [aliyun] [关于对antSword(蚁剑)进行流量混淆处理的解决方案](https://xz.aliyun.com/t/5756)
- 2019.06 [freebuf] [Graffiti：一款专为渗透测试人员设计的混淆代码One Liner](https://www.freebuf.com/sectool/206565.html)
- 2019.06 [trustedsec] [On the possibility of obfuscating code using neural networks](https://www.trustedsec.com/2019/06/on-the-possibility-of-obfuscating-code-using-neural-networks/)
- 2019.05 [compass] [Reversing obfuscated passwords](https://blog.compass-security.com/2019/05/reversing-obfuscated-passwords/)
- 2019.05 [arxiv] [[1905.09778] Privacy-Preserving Obfuscation of Critical Infrastructure Networks](https://arxiv.org/abs/1905.09778)
- 2019.05 [aliyun] [混淆IDA F5的一个小技巧-x86](https://xz.aliyun.com/t/5062)
- 2019.05 [aliyun] [混淆IDA F5的一个小技巧-x64](https://xz.aliyun.com/t/4994)
- 2019.05 [talosintelligence] [Qakbot levels up with new obfuscation techniques](https://blog.talosintelligence.com/2019/05/qakbot-levels-up-with-new-obfuscation.html)
- 2019.04 [urlteam] [爬虫解决网站混淆JS跳转](https://www.urlteam.cn/2019/04/%e7%88%ac%e8%99%ab%e8%a7%a3%e5%86%b3%e7%bd%91%e7%ab%99%e6%b7%b7%e6%b7%86js%e8%b7%b3%e8%bd%ac/)
- 2019.04 [arxiv] [[1904.09516] EOP: An Encryption-Obfuscation Solution for Protecting PCBs Against Tampering and Reverse Engineering](https://arxiv.org/abs/1904.09516)
- 2019.04 [arxiv] [[1904.09429] Chaotic Compilation for Encrypted Computing: Obfuscation but Not in Name](https://arxiv.org/abs/1904.09429)
- 2019.04 [nviso] [Circumventing SSL Pinning in obfuscated apps with OkHttp](https://blog.nviso.be/2019/04/02/circumventing-ssl-pinning-in-obfuscated-apps-with-okhttp/)
- 2019.04 [NDSSSymposium] [NDSS 2019 OBFUSCURO: A Commodity Obfuscation Engine on Intel SGX](https://www.youtube.com/watch?v=FFoOk1_FDno)
- 2019.03 [arxiv] [[1904.00188] PILOT: Password and PIN Information Leakage from Obfuscated Typing Videos](https://arxiv.org/abs/1904.00188)
- 2019.03 [freebuf] [SharPyShell：用于C# Web应用程序的小型混淆版WebShell](https://www.freebuf.com/sectool/198286.html)
- 2019.03 [sucuri] [More on Dnsden[.]biz Swipers and Radix Obfuscation](https://blog.sucuri.net/2019/03/more-on-dnsden-biz-swipers-and-radix-obfuscation.html)
- 2019.03 [arxiv] [[1903.02601] Attack Graph Obfuscation](https://arxiv.org/abs/1903.02601)
- 2019.03 [arxiv] [[1903.00841] CodeTrolley: Hardware-Assisted Control Flow Obfuscation](https://arxiv.org/abs/1903.00841)
- 2019.02 [aliyun] [使用机器学习检测混淆过的cmd命令](https://xz.aliyun.com/t/4122)
- 2019.02 [xplodwild] [Reverse engineering of a mobile game, part 3: Now, it’s obfuscated](https://medium.com/p/9c31e29c386b)
- 2019.02 [TechnicalMujeeb] [Install and use Ip obfuscator tool in Termux | termux 2019](https://www.youtube.com/watch?v=-T-EAKv_c_g)
- 2019.02 [arxiv] [[1902.06146] Compiled Obfuscation for Data Structures in Encrypted Computing](https://arxiv.org/abs/1902.06146)
- 2019.02 [seowhistleblower] [Cheat Engine Tutorial: How to Convert AA Scripts to Lua and Obfuscate Trainer Data! [Terraria]](https://www.youtube.com/watch?v=eEg3q2qocwQ)
- 2019.01 [klee] [A Framework for Measuring Software Obfuscation Resilience Against Automated Attacks](https://rawgit.com/alexxnica/publications-clones/master/PID3580639.pdf)
- 2019.01 [klee] [Control Flow Obfuscation using Neural Network to Fight Concolic Testing](http://ink.library.smu.edu.sg/sis_research/2260/)
- 2018.12 [freebuf] [新型诈骗花样多，使用多种混淆方法绕过安全检测](https://www.freebuf.com/articles/network/192648.html)
- 2018.12 [aliyun] [使用机器学习检测混淆的命令行](https://xz.aliyun.com/t/3485)
- 2018.11 [fireeye] [Obfuscated Command Line Detection Using Machine Learning](https://www.fireeye.com/blog/threat-research/2018/11/obfuscated-command-line-detection-using-machine-learning.html)
- 2018.11 [arxiv] [[1811.12365] (Un)Encrypted Computing and Indistinguishability Obfuscation](https://arxiv.org/abs/1811.12365)
- 2018.11 [trustwave] [解析一个感恩节诈骗行动中使用的MS Office文件](https://www.trustwave.com/Resources/SpiderLabs-Blog/Demystifying-Obfuscation-Used-in-the-Thanksgiving-Spam-Campaign/)
- 2018.11 [ironcastle] [Basic Obfuscation With Permissive Languages, (Fri, Nov 16th)](https://www.ironcastle.net/basic-obfuscation-with-permissive-languages-fri-nov-16th/)
- 2018.11 [sans] [Basic Obfuscation With Permissive Languages](https://isc.sans.edu/forums/diary/Basic+Obfuscation+With+Permissive+Languages/24318/)
- 2018.11 [pediy] [[原创]Null混淆](https://bbs.pediy.com/thread-247680.htm)
- 2018.11 [malwarebytes] [Browlock flies under the radar with complete obfuscation](https://blog.malwarebytes.com/threat-analysis/2018/11/browlock-flies-under-the-radar-with-complete-obfuscation/)
- 2018.10 [arxiv] [[1810.10031] Stochastic Substitute Training: A Gray-box Approach to Craft Adversarial Examples Against Gradient Obfuscation Defenses](https://arxiv.org/abs/1810.10031)
- 2018.10 [pediy] [[原创] 关于代码混淆以及垃圾代码的处理，第一篇(寄存器混淆)](https://bbs.pediy.com/thread-247422.htm)
- 2018.10 [pediy] [[原创]代码混淆之我见（一）](https://bbs.pediy.com/thread-247128.htm)
- 2018.10 [arxiv] [[1810.01571] Distributing and Obfuscating Firewalls via Oblivious Bloom Filter Evaluation](https://arxiv.org/abs/1810.01571)
- 2018.09 [360] [DDE混淆的3种新方法](https://www.anquanke.com/post/id/161041/)
- 2018.09 [aliyun] [三种新型的DDE混淆方法](https://xz.aliyun.com/t/2824)
- 2018.09 [arxiv] [[1809.10743] SAIL: Machine Learning Guided Structural Analysis Attack on Hardware Obfuscation](https://arxiv.org/abs/1809.10743)
- 2018.09 [infosecinstitute] [Reverse Engineering Obfuscated Assemblies [Updated 2018]](https://resources.infosecinstitute.com/reverse-engineering-obfuscated-assemblies/)
- 2018.09 [reversinglabs] [Three New DDE Obfuscation Methods](https://blog.reversinglabs.com/blog/cvs-dde-exploits-and-obfuscation)
- 2018.09 [hexblog] [Hex-Rays Microcode API vs. Obfuscating Compiler](http://www.hexblog.com/?p=1248)
- 2018.09 [arxiv] [[1809.06207] Algorithmic Obfuscation over GF($2^m$)](https://arxiv.org/abs/1809.06207)
- 2018.09 [arxiv] [[1809.01562] Probabilistic Modeling and Inference for Obfuscated Cyber Attack Sequences](https://arxiv.org/abs/1809.01562)
- 2018.08 [ironcastle] [Identifying numeric obfuscation, (Sun, Aug 26th)](https://www.ironcastle.net/identifying-numeric-obfuscation-sun-aug-26th/)
- 2018.08 [sans] [Identifying numeric obfuscation](https://isc.sans.edu/forums/diary/Identifying+numeric+obfuscation/24028/)
- 2018.08 [arxiv] [[1808.07432] A Developer-Friendly Library for Smart Home IoT Privacy-Preserving Traffic Obfuscation](https://arxiv.org/abs/1808.07432)
- 2018.08 [acolyer] [Obfuscated gradients give a false sense of security: circumventing defenses to adversarial examples](https://blog.acolyer.org/2018/08/15/obfuscated-gradients-give-a-false-sense-of-security-circumventing-defenses-to-adversarial-examples/)
- 2018.08 [sans] [Numeric obfuscation: another example](https://isc.sans.edu/forums/diary/Numeric+obfuscation+another+example/23960/)
- 2018.08 [dist67] [Dealing With Numeric Obfuscation](https://www.youtube.com/watch?v=rxfnT_IUTNw)
- 2018.07 [arxiv] [[1807.09464] Specification-Based Protocol Obfuscation](https://arxiv.org/abs/1807.09464)
- 2018.07 [arxiv] [[1807.08456] On the Anonymization of Differentially Private Location Obfuscation](https://arxiv.org/abs/1807.08456)
- 2018.07 [arxiv] [[1807.01860] Privacy-preserving Machine Learning through Data Obfuscation](https://arxiv.org/abs/1807.01860)
- 2018.06 [arxiv] [[1806.10313] DeepObfuscation: Securing the Structure of Convolutional Neural Networks via Knowledge Distillation](https://arxiv.org/abs/1806.10313)
- 2018.06 [HackerSploit] [AV/IDS Evasion With Msfvenom - Payload Encoding Through Obfuscation](https://www.youtube.com/watch?v=ubXCiJ0fl-k)
- 2018.06 [arxiv] [[1806.02011] DMOS-PUF: Dynamic Multi-key-selection Obfuscation for Strong PUFs against Machine Learning Attacks](https://arxiv.org/abs/1806.02011)
- 2018.06 [arxiv] [[1806.02432] Obfuscation Resilient Search through Executable Classification](https://arxiv.org/abs/1806.02432)
- 2018.06 [arxiv] [[1806.01393] REORDER: Securing Dynamic-Priority Real-Time Systems Using Schedule Obfuscation](https://arxiv.org/abs/1806.01393)
- 2018.05 [arxiv] [[1805.08866] Author Obfuscation Using Generalised Differential Privacy](https://arxiv.org/abs/1805.08866)
- 2018.05 [graxcoding] [Taking a closer look at Zelix KlassMaster’s Flow Obfuscation](https://medium.com/p/7d8a17fdfa57)
- 2018.05 [arxiv] [[1805.02684] Improving Network Intrusion Detection Classifiers by Non-payload-Based Exploit-Independent Obfuscations: An Adversarial Approach](https://arxiv.org/abs/1805.02684)
- 2018.04 [arxiv] [[1804.11275] LUT-Lock: A Novel LUT-based Logic Obfuscation for FPGA-Bitstream and ASIC-Hardware Protection](https://arxiv.org/abs/1804.11275)
- 2018.04 [arxiv] [[1805.00054] Benchmarking the Capabilities and Limitations of SAT Solvers in Defeating Obfuscation Schemes](https://arxiv.org/abs/1805.00054)
- 2018.04 [arxiv] [[1804.04779] A Hybrid Model for Identity Obfuscation by Face Replacement](https://arxiv.org/abs/1804.04779)
- 2018.04 [sucuri] [Obfuscation Through Legitimate Appearances](https://blog.sucuri.net/2018/04/obfuscation-through-legitimate-appearances.html)
- 2018.03 [arxiv] [[1803.10133] You are your Metadata: Identification and Obfuscation of Social Media Users using Metadata Information](https://arxiv.org/abs/1803.10133)
- 2018.03 [360] [Cobalt Strike：使用混淆技术绕过Windows Defender](https://www.anquanke.com/post/id/101308/)
- 2018.03 [offensiveops] [Empire, Kaspersky & Obfuscation oh my!](http://www.offensiveops.io/tools/empire-kaspersky-obfuscation-oh-my/)
- 2018.03 [aliyun] [Cobalt Strike——利用混淆处理绕过Windows Defender](https://xz.aliyun.com/t/2173)
- 2018.03 [offensiveops] [使用混淆绕过Windows Defender](http://www.offensiveops.io/tools/cobalt-strike-bypassing-windows-defender-with-obfuscation/)
- 2018.03 [aliyun] [深入探索数据库攻击技术 Part 1：SQL混淆](https://xz.aliyun.com/t/2154)
- 2018.03 [arxiv] [[1803.03332] Deep RNN-Oriented Paradigm Shift through BOCANet: Broken Obfuscated Circuit Attack](https://arxiv.org/abs/1803.03332)
- 2018.03 [pediy] [[原创]使用Unicorn Engine绕过混淆完成算法的调用](https://bbs.pediy.com/thread-225018.htm)
- 2018.03 [pediy] [[翻译]手把手静态分析FinSpy VM：第一部分，x86去混淆](https://bbs.pediy.com/thread-224911.htm)
- 2018.02 [360] [一类混淆变形的Webshell分析](https://www.anquanke.com/post/id/98889/)
- 2018.02 [imperva] [A Deep Dive into Database Attacks [Part I]: SQL Obfuscation](https://www.imperva.com/blog/2018/02/database-attacks-sql-obfuscation/)
- 2018.02 [arxiv] [[1802.04259] Sphinx: A Secure Architecture Based on Binary Code Diversification and Execution Obfuscation](https://arxiv.org/abs/1802.04259)
- 2018.02 [freebuf] [任意用户密码重置（三）：用户混淆](http://www.freebuf.com/articles/web/162152.html)
- 2018.02 [arxiv] [[1802.02789] Exploiting Spin-Orbit Torque Devices as Reconfigurable Logic for Circuit Obfuscation](https://arxiv.org/abs/1802.02789)
- 2018.02 [arxiv] [[1802.00420] Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples](https://arxiv.org/abs/1802.00420)
- 2018.01 [pediy] [[原创]汇编指令级混淆器的实现](https://bbs.pediy.com/thread-224351.htm)
- 2018.01 [f5] [What is HTML Field Obfuscation?](https://devcentral.f5.com/articles/what-is-html-field-obfuscation-29144)
- 2018.01 [arxiv] [[1801.02742] A Large Scale Investigation of Obfuscation Use in Google Play](https://arxiv.org/abs/1801.02742)
- 2017.12 [dist67] [Dealing with obfuscated rtf files](https://www.youtube.com/watch?v=2XdfljBRr0A)
- 2017.12 [sans] [Dealing with obfuscated RTF files](https://isc.sans.edu/forums/diary/Dealing+with+obfuscated+RTF+files/23169/)
- 2017.12 [360] [深入分析PE可执行文件是如何进行加壳和数据混淆的](https://www.anquanke.com/post/id/90173/)
- 2017.12 [arxiv] [[1712.04130] Topology of Privacy: Lattice Structures and Information Bubbles for Inference and Obfuscation](https://arxiv.org/abs/1712.04130)
- 2017.12 [antoinevastel] [What is obfuscation?](https://antoinevastel.com/obfuscation/2017/12/06/presentation-obfuscation.html)
- 2017.11 [arxiv] [[1711.09001] Natural and Effective Obfuscation by Head Inpainting](https://arxiv.org/abs/1711.09001)
- 2017.11 [cobbr] [PSAmsi - Minimizing Obfuscation to Maximize Stealth](https://cobbr.io/PSAmsi-Minimizing-Obfuscation-To-Maximize-Stealth.html)
- 2017.11 [arxiv] [[1711.05284] Obfuscating the Interconnects: Low-Cost and Resilient Full-Chip Layout Camouflaging](https://arxiv.org/abs/1711.05284)
- 2017.11 [360] [MSWord：如何混淆域代码绕过基于Yara规则的DDEAUTO检测](https://www.anquanke.com/post/id/87198/)
- 2017.11 [darkoperator] [测试 Windows Defender Exploit Guard 使用 Attack Surface Reduction（ASR） 规则检测/阻止特定行为的能力. 检测和阻止混淆后的脚本执行。结果显示 ASR 规则并不给力，使用 Invoke-Obfuscation 混淆的脚本成功执行](https://www.darkoperator.com/blog/2017/11/8/windows-defender-exploit-guard-asr-obfuscated-script-rule)
- 2017.11 [pediy] [[翻译]MSWord-用字段代码混淆](https://bbs.pediy.com/thread-222584.htm)
- 2017.11 [sans] [Simple Analysis of an Obfuscated JAR File](https://isc.sans.edu/forums/diary/Simple+Analysis+of+an+Obfuscated+JAR+File/23004/)
- 2017.10 [pluginvulnerabilities] [Base64 Obfuscation Used in WordPress Plugin’s Code That Emails Details of Website to Developer](https://www.pluginvulnerabilities.com/2017/10/30/base64-obfuscation-used-in-wordpress-plugins-code-that-emails-details-of-website-to-developer/)
- 2017.10 [staaldraad] [MSWord - Obfuscation with Field Codes](https://staaldraad.github.io/2017/10/23/msword-field-codes/)
- 2017.10 [arxiv] [[1710.01139] On Secure and Usable Program Obfuscation: A Survey](https://arxiv.org/abs/1710.01139)
- 2017.09 [arxiv] [[1710.00197] Matching Anonymized and Obfuscated Time Series to Users' Profiles](https://arxiv.org/abs/1710.00197)
- 2017.09 [arxiv] [[1709.10412] CAOS: Concurrent-Access Obfuscated Store](https://arxiv.org/abs/1709.10412)
- 2017.09 [pluginvulnerabilities] [WordPress Plugin Directory Allowing Plugins to Obfuscate Addresses of Websites That the Plugin Connect To](https://www.pluginvulnerabilities.com/2017/09/25/wordpress-plugin-directory-allowing-plugins-to-obfuscate-addresses-of-websites-that-the-plugin-connect-to/)
- 2017.09 [antonioparata] [使用 Mealy 元数据混淆字符串](http://antonioparata.blogspot.com/2017/09/using-mealy-automata-for-string.html)
- 2017.08 [f5] [URL Obfuscation—Still a Phisher's Phriend](https://f5.com/labs/articles/threat-intelligence/cyber-security/url-obfuscationstill-a-phishers-phriend)
- 2017.08 [arxiv] [[1708.07150] Threshold-based Obfuscated Keys with Quantifiable Security against Invasive Readout](https://arxiv.org/abs/1708.07150)
- 2017.08 [secist] [代码混淆之道——控制流扁平与不透明谓词理论篇](http://www.secist.com/archives/4219.html)
- 2017.08 [forcepoint] [Part one - security, performance, obfuscation, and compression](https://www.forcepoint.com/blog/security-labs/part-one-security-performance-obfuscation-and-compression)
- 2017.08 [arxiv] [[1708.02629] Protecting Genomic Privacy by a Sequence-Similarity Based Obfuscation Method](https://arxiv.org/abs/1708.02629)
- 2017.07 [pat] [Misconceptions in Client-Side Security: Reverse Engineering Obfuscation & Disguised Endpoints](https://medium.com/p/dddfdafbc60e)
- 2017.07 [freebuf] [FireEye发布调查报告，混淆技术成为了2017年攻击者最喜欢用的技术之一](http://www.freebuf.com/news/139321.html)
- 2017.06 [fireeye] [Obfuscation in the Wild: Targeted Attackers Lead the Way in Evasion Techniques](https://www.fireeye.com/blog/threat-research/2017/06/obfuscation-in-the-wild.html)
- 2017.06 [pentestpartners] [Obfuscating consumer IoT hardware. Is it worth it?](https://www.pentestpartners.com/security-blog/obfuscating-consumer-iot-hardware-is-it-worth-it/)
- 2017.06 [arxiv] [[1706.08003] OS Fingerprinting: New Techniques and a Study of Information Gain and Obfuscation](https://arxiv.org/abs/1706.08003)
- 2017.06 [sans] [Obfuscating without XOR](https://isc.sans.edu/forums/diary/Obfuscating+without+XOR/22544/)
- 2017.06 [cobbr] [ObfuscatedEmpire - Updates and Pull Request!](https://cobbr.io/ObfuscatedEmpire-Updates.html)
- 2017.06 [arxiv] [[1706.06232] Modeling Attack Resilient Reconfigurable Latent Obfuscation Technique for PUF based Lightweight Authentication](https://arxiv.org/abs/1706.06232)
- 2017.06 [arxiv] [[1706.05432] Obfuscation in Bitcoin: Techniques and Politics](https://arxiv.org/abs/1706.05432)
- 2017.06 [quarkslab] [PhD defense of Ninon Eyrolles: Obfuscation with Mixed Boolean-Arithmetic Expressions: Reconstruction, Analysis and Simplification Tools](https://blog.quarkslab.com/phd-defense-of-ninon-eyrolles-obfuscation-with-mixed-boolean-arithmetic-expressions-reconstruction-analysis-and-simplification-tools.html)
- 2017.06 [arxiv] [[1706.02693] A Mean-Field Stackelberg Game Approach for Obfuscation Adoption in Empirical Risk Minimization](https://arxiv.org/abs/1706.02693)
- 2017.06 [4hou] [看我如何使用数据格式混淆来绕过WAF进行攻击?](http://www.4hou.com/technology/5163.html)
- 2017.05 [d0znpp] [Bypassing NGFW/WAFs using data format obfuscations](https://medium.com/p/188351ea9e73)
- 2017.05 [paloaltonetworks] [Practice Makes Perfect: Nemucod Evolves Delivery and Obfuscation Techniques to Harvest Cr](https://unit42.paloaltonetworks.com/unit42-practice-makes-perfect-nemucod-evolves-delivery-obfuscation-techniques-harvest-credentials/)
- 2017.05 [securestate] [Obfuscating Launchers to Limit Detection](https://warroom.securestate.com/obfuscating-launchers-limit-detection/)
- 2017.05 [securestate] [Obfuscating Launchers to Limit Detection](https://warroom.rsmus.com/obfuscating-launchers-limit-detection/)
- 2017.04 [sans] [Another Day, Another Obfuscation Technique](https://isc.sans.edu/forums/diary/Another+Day+Another+Obfuscation+Technique/22354/)
- 2017.04 [NDSSSymposium] [NDSS 2017:  HOP: Hardware makes Obfuscation Practical](https://www.youtube.com/watch?v=yXHrs3qtyuY)
- 2017.04 [NDSSSymposium] [NDSS 2017:  Obfuscation-Resilient Privacy Leak Detection for Mobile Apps Through Differential...](https://www.youtube.com/watch?v=5aNBBeI9HXw)
- 2017.04 [sans] [Analysis of a Maldoc with Multiple Layers of Obfuscation](https://isc.sans.edu/forums/diary/Analysis+of+a+Maldoc+with+Multiple+Layers+of+Obfuscation/22330/)
- 2017.04 [arxiv] [[1704.02307] Assessment of Source Code Obfuscation Techniques](https://arxiv.org/abs/1704.02307)
- 2017.03 [arxiv] [[1703.07427] Intrinsically Reliable and Lightweight Physical Obfuscated Keys](https://arxiv.org/abs/1703.07427)
- 2017.03 [nviso] [Analyzing obfuscated scripts using nothing but a text editor](https://blog.nviso.be/2017/03/07/analyzing-obfuscated-scripts-using-nothing-but-a-text-editor/)
- 2017.03 [sans] [Another example of maldoc string obfuscation, with extra bonus: UAC bypass](https://isc.sans.edu/forums/diary/Another+example+of+maldoc+string+obfuscation+with+extra+bonus+UAC+bypass/22153/)
- 2017.03 [arxiv] [[1703.00475] Design Automation for Obfuscated Circuits with Multiple Viable Functions](https://arxiv.org/abs/1703.00475)
- 2017.02 [endgame] [Lessons from the Trenches: Obfuscation and Pattern Recognition](https://www.endgame.com/blog/technical-blog/lessons-trenches-obfuscation-and-pattern-recognition)
- 2017.02 [secist] [三个混淆过狗一句话分析](http://www.secist.com/archives/2767.html)
- 2017.01 [tetrane] [Unfolding obfuscated code with Reven (part 2)](http://blog.tetrane.com/2017/01/reversing-f4b-challenge-part2.html)
- 2016.12 [arxiv] [[1612.05675] Targeting Infeasibility Questions on Obfuscated Codes](https://arxiv.org/abs/1612.05675)
- 2016.12 [360] [如何分析经过混淆的SWF](https://www.anquanke.com/post/id/85098/)
- 2016.12 [arxiv] [[1612.03345] Obfuscation using Encryption](https://arxiv.org/abs/1612.03345)
- 2016.11 [tetrane] [Unfolding obfuscated code with Reven (part 1, full write-up)](http://blog.tetrane.com/2016/11/reversing-f4b-challenge-part1.html)
- 2016.11 [vkremez] [IDA Pro Tutorial: Unpacking Obfuscated Binary Using IDA Pro Debugger](https://www.vkremez.com/2016/10/ida-pro-tutorial-unpacking-obfuscated.html)
- 2016.10 [tetrane] [Unfolding obfuscated code (part 1)](http://blog.tetrane.com/2016/10/f4b-xor-w4kfu-short-1.html)
- 2016.10 [arxiv] [[1610.06694] ODIN: Obfuscation-based privacy preserving consensus algorithm for Decentralized Information fusion in smart device Networks](https://arxiv.org/abs/1610.06694)
- 2016.10 [jm33] [Using Obfs4proxy to obfuscate your non-TOR proxy / 为Shadowsocks路由器增加Obfs4混淆](https://jm33.me/using-obfs4proxy-to-obfuscate-your-non-tor-proxy-wei-shadowsockslu-you-qi-zeng-jia-obfs4hun-yao.html)
- 2016.10 [rsaconference] [Obfuscation: A User's Guide for Privacy and Protest](https://www.rsaconference.com/blogs/obfuscation-a-users-guide-for-privacy-and-protest)
- 2016.10 [endgame] [Defeating the Latest Advances in Script Obfuscation](https://www.endgame.com/blog/technical-blog/defeating-latest-advances-script-obfuscation)
- 2016.09 [arxiv] [[1609.07612] Obfuscating Keystroke Time Intervals to Avoid Identification and Impersonation](https://arxiv.org/abs/1609.07612)
- 2016.09 [mrpapercut] [Non-Alphanumeric JS obfuscator](https://mrpapercut.com/blog/2016-09-06-non-alphanum-obfuscator)
- 2016.09 [arxiv] [[1609.00408] Defeating Image Obfuscation with Deep Learning](https://arxiv.org/abs/1609.00408)
- 2016.08 [cryptologie] [Whibox part 1: Indistinguishability Obfuscation](http://cryptologie.net/article/362/whibox-part-1-indistinguishability-obfuscation/)
- 2016.08 [arxiv] [[1608.02546] A Stackelberg Game Perspective on the Conflict Between Machine Learning and Data Obfuscation](https://arxiv.org/abs/1608.02546)
- 2016.08 [trustwave] [To Obfuscate, or not to Obfuscate](https://www.trustwave.com/Resources/SpiderLabs-Blog/To-Obfuscate,-or-not-to-Obfuscate/)
- 2016.08 [contextis] [Obfuscation, Encryption & Unicorns… Reversing the string encryption in the Pangu 9.3 jailbreak](https://www.contextis.com/blog/obfuscation-encryption-unicorns-reversing-string-encryption-pangu-93-jailbr)
- 2016.07 [0x00sec] [Packers - Executable Compression and Data Obfuscation](https://0x00sec.org/t/packers-executable-compression-and-data-obfuscation/847/)
- 2016.07 [breakdev] [Obfusion - C++ X86 Code Obfuscation Library](https://breakdev.org/obfusion-c-x86-code-obfuscation-library/)
- 2016.07 [pcsxcetrasupport3] [De-obfuscating Cerber Malspam file](https://pcsxcetrasupport3.wordpress.com/2016/07/04/de-obfuscating-cerber-malspam-file/)
- 2016.07 [p] [NDH2K16 - lol so obfuscated](https://p-te.fr/2016/07/03/nuit-du-hack-2016-lol-so-obfuscated/)
- 2016.06 [securitygossip] [ViewDroid: Towards Obfuscation-Resilient Mobile Application Repackaging Detection](http://securitygossip.com/blog/2016/06/30/2016-06-30/)
- 2016.06 [sjtu] [ViewDroid: Towards Obfuscation-Resilient Mobile Application Repackaging Detection](https://loccs.sjtu.edu.cn/gossip/blog/2016/06/30/2016-06-30/)
- 2016.06 [arxiv] [[1606.06771] A Stackelberg Game Perspective on the Conflict Between Machine Learning and Data Obfuscation](https://arxiv.org/abs/1606.06771)
- 2016.05 [mcafee] [Seeing Through Darkleech Obfuscation: a Quick Hack to Iframes](https://www.mcafee.com/blogs/other-blogs/mcafee-labs/seeing-darkleech-obfuscation-quick-hack-iframes/)
- 2016.05 [mcafee] [Seeing Through Darkleech Obfuscation: a Quick Hack to Iframes](https://securingtomorrow.mcafee.com/mcafee-labs/seeing-darkleech-obfuscation-quick-hack-iframes/)
- 2016.05 [jpcert] [Decoding Obfuscated Strings in Adwind](https://blogs.jpcert.or.jp/en/2016/05/decoding-obfuscated-strings-in-adwind.html)
- 2016.05 [arxiv] [[1605.04044] Network Traffic Obfuscation and Automated Internet Censorship](https://arxiv.org/abs/1605.04044)
- 2016.05 [osandamalith] [IP Obfuscator](https://osandamalith.com/2016/05/02/ip-obfuscator/)
- 2016.04 [360] [漫谈混淆技术----从Citadel混淆壳说起](https://www.anquanke.com/post/id/83849/)
- 2016.04 [freebuf] [漫谈混淆技术：从Citadel混淆壳说起](http://www.freebuf.com/articles/web/103188.html)
- 2016.04 [n0where] [Obfuscated String Solver: Floss](https://n0where.net/obfuscated-string-solver-floss)
- 2016.04 [advancedpersistentjest] [Writeup – Obfuscation (sCTF)](https://advancedpersistentjest.com/2016/04/17/writeup-obfuscation-sctf/)
- 2016.04 [jm33] [使用Obfsproxy (Scramblesuit) 混淆sh4d0ws0cks流量](https://jm33.me/shi-yong-obfsproxy-scramblesuit-hun-yao-sh4d0ws0cksliu-liang.html)
- 2016.04 [layerone] [DeObf 2016: I Wanna Be (De)Obfuscated!](http://www.layerone.org/deobf-2016-i-wanna-be-deobfuscated/)
- 2016.03 [fortinet] [Unseen Dangers—Obfuscation Tools & Cybercrime](https://www.fortinet.com/blog/industry-trends/unseen-dangers-obfuscation-tools-cybercrime.html)
- 2016.03 [arxiv] [[1603.06597] Evaluating the Security of a DNS Query Obfuscation Scheme for Private Web Surfing](https://arxiv.org/abs/1603.06597)
- 2016.02 [buffered] [TLV Traffic Obfuscation](http://buffered.io/posts/tlv-traffic-obfuscation/)
- 2016.02 [arxiv] [[1602.01771] On Quantum Obfuscation](https://arxiv.org/abs/1602.01771)
- 2016.01 [arxiv] [[1601.06371] Your Interests According to Google - A Profile-Centered Analysis for Obfuscation of Online Tracking Profiles](https://arxiv.org/abs/1601.06371)
- 2016.01 [sans] [Obfuscated MIME Files](https://isc.sans.edu/forums/diary/Obfuscated+MIME+Files/20643/)
- 2016.01 [DarrenKitchen] [Mail Obfuscation and Pickup Procrastination](https://www.youtube.com/watch?v=Y8DbwEtTjaE)
- 2016.01 [arxiv] [[1601.00763] Translingual Obfuscation](https://arxiv.org/abs/1601.00763)
- 2016.01 [freebuf] [FLARE脚本系列：自动解码混淆字符串](http://www.freebuf.com/sectool/91910.html)
- 2015.12 [360] [​FLARE脚本系列：自动解码混淆字符串](https://www.anquanke.com/post/id/83205/)
- 2015.12 [pediy] [[原创]记一次混淆算法逆向分析](https://bbs.pediy.com/thread-206635.htm)
- 2015.11 [securitygossip] [LOOP: Logic-Oriented Opaque Predicate Detection in Obfuscated Binary Code](http://securitygossip.com/blog/2015/11/27/2015-11-27/)
- 2015.11 [sjtu] [LOOP: Logic-Oriented Opaque Predicate Detection in Obfuscated Binary Code](https://loccs.sjtu.edu.cn/gossip/blog/2015/11/27/2015-11-27/)
- 2015.11 [benthamsgaze] [Program obfuscation](https://www.benthamsgaze.org/2015/11/24/program-obfuscation/)
- 2015.11 [trustwave] [BOM Obfuscation in Spam](https://www.trustwave.com/Resources/SpiderLabs-Blog/BOM-Obfuscation-in-Spam/)
- 2015.09 [malwarebytes] [Obfuscated URLs, where is that link taking you?](https://blog.malwarebytes.com/cybercrime/2015/09/obfuscated-urls-where-is-that-link-taking-you/)
- 2015.09 [cert] [A funny little obfuscation technique](https://www.cert.pl/en/news/single/10550/)
- 2015.08 [pediy] [[原创]过腾讯的资源混淆,附工具](https://bbs.pediy.com/thread-202965.htm)
- 2015.06 [arxiv] [[1506.03032] N-Version Obfuscation: Impeding Software Tampering Replication with Program Diversity](https://arxiv.org/abs/1506.03032)
- 2015.06 [talosintelligence] [Angler EK: More Obfuscation, Fake Extensions, and Other Nonsense](https://blog.talosintelligence.com/2015/06/angler-ek-more-obfuscation-fake.html)
- 2015.03 [layerone] [The (De)Obfuscated: De-obfuscation contest returns!](http://www.layerone.org/the-deobfuscated-de-obfuscation-contest-returns/)
- 2015.03 [sans] [An Example of Evolving Obfuscation](https://isc.sans.edu/forums/diary/An+Example+of+Evolving+Obfuscation/19403/)
- 2015.02 [websec] [Presentation on Optimization and Obfuscation Techniques for SQL Injections](https://websec.ca/blog/view/Blackhat-2013-SQL-Injections-Optimization-Obfuscation-presentation)
- 2015.01 [arxiv] [[1501.02885] Benchmarking Obfuscators of Functionality](https://arxiv.org/abs/1501.02885)
- 2014.11 [trendmicro] [Obfuscated Flash Files Make Their Mark in Exploit Kits](https://blog.trendmicro.com/trendlabs-security-intelligence/malicious-flash-files-gain-the-upper-hand-with-new-obfuscation-techniques/)
- 2014.09 [lastline] [Rogue Online Pharmacies Use Fake Security Seals and Content Obfuscation to Deceive Humans and Programs](https://www.lastline.com/labsblog/rogue-online-pharmacies-use-fake-security-seals-and-content-obfuscation-to-deceive-humans-and-programs/)
- 2014.09 [pediy] [[原创]多态混淆器 [开源]](https://bbs.pediy.com/thread-191962.htm)
- 2014.06 [mrg] [How deep is the rabbit hole? A tale about exploit kits and layers of obfuscation](https://www.mrg-effitas.com/research/how-deep-is-the-rabbit-hole-a-tale-about-exploit-kits-and-layers-of-obfuscation/)
- 2014.05 [Proteas] [反-反汇编 & 混淆 #1： 苹果没有遵循自己制定的Mach-O规范？](https://blog.csdn.net/Proteas/article/details/27207367)
- 2014.05 [arxiv] [[1405.5410] A Codon Frequency Obfuscation Heuristic for Raw Genomic Data Privacy](https://arxiv.org/abs/1405.5410)
- 2014.05 [trustwave] [Exploit Kit Roundup: Best of Obfuscation Techniques](https://www.trustwave.com/Resources/SpiderLabs-Blog/Exploit-Kit-Roundup--Best-of-Obfuscation-Techniques/)
- 2014.04 [brendangregg] [Compilers: Let Me Obfuscate That For You](http://brendangregg.com/blog/2014-04-27/let-me-obfuscate-that-for-you.html)
- 2014.03 [trendmicro] [Careto and OS X Obfuscation](https://blog.trendmicro.com/trendlabs-security-intelligence/careto-and-os-x-obfuscation/)
- 2014.02 [cryptographyengineering] [Cryptographic obfuscation and ‘unhackable’ software](https://blog.cryptographyengineering.com/2014/02/21/cryptographic-obfuscation-and/)
- 2014.02 [arxiv] [[1402.3426] Privacy Games: Optimal User-Centric Data Obfuscation](https://arxiv.org/abs/1402.3426)
- 2014.01 [arxiv] [[1401.0348] The impossibility of obfuscation with auxiliary input or a universal simulator](https://arxiv.org/abs/1401.0348)
- 2013.11 [palshack] [Hardcore SQL Injections, optimizations and obfuscation](http://palshack.org/hardcore-sql-injections-optimizations-and-obfuscation/)
- 2013.10 [arxiv] [[1311.0044] Thread-Based Obfuscation through Control-Flow Mangling](https://arxiv.org/abs/1311.0044)
- 2013.09 [doar] [Breaking Kryptonite's Obfuscation: A Static Analysis Approach Relying on Symbolic Execution](http://doar-e.github.io/blog/2013/09/16/breaking-kryptonites-obfuscation-with-symbolic-execution/)
- 2013.08 [welivesecurity] [Nymaim - obfuscation chronicles](https://www.welivesecurity.com/2013/08/26/nymaim-obfuscation-chronicles/)
- 2013.08 [doar] [Regular Expressions Obfuscation Under the Microscope](http://doar-e.github.io/blog/2013/08/24/regular-expressions-obfuscation-under-the-microscope/)
- 2013.07 [pediy] [[原创]实时混淆生成的crackme](https://bbs.pediy.com/thread-174591.htm)
- 2013.05 [malwarebytes] [Nowhere to Hide: Three methods of XOR obfuscation](https://blog.malwarebytes.com/threat-analysis/2013/05/nowhere-to-hide-three-methods-of-xor-obfuscation/)
- 2013.01 [mcafee] [IPS Countermeasures Fight Obfuscation, Evasion](https://securingtomorrow.mcafee.com/mcafee-labs/ips-countermeasures-fight-obfuscation-evasion/)
- 2013.01 [talosintelligence] [The 0-day That Wasn't: Dissecting A Highly Obfuscated PDF Attack](https://blog.talosintelligence.com/2013/01/the-0-day-that-wasnt-dissecting-highly.html)
- 2012.12 [arxiv] [[1212.6458] Partial-indistinguishability obfuscation using braids](https://arxiv.org/abs/1212.6458)
- 2012.11 [compass] [ASFWS – Obfuscator, ou comment durcir un code source ou un binaire contre le reverse-engineering](https://blog.compass-security.com/2012/11/asfws-obfuscator-ou-comment-durcir-un-code-source-ou-un-binaire-contre-le-reverse-engineering/)
- 2012.09 [sysforensics] [Obfuscated iframe leads to Blackhole Exploit Kit 2.0](http://sysforensics.org/2012/09/obfuscated-iframe-leads-to-blackhole-exploit-kit-2-0/)
- 2012.09 [toolswatch] [NOVA the Network Obfuscation and Virtualized Anti-Reconnaissance v12.6 available](http://www.toolswatch.org/2012/09/nova-the-network-obfuscation-and-virtualized-anti-reconnaissance-v12-6-available/)
- 2012.05 [arxiv] [[1205.4813] Securing SQLJ Source Codes from Business Logic Disclosure by Data Hiding Obfuscation](https://arxiv.org/abs/1205.4813)
- 2012.02 [reverse] [Obfuscation #2: Playing entrypoint hide & seek game with dyld](https://reverse.put.as/2012/02/07/obfuscation-2-playing-entrypoint-hide-seek-game-with-dyld/)
- 2011.02 [securityinnovation] [How Much Security Does Obfuscation Get You?](https://blog.securityinnovation.com/blog/bid/56448/how-much-security-does-obfuscation-get-you)
- 2010.11 [androidcracking] [string obfuscation](http://androidcracking.blogspot.com/2010/11/string-obfuscation.html)
- 2010.08 [forcepoint] [Phoenix Exploit Kit's Random Access Obfuscation](https://www.forcepoint.com/blog/security-labs/phoenix-exploit-kits-random-access-obfuscation)
- 2010.08 [websec] [Attacking Linksys WRT160N router using the "URL Obfuscation in Frames" bug](https://websec.ca/blog/view/hacking_linksys_wrt160n)
- 2010.08 [sans] [Obfuscated SQL Injection attacks](https://isc.sans.edu/forums/diary/Obfuscated+SQL+Injection+attacks/9397/)
- 2010.04 [arxiv] [[1004.4940] FauxCrypt - A Method of Text Obfuscation](https://arxiv.org/abs/1004.4940)
- 2010.04 [forcepoint] [De-obfuscating the obfuscated binaries with visualization](https://www.forcepoint.com/blog/security-labs/de-obfuscating-obfuscated-binaries-visualization)
- 2009.08 [rapid7] [Binary Obfuscation from the Top Down](https://blog.rapid7.com/2009/08/18/binary-obfuscation-from-the-top-down/)
- 2009.08 [msreverseengineering] [Unpacking Virtualization Obfuscators](http://www.msreverseengineering.com/blog/2014/6/23/unpacking-virtualization-obfuscators)
- 2009.02 [sans] [We want your logs, obfuscated even.](https://isc.sans.edu/forums/diary/We+want+your+logs+obfuscated+even/5857/)
- 2009.02 [gamelinux] [Status Bar Obfuscation / Clickjacking in Firefox](https://gamelinux.wordpress.com/2009/02/06/status-bar-obfuscation-clickjacking-in-firefox/)
- 2008.12 [addxorrol] [Sometimes, diffing can remove obfuscation (albeit rarely)](http://addxorrol.blogspot.com/2008/12/sometimes-diffing-can-remove.html)
- 2008.10 [imperialviolet] [Obfuscated TCP](https://www.imperialviolet.org/2008/10/06/obfuscated-tcp.html)
- 2008.08 [kobyk] [Unexporting a function from a DLL at runtime by name obfuscation](https://kobyk.wordpress.com/2008/08/30/unexporting-a-function-from-a-dll-at-runtime-by-name-obfuscation/)
- 2008.05 [arxiv] [[0805.4648] On White-box Cryptography and Obfuscation](https://arxiv.org/abs/0805.4648)
- 2008.03 [imperialviolet] [OTCP - Obfuscated TCP](https://www.imperialviolet.org/2008/03/11/otcp--obfuscated-tcp.html)
- 2007.05 [sans] [Analyzing an obfuscated ANI exploit](https://isc.sans.edu/forums/diary/Analyzing+an+obfuscated+ANI+exploit/2826/)
- 2007.03 [pediy] [[分享]ACProtect之补区段法(OEP Obfuscation, API redirection)](https://bbs.pediy.com/thread-41511.htm)
- 2007.02 [em386] [Obfuscated ELF Objects](http://em386.blogspot.com/2007/02/obfuscated-elf-objects.html)
- 2007.01 [trendmicro] [Just another obfuscated script… and browser exploits galore!](https://blog.trendmicro.com/trendlabs-security-intelligence/just-another-obfuscated-script-and-browser-exploits-galore21/)
- 2007.01 [slightlyrandombrokenthoughts] [Obfuscating by overloading method and field names](http://slightlyrandombrokenthoughts.blogspot.com/2007/01/obfuscating-by-overloading-method-and.html)
- 2006.09 [trendmicro] [Obfuscation: Creating something new but not really…](https://blog.trendmicro.com/trendlabs-security-intelligence/obfuscation3a-creating-something-new-but-not-really/)
- 2006.05 [sans] [Phishers use urlencoding to obfuscate hostnames](https://isc.sans.edu/forums/diary/Phishers+use+urlencoding+to+obfuscate+hostnames/1342/)
- 2006.01 [pediy] [我对混淆代码的粗浅认识](https://bbs.pediy.com/thread-20648.htm)


# <a id="b3551c683c83f36d15d84d207f2b1c9b"></a>新添加-反混淆


***


## <a id="ac795f859fb0f410e2fbda2ef60f407f"></a>工具


- [**233**星][15d] [Py] [rub-syssec/syntia](https://github.com/rub-syssec/syntia) Syntia:综合模糊代码的语义
- [**212**星][13d] [Py] [eth-sri/debin](https://github.com/eth-sri/debin) Machine Learning to Deobfuscate Binaries
- [**204**星][3m] [Jupyter Notebook] [malrev/abd](https://github.com/malrev/abd) Course materials for Advanced Binary Deobfuscation by NTT Secure Platform Laboratories
- [**154**星][12d] [Py] [cq674350529/deflat](https://github.com/cq674350529/deflat) use angr to deobfuscation
- [**103**星][2y] [C#] [holly-hacker/eazfixer](https://github.com/holly-hacker/eazfixer) A deobfuscation tool for Eazfuscator.
- [**62**星][2y] [Java] [java-deobfuscator/deobfuscator-gui](https://github.com/java-deobfuscator/deobfuscator-gui) deobfuscator的GUI
- [**44**星][1m] [Py] [dissectmalware/batch_deobfuscator](https://github.com/dissectmalware/batch_deobfuscator) Deobfuscate batch scripts obfuscated using string substitution and escape character techniques.
- [**40**星][3y] [C++] [x64dbg/interobfu](https://github.com/x64dbg/interobfu) Intermediate x86 instruction representation for use in obfuscation/deobfuscation.
- [**37**星][21d] [JS] [michenriksen/hackpad](https://github.com/michenriksen/hackpad) A web application hacker's toolbox. Base64 encoding/decoding, URL encoding/decoding, MD5/SHA1/SHA256/HMAC hashing, code deobfuscation, formatting, highlighting and much more.
- [**35**星][19d] [Java] [graxcode/zelixkiller](https://github.com/graxcode/zelixkiller) Deobfuscate ZKM up to version 11
- [**31**星][4y] [Pascal] [pigrecos/codedeobfuscator](https://github.com/pigrecos/codedeobfuscator) Code Deobfuscator
- [**21**星][1m] [Py] [cylance/winapi-deobfuscation](https://github.com/cylance/winapi-deobfuscation) Towards Generic Deobfuscation of Windows API Calls
- [**20**星][2m] [C++] [jacob-baines/jit_obfuscation_poc](https://github.com/jacob-baines/jit_obfuscation_poc) Using GNU lightning to generate xor deobfuscation at runtime
- [**20**星][9m] [Py] [jnraber/virtualdeobfuscator](https://github.com/jnraber/virtualdeobfuscator) Reverse engineering tool for virtualization wrappers
- [**16**星][8m] [C] [gdbinit/unicorn_string_deobfuscator](https://github.com/gdbinit/unicorn_string_deobfuscator) A Unicorn based emulator to deobfuscate Equation Group string XOR obfuscation
- [**16**星][25d] [Kotlin] [heartpattern/mc-remapper](https://github.com/HeartPattern/MC-Remapper) Deobfuscator for Minecraft by mapping json
- [**16**星][25d] [Kotlin] [heartpattern/mc-remapper](https://github.com/heartpattern/mc-remapper) Deobfuscator for Minecraft by mapping json
- [**15**星][24d] [Java] [lxgaming/reconstruct](https://github.com/lxgaming/reconstruct) ProGuard Deobfuscator
- [**11**星][2m] [calware/deobfuscation](https://github.com/calware/deobfuscation) Binary Deobfuscation Series
- [**10**星][4m] [Java] [soxs/osrsupdater](https://github.com/soxs/osrsupdater) A simple (and outdated) Old-School RuneScape decompiler/deobfuscator. Performs field and method analysis which uses ASM and bytecode patterns for identification. Identified fields could be used for creating bot clients or QoL clients. For educational use only.
- [**9**星][3m] [C] [valdikss/sophos-deobfuscation-tool](https://github.com/valdikss/sophos-deobfuscation-tool) Sophos Deobfuscation Tool. Deobfuscates passwords obfuscated with Sophos Obfuscation Tool.
- [**6**星][14d] [C++] [teapotd/xdeobf](https://github.com/teapotd/xdeobf) A deobfuscation plugin for IDA
- [**4**星][12m] [Rust] [xermicus/r2deob](https://github.com/xermicus/r2deob) deobfuscation PoC with r2 + ESIL
- [**4**星][3m] [Py] [randomrhythm/web_log_deobfuscate](https://github.com/randomrhythm/web_log_deobfuscate) Deobfuscate various encodings that can be found in web logs.
- [**4**星][6m] [JS] [skyrising/mc-deobfuscator](https://github.com/skyrising/mc-deobfuscator) Automatic deobfuscator for Minecraft
- [**4**星][8m] [JS] [bobbystacksmash/cmd-deobfuscator](https://github.com/bobbystacksmash/cmd-deobfuscator) A Node.js module for deobfuscating and expanding DOS/BATCH commands.
- [**3**星][1y] [Java] [aperrad/gwtclientlogdeobfuscator](https://github.com/aperrad/gwtclientlogdeobfuscator) GWT Client Stacktrace Deobfuscator
- [**2**星][2y] [Groovy] [nao20010128nao/kliket](https://github.com/nao20010128nao/kliket) A php code deobfuscator (re)written in Groovy
- [**1**星][3y] [Java] [jasjisdo/enigma](https://github.com/jasjisdo/enigma) A deobfuscator tool for JavaSE bytecode
- [**1**星][4m] [Py] [0h2o/py2_deobf_tool](https://github.com/0h2o/py2_deobf_tool) Python2.7 pyc deobfuscator
- [**0**星][2y] [JS] [notathrowaway/deobfuscated-payloads_tiempo-en-colombia-en-vivo](https://github.com/notathrowaway/deobfuscated-payloads_tiempo-en-colombia-en-vivo) Deobfuscated payload scripts of the extension "Tiempo en colombia en vivo". Sorry for the long name.
- [**0**星][5m] [Py] [uintdev/cssed](https://github.com/uintdev/cssed) Cloudflare ScrapeShield Email Deobfuscator
- [**None**星][Py] [dissectmalware/xlmmacrodeobfuscator](https://github.com/dissectmalware/xlmmacrodeobfuscator) Extract and Deobfuscate XLM macros (a.k.a Excel 4.0 Macros)


***


## <a id="6b28f0c3d5bfab275e21b6e943063a17"></a>文章


- 2020.02 [quarkslab] [PhD Defense of Jonathan Salwan: Use of Symbolic Execution for Binary Deobfuscation](https://blog.quarkslab.com/phd-defense-of-jonathan-salwan-use-of-symbolic-execution-for-binary-deobfuscation.html)
- 2019.07 [freebuf] [反混淆神器！CyberChef助你秒解混淆脚本](https://www.freebuf.com/sectool/209290.html)
- 2019.04 [msreverseengineering] [An Abstract Interpretation-Based Deobfuscation Plugin for Ghidra](https://www.msreverseengineering.com/blog/2019/4/17/an-abstract-interpretation-based-deobfuscation-plugin-for-ghidra)
- 2019.02 [arxiv] [[1902.05357] Estimating the Circuit Deobfuscating Runtime based on Graph Deep Learning](https://arxiv.org/abs/1902.05357)
- 2019.01 [pediy] [[原创]c/c++反混淆方法](https://bbs.pediy.com/thread-249210.htm)
- 2019.01 [Swarlemagne] [F'ing around with Binary Ninja, Episode 6: Automating Deobfuscation!](https://www.youtube.com/watch?v=MKB5LkWRuGE)
- 2019.01 [Swarlemagne] [F'ing around with Binary Ninja, Episode 5: Automated Deobfuscation!](https://www.youtube.com/watch?v=SgBaqsvYjKg)
- 2019.01 [aliyun] [Automatic string formatting deobfuscation](https://xz.aliyun.com/t/3906)
- 2019.01 [Swarlemagne] [F'ing Around with Binary Ninja, Episode 4: Emulator, and Deobfuscation!](https://www.youtube.com/watch?v=XSxhfRk7YnA)
- 2019.01 [klee] [Effectiveness of Synthesis in Concolic Deobfuscation](http://www.sciencedirect.com/science/article/pii/S0167404817301475)
- 2018.11 [malwarebytes] [TrickBot主模块使用新的混淆技术](https://blog.malwarebytes.com/threat-analysis/malware-threat-analysis/2018/11/whats-new-trickbot-deobfuscating-elements/)
- 2018.07 [sans] [Windows Batch File Deobfuscation](https://isc.sans.edu/forums/diary/Windows+Batch+File+Deobfuscation/23916/)
- 2018.07 [360] [符号反混淆：从虚拟代码中恢复源码(DIMVA 2018)](https://www.anquanke.com/post/id/151940/)
- 2018.07 [quarkslab] [Symbolic Deobfuscation: From Virtualized Code Back to the Original (DIMVA 2018)](https://blog.quarkslab.com/symbolic-deobfuscation-from-virtualized-code-back-to-the-original-dimva-2018.html)
- 2018.05 [pediy] [[原创]JEB2反混淆神器](https://bbs.pediy.com/thread-227046.htm)
- 2018.05 [hexblog] [Deobfuscating xor’ed strings](http://www.hexblog.com/?p=1198)
- 2018.03 [hasherezade] [Deobfuscating TrickBot's strings with libPeConv](https://www.youtube.com/watch?v=KMcSAlS9zGE)
- 2018.03 [pediy] [[翻译]手把手静态分析FinSpy VM：第三部分第一阶段，反混淆FINSPY VM字节码程序](https://bbs.pediy.com/thread-225554.htm)
- 2018.02 [msreverseengineering] [FinSpy VM Unpacking Tutorial Part 3: Devirtualization. Phase #1: Deobfuscating FinSpy VM Bytecode Programs](http://www.msreverseengineering.com/blog/2018/2/21/wsbjxrs1jjw7qi4trk9t3qy6hr7dye)
- 2018.02 [dustri] [Paper notes: Towards generic deobfuscation of Windows API calls](https://dustri.org/b/paper-notes-towards-generic-deobfuscation-of-windows-api-calls.html)
- 2018.02 [venus] [JStillery：Advanced JS Deobfuscation via Partial Evaluation](https://paper.seebug.org/524/)
- 2018.01 [msreverseengineering] [恶意软件 Finspy VM 脱壳教程 - X86 反混淆](http://www.msreverseengineering.com/blog/2018/1/23/a-walk-through-tutorial-with-code-on-statically-unpacking-the-finspy-vm-part-one-x86-deobfuscation)
- 2017.10 [Cooper] [Hack.lu 2017 SMT Solvers in the IT Security - deobfuscating binary code with logic by Thaís Hamasaki](https://www.youtube.com/watch?v=cyr_4_rN4pY)
- 2017.10 [0x00sec] [Deobfuscating js code](https://0x00sec.org/t/deobfuscating-js-code/3858/)
- 2017.07 [] [Deobfuscating PjOrion using bytecode simplifier](https://0xec.blogspot.com/2017/07/deobfuscating-pjorion-using-bytecode.html)
- 2017.03 [pediy] [[翻译]AutoIt脚本反混淆](https://bbs.pediy.com/thread-216429.htm)
- 2017.03 [dist67] [Maldoc Deobfuscation: Plugin sub-str](https://www.youtube.com/watch?v=tnPWKHiHpBo)
- 2017.03 [dist67] [Maldoc Deobfuscation: Character Removal](https://www.youtube.com/watch?v=nN37Uy46AWU)
- 2016.07 [hackerlists] [13 Awesome Deobfuscation Tools For Reverse Engineers](https://hackerlists.com/deobfuscation-tools/)
- 2016.05 [] [PjOrion Deobfuscator Open Sourced](https://0xec.blogspot.com/2016/05/pjorion-deobfuscator-open-sourced.html)
- 2016.04 [sjtu] [Deobfuscation Reverse Engineering Obfuscated Code](https://loccs.sjtu.edu.cn/gossip/blog/2016/04/27/2016-04-27/)
- 2016.03 [360] [MIME类型文件反混淆工具](https://www.anquanke.com/post/id/83560/)
- 2015.10 [mindedsecurity] [Advanced JS Deobfuscation Via AST and Partial Evaluation (Google Talk WrapUp)](http://blog.mindedsecurity.com/2015/10/advanced-js-deobfuscation-via-ast-and.html)
- 2015.10 [ixiacom] [Angler Exploit Kit Deobfuscation and Analysis](https://www.ixiacom.com/company/blog/angler-exploit-kit-deobfuscation-and-analysis)
- 2015.06 [msreverseengineering] [Transparent Deobfuscation with IDA Processor Module Extensions](http://www.msreverseengineering.com/blog/2015/6/29/transparent-deobfuscation-with-ida-processor-module-extensions)
- 2015.05 [securitygossip] [Deobfuscation of Virtualization-Obfuscated Software: A Semantics-Based Approach](http://securitygossip.com/blog/2015/05/14/2015-05-14/)
- 2015.05 [sjtu] [Deobfuscation of Virtualization-Obfuscated Software: A Semantics-Based Approach](https://loccs.sjtu.edu.cn/gossip/blog/2015/05/14/2015-05-14/)
- 2014.12 [ZeroNights] [Dmitry Schelkunov, Vasily Bukasov - «Deobfuscation and beyond»](https://www.youtube.com/watch?v=1ODkJ4zF0YU)
- 2014.06 [nvisium] [Deobfuscate Client Side Cookies](https://nvisium.com/blog/2014/06/06/deobfuscate-client-side-cookies/)
- 2013.04 [malforsec] [Blackhole Exploit Kit - deobfuscating the CVE-2010-0188 PDF](http://malforsec.blogspot.com/2013/04/blckhole-exploit-kit-deobfuscating-cve.html)
- 2012.11 [quequero] [Deobfuscating generic BlackHole 2 with JsADO](https://quequero.org/2012/11/deobfuscating-generic-blackhole-2-with-jsado/)
- 2011.07 [msreverseengineering] [Control Flow Deobfuscation via Abstract Interpretation](http://www.msreverseengineering.com/blog/2014/6/23/control-flow-deobfuscation-via-abstract-interpretation)
- 2011.02 [sogeti] [Training at CanSecWest 2011: Advanced binary deobfuscation](http://esec-lab.sogeti.com/posts/2011/02/03/training-at-cansecwest-2011-advanced-binary-deobfuscation.html)


# 贡献
内容为系统自动导出, 有任何问题请提issue
