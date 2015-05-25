# Resume

## Personal
* 岳洋
* Male
* Birthday: 1991 Feb 15
* Location: living in `Tianjin`, home's in `HuBei`
* Mobile: +86 138 2106 7407
* Email: yueyang.fanqiang@gmail.com 995137302@qq.com
* QQ: 995137302
* GitHub: https://github.com/KaiserY

## Education
### Taijin University of Science & Technology
* International College
* Bachelor of CSIE
* The First Prize Scholarship at 1st/2nd year
* 2009 ~ 2013

## Language Abilities
* English: `CET6`
* Japanese: `N1`

## Summary

* Quick Learner, Good at solving problems though `Baidu`/`Google`
* Mostly used languages: `C#` `Java`
* Languages I know: `C/C++` `VB` `Javascript` `PHP` `Assembly`
* Languages I was learning: `Rust` `Scala`(functional programming)
* Familiar with `Fedora`, can write some `Bash` scripts
* Mostly visited website: `Hacker News` `InfoQ` `TechCrunch` `Engadget` `phoronix` `GitHub` `V2EX` `36kr`
* Ability to surf the Internet with proxy

## Experience
### ANHUI WANTONG TECHNOLOGY Co.,Ltd. Research Center, `Taijin`, `2012 Nov` ~ `2015 Apr`
#### ANHUI Expressway Toll Collection System, `2012 Nov` ~ `2014 Jan`

* This system was written in `C#`(`.NET 4.0`), and I was assigned to maintain the Hardware Abstraction Layer(abbr. for HAL below) and add new features according to new demand.
* WinForm Desktop Application, IDE was `Visual Studio`, database was `SQL Server`.
* Most hardware connected to computer with serial port or Ethernet, So I developed good skills at serial port communication, `TCP/IP` protocols and calling `C/C++` DLLs(`P/Invoke`).
* Due to IC card reader, I was familiar with card operation and Chinese Financial IC Card Standard.

##### Conclusion: In this period of work, I have learned developing enterprise software using `C#`, Version Control with `SVN` and team collaboration through `JIRA`.

#### ANHUI Expressway Toll Collection System Flat Version, `2014 Jan` ~ `2015 Apr`

* This project was a newer and larger version of previous project which focused on entire road system intercommunication(pure `Java` implemented) and cross platform(`Windows`/`Linux`).
* SWT desktop application, IDE was `Eclipse`, package control was `Maven`, workflow was `Activiti` and database was `H2`.
* Using `Hudson` CI for rapid iteration and `Findbugs` for code quality.
* Participated in the whole Toll project's design and coding, as a core programmer. I was committed to design and implement the entire HAL, ``Windows`/`Linux` platform compatibility and data transition between new and old system.
* The whole device layer implemented with multi-thread and asynchronous call. Each kind of device has a execution thread，and there was one status thread monitoring all execution threads, releasing resources and handling exception if necessary, guaranteeing devices to response fast and be isolated from other components. As a result of trail run, devices operated as fast as when they did in `C#`.
* Because we need to display video, I used a `Java` `FFmpeg` wrapper called `Xuggle`.
* Written most device simulation applications, using AWT, for QA auto-testing project without production environment.
* Written cross platform deployment scheme, including multi-system switch, booting script, device driver installation, etc...
* At the trail run period, I wrote a `LINQ to SQL` new/old system data transfer app, because old system running on `Windows Server` using `SQL Server` , to acquire data consistency. 
* Troubleshooting some technical issues, e.g., analysing jvm heapdump to find out memory leak; using `jmc`, `jvisualvm` to monitor jvm status, modifying device driver code to improve JNA call.

##### Conclusion: This period gave me a complete experience of a `Java` project, from design to trail run, I was part of it. But due to lots of business trip(130+ days a year) and overtime working climate, sadly, I left this company.
