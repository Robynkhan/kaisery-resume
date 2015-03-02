# Resume

## Personal
* 岳洋
* Male
* 1991 Feb 15
* Mobile +86 138 2106 7407
* Email yueyang.fanqiang@gmail.com
* QQ 995137302

## Education
### Taijin University of Science & Technology
* International College
* Bachelor of CSIE
* The First Prize Scholarship at 1st/2nd year
* 2009 ~ 2013

## Language Abilities
* English: CET6
* Japanese: N1

## Experience
### ANHUI WANTONG TECHNOLOGY Co.,Ltd. Research Center, Taijin
#### ANHUI Expressway Toll Collection System, 2012 Nov ~ 2014 Jan
* This system was written in C#, and I was assigned to maintain the Hardware Abstraction Layer(abbr. for HAL below) and add new features according to new demand.
* WinForm Desktop Application, IDE was Visual Studio.
* Most hardware connected to computer with serial port or Ethernet, So I developed good skills at serial port communication, TCP/IP protocols and calling C/C++ DLLs(P/Invoke).
* Due to IC card reader, I was familiar with card operation and Chinese Financial IC Card Standard.
* In this period of work, I have learned developing enterprise software using C#, Version Control with SVN and team collaboration through JIRA.

#### ANHUI Expressway Toll Collection System Flat Version, 2014 Jan ~ now
* This project was a newer and larger version of previous project which focused on entire road system intercommunication(pure JAVA implemented) and cross platform(Windows/Linux).
* Using Hudson CI for rapid iteration and Findbugs for code quality.
* I was committed to design and implement the entire HAL, Windows/Linux platform compatibility and data transition between new and old system。
* The whole device layer implemented with multi-thread and asynchronous call. Every kind of device has a execution thread，and there was a status thread monitoring all execution threads, releasing resources and handling exception if necessary, guaranteeing devices to response fast and be isolated from other components. As a result of alpha test, devices were as fast as when they ran in C#.
* Because we need to display video, I used a JAVA FFmpeg wrapper called Xuggle.
* Writing most analog device applications, using AWT, for QA auto-testing project without production environment.
* Writing cross platform deployment scheme, including multi-system switch, booting script, device driver installation, etc...
* At the alpha test period, I wrote a LINQ to SQL new/old system data transfer app, because old system running on Windows Server using SQL Server , to acquire data consistency. 
* Troubleshooting some technical issues, e.g., analysing jvm heapdump to find out memory leak; using jmc, jvisualvm to monitor jvm status.

## Other skills
* Familiar with rpm-based Linux like Fedora, can write some bash script
* Understanding Groovy
* Can Write some C/C++ code
* Have written a small game using Websocket, WebGL
* Can read Intel x86, x64 and ARM assembly language
* Graduation project included a small Android client app
* Learning Rust
* Used to solve technical problem through Google
* Focused technical site: Hacker News, InfoQ, TechCrunch, Engadget, phoronix, GitHub
* Ability surf the Internet using proxy
