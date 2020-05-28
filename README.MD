# Handheld PC development resources

Disclaimer: this document is very much under construction!

This is a curated list of Handheld PC development resources. This list is created by [HPC:Factor](https://www.hpcfactor.com), a community dedicated to keeping the Handheld PC legacy alive.

## Various tools

* [ExecutabilityCheck](https://www.hpcfactor.com/downloads/details.asp?r={40A26F4C-E4AC-41C9-81A1-1D81B4C41A0E}) - Executability Check allows you to reassign imports and operating system dependencies required to run Pocket PC applications on the Handheld PC.
* [ExecutabilityCheck How-To](https://www.hpcfactor.com/support/cesd/s/0128.asp) - This article discusses the purpose and use of ExecutabilityCheck on MIPS & ARM based Handheld PCs.
* [UAEDT](https://www.hpcfactor.com/scl/453/Harald-Ren_Flasch/UAEDT/version_3.3) - Unrecoverable Application Error Debugging Tool (CE2.11+)
* [cetoys](https://sourceforge.net/projects/cetoys/) - Collection of tools for accessing/manipulating a Windows CE device using the remote api (rapi)
* [OpenWinCE Project](https://sourceforge.net/projects/openwince/files/) - Collection of (outdated) devtools, header files, etc

## C++

* [Setting up a Windows CE 2.00, H/PC Pro and HPC2000 Development Environment in a Virtual Machine](https://www.hpcfactor.com/support/cesd/d/0009.asp)

### C++ compilers and IDEs
* [Microsoft Visual C++ For Windows CE Version 1.0](https://archive.org/details/msvcceu.100) (Windows CE 1.0)
embedded Visual Tools
* [CEGCC](https://sourceforge.net/projects/cegcc/) - GCC for Windows CE development
* [GNUWINCE](https://www.hpcfactor.com/downloads/details.asp?r={9D534150-2CDD-42A4-8AAE-1B1FBCEB64A5}) - Collection of tools supporting C, C++, and Java programming for Windows CE

### C++ projects
* [J720Video Ez Hack](https://github.com/battlecoder/ancient_hpc_stuff/tree/master/J720Video_ez_hack) - GAPI implementation for HP Jornada 720 HandheldPC
* [WinWatch](https://github.com/battlecoder/ancient_hpc_stuff/tree/master/WinWatch) - Tool that helps with running PPC apps on HPCs
* [MouSer](https://github.com/battlecoder/ancient_hpc_stuff/tree/master/mouser) - Serial mouse driver
* [OKey](https://github.com/battlecoder/ancient_hpc_stuff/tree/master/okey) - Keyboard remapping tool
* [CeAtaDrv](https://sourceforge.net/projects/ceatadrv/) - An ATA/IDE driver for Windows CE
* [Ultra Light FTP Client](https://sourceforge.net/projects/ultralightftpc/files/version%201.0/)
* [Windows CE Library extentions](https://sourceforge.net/projects/wcelibcex/) - Collection of functions to help with porting software
* [Windows CE VNC Server](https://sourceforge.net/projects/wincevncsvr/files/wincevncsvr/cevncsvr-0.1/)

### C++ Books

* 📕 [Sams Windows CE Programming in 24 hours](https://books.google.co.jp/books?id=hzzkPgAACAAJ)
* 📕 [Windows CE 3.0 Application Programming](https://books.google.com/books?id=AF5Lr5HA5UEC)

## .net

Description of how .net development works.

* [.net Compact framework for Windows CE 2.0/2.01](https://www.hpcfactor.com/scl/1040/dstefanov/Microsoft_.NET_Compact_Framework_1.0_SP3_for_Windows_CE_2.00/2.01) - Port of the .net CF to Windows CE 2.0/2.01 by dstefanov
* [.net Compact framework for Windows CE 2.11](https://www.hpcfactor.com/scl/1041/dstefanov/Microsoft_.NET_Compact_Framework_1.0_SP3_for_Windows_CE_2.11) - Port of the .net CF to Windows CE 2.11 by dstefanov

### .net Books
* 📕 [.NET Compact Framework Pocket Guide](https://www.amazon.com/s/ref=as_li_ss_tl?url=search-alias=aps&field-keywords=9780596007577&rh=i:aps,k:9780596007577&tag=hpcfactor00-20) (ISBN 9780596007577) 
* 📕 [Microsoft .NET Compact Framework Kick Start](https://www.amazon.com/s/ref=as_li_ss_tl?url=search-alias=aps&field-keywords=9780672325700&rh=i:aps,k:9780672325700&tag=hpcfactor00-20) (ISBN 9780672325700) 
* 📕 [Microsoft .NET Compact Framework (Core Reference)](https://www.amazon.com/s/ref=as_li_ss_tl?url=search-alias=aps&field-keywords=9780735617254&rh=i:aps,k:9780735617254&tag=hpcfactor00-20) (ISBN 9780735617254) 
* 📕 [.NET Compact Framework](https://www.amazon.com/s/ref=as_li_ss_tl?url=search-alias=aps&field-keywords=9781861007001&rh=i:aps,k:9781861007001&tag=hpcfactor00-20) (ISBN 9781861007001) 

### .net projects
* [TicTacToe](https://github.com/HPC-Factor/TicTacToe)

## Visual Basic

TODO

## Java

There are numerous Java runtimes for Windows CE. Sun created PortableJava, a somewhat limited runtime which was compatible with Java SE 1.2. Other companies created JREs which won;t be covered here since they were mostly commercial and lack documentation.
Another notable product was Microsoft Visual J++, which was part of the embedded Visual Toolkit until support was dropped in embedded Visual Tools 6.0, meaning it was not possible to use J++ for creating Windows CE 3.0 apps, at least not for ARM processors.

* [Microsoft Java VM for Windows CE](https://www.hpcfactor.com/scl/1044/Microsoft_Corporation/Microsoft_Virtual_Machine_for_Java_MSVM/version_1.0.0.0)

### PersonalJava

* [Personal Java runtime](https://www.hpcfactor.com/scl/842/Sun_Microsystems/Personal_JAVA_Virtual_Machine/version_1.0) 
* [Setting up Eclipse for PersonalJava development](http://www.ohnitsch.net/2014/05/03/personaljava-tutorial/)

### SuperWaba
[SuperWABA](https://en.wikipedia.org/wiki/SuperWaba) is a java-like VM developed for low-power devices
* [SuperWaba sources & binaries](https://sourceforge.net/projects/superwaba/files/VM/Release%204.50a/)
* [WabaSoft website](http://web.archive.org/web/20070205081050/http://www.wabasoft.com/howto.shtml)

### Java Projects

* [MindTerm](https://www.hpcfactor.com/scl/1072/Appgate/MindTerm_SSH_Client/version_2.4.2) - A Java 1.1 SSH client with sources and libraries that can be used in other applications. SSH1 and SSH2 compatible.

### Ewe
* [Ewe](https://www.hpcfactor.com/scl/7/Eve_Soft/Ewe_Virtual_Machine/version_1.49) - A programming system which you can use Java to write applications.

## Python
* [PythonCE](http://pythonce.sourceforge.net/) - Python port for Windows CE ([mirror](https://www.hpcfactor.com/scl/1073/PythonCE/Python/version_2.3.4))


## Books

* 📕 [Inside Microsoft Windows CE](https://books.google.nl/books/about/Inside_Microsoft_Windows_CE.html?id=Rsu7AAAACAAJ&redir_esc=y) - A book discussing history and technical decisions of Windows CE 1.0-2.11
