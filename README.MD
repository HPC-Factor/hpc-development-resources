# Handheld PC development resources

Disclaimer: this document is very much under construction!

This is a curated list of Handheld PC development resources. This list is created by [HPC:Factor](https://www.hpcfactor.com), a community dedicated to keeping the Handheld PC legacy alive.

## Various tools

* [ExecutabilityCheck](https://www.hpcfactor.com/downloads/details.asp?r={40A26F4C-E4AC-41C9-81A1-1D81B4C41A0E}) - Executability Check allows you to reassign imports and operating system dependencies required to run Pocket PC applications on the Handheld PC.
* [ExecutabilityCheck How-To](https://www.hpcfactor.com/support/cesd/s/0128.asp) - This article discusses the purpose and use of ExecutabilityCheck on MIPS & ARM based Handheld PCs.
* [UAEDT](https://www.hpcfactor.com/scl/453/Harald-Ren_Flasch/UAEDT/version_3.3) - Unrecoverable Application Error Debugging Tool (CE2.11+)
* [cetoys](https://sourceforge.net/projects/cetoys/) - Collection of tools for accessing/manipulating a Windows CE device using the remote api (rapi)
* [OpenWinCE Project](https://sourceforge.net/projects/openwince/files/) - Collection of (outdated) devtools, header files, etc

## C/C++

* [Setting up a Windows CE 2.00, H/PC Pro and HPC2000 Development Environment in a Virtual Machine](https://www.hpcfactor.com/support/cesd/d/0009.asp)
* [Windows CE Development FAQ](http://web.archive.org/web/20010616145539/http://www.cegadgets.com/wincedevfaq.htm)
* [Windows CE 3.0 MSDN Technical Articles](https://web.archive.org/web/20040614224612if_/http://msdn.microsoft.com/embedded/prevver/ce3/article/default.aspx)

### C/C++ compilers and IDEs
* [Microsoft Visual C++ For Windows CE Version 1.0](https://archive.org/details/msvcceu.100) (Windows CE 1.0)
embedded Visual Tools
* [CEGCC](https://sourceforge.net/projects/cegcc/) - GCC for Windows CE development (deprecated, use updated version below)
* [CEGCC 9.3](https://github.com/MaxKellermann/cegcc-build) - Updated CEGCC build with build script
* PGCC - GCC port that runs on ARM CE3.0
* [GNUWINCE](https://www.hpcfactor.com/downloads/details.asp?r={9D534150-2CDD-42A4-8AAE-1B1FBCEB64A5}) - Collection of tools supporting C, C++, and Java programming for Windows CE

### C/C++ projects and sample code
* [Sample code from the Windows CE Developer's Kit book set](https://github.com/HPC-Factor/windows-ce-developers-kit-code-samples) - Code samples for Windows CE 2.11
* [J720Video Ez Hack](https://github.com/battlecoder/ancient_hpc_stuff/tree/master/J720Video_ez_hack) - GAPI implementation for HP Jornada 720 HandheldPC
* [WinWatch](https://github.com/battlecoder/ancient_hpc_stuff/tree/master/WinWatch) - Tool that helps with running PPC apps on HPCs
* [MouSer](https://github.com/battlecoder/ancient_hpc_stuff/tree/master/mouser) - Serial mouse driver
* [OKey](https://github.com/battlecoder/ancient_hpc_stuff/tree/master/okey) - Keyboard remapping tool
* [CeAtaDrv](https://sourceforge.net/projects/ceatadrv/) - An ATA/IDE driver for Windows CE
* [Ultra Light FTP Client](https://sourceforge.net/projects/ultralightftpc/files/version%201.0/)
* [Windows CE Library extentions](https://sourceforge.net/projects/wcelibcex/) - Collection of functions to help with porting software
* [Windows CE VNC Server](https://sourceforge.net/projects/wincevncsvr/files/wincevncsvr/cevncsvr-0.1/)
* [Driver for various USB-RS232 adapters](https://github.com/HPC-Factor/232usb-windowsce)
* [SynCE](https://github.com/HPC-Factor/synce)
* [CEuroPad (CE1.0)](https://bitbucket.org/PeCeT_full/ceuropad/src/main/)

### C++ Books

* 📕 [Sams Windows CE Programming in 24 hours](https://archive.org/details/samsteachyoursel00nott)
* 📕 [Windows CE 3.0 Application Programming](https://archive.org/details/bitsavers_microsoftw0ApplicationProgramming2001_37941879)
* 📕 [Windows CE Application Programming](https://archive.org/details/windowsceprogram0000bake)
* 📕 [Windows CE Developer's Kit](https://www.google.com/books/edition/Microsoft_Windows_CE_Developer_s_Kit/m8taAQAACAAJ?hl=en)
  * 📕 [Windows CE User Interface Services Guide](https://archive.org/details/bitsavers_microsoftwndowsCEUserInterfaceServicesGuide1999_11958099)
  * 📕 [Windows CE Communications Guide](https://archive.org/details/bitsavers_microsoftwndowsCECommunicationsGuide1999_10487503)
  * 📕 [Windows CE Device Driver Kit](https://archive.org/details/bitsavers_microsoftwndowsCEDeviceDriverKit1999_7069688)
  * 📕 [Windows CE Programmers Guide](https://archive.org/details/bitsavers_microsoftwndowsCEProgrammersGuide1999_12054297)
* 📕 [Microsoft Windows CE Programmer's Guide](https://archive.org/details/bitsavers_microsoftwndowsCEProgrammersGuide1998_37282992)
* 📕 [The Windows CE Technology Tutorial: Windows Powered Solutions for the Developer](https://www.amazon.com/gp/product/0201616424/?creativeASIN=0201616424&tag=hpcfactor00-20)
* 📕 [Programming Microsoft Windows CE](https://archive.org/details/bitsavers_microsoftwammingMicrosoftWindowsCE1998_198442712)
* 📕 [Windows CE From the Ground Up](https://archive.org/details/windowscefromgro00jean)
* 📕 [Making Win32 Applications Mobile: Porting to Windows CE](https://archive.org/details/makingwin32appli00nico)

## .net

* [.net Compact framework for Windows CE 2.0/2.01](https://www.hpcfactor.com/scl/1040/dstefanov/Microsoft_.NET_Compact_Framework_1.0_SP3_for_Windows_CE_2.00/2.01) - Port of the .net CF to Windows CE 2.0/2.01 by dstefanov
* [.net Compact framework for Windows CE 2.11](https://www.hpcfactor.com/scl/1041/dstefanov/Microsoft_.NET_Compact_Framework_1.0_SP3_for_Windows_CE_2.11) - Port of the .net CF to Windows CE 2.11 by dstefanov

### .net Books
* 📕 [.NET Compact Framework Pocket Guide](https://www.amazon.com/s/ref=as_li_ss_tl?url=search-alias=aps&field-keywords=9780596007577&rh=i:aps,k:9780596007577&tag=hpcfactor00-20) (ISBN 9780596007577) 
* 📕 [Microsoft .NET Compact Framework Kick Start](https://www.amazon.com/s/ref=as_li_ss_tl?url=search-alias=aps&field-keywords=9780672325700&rh=i:aps,k:9780672325700&tag=hpcfactor00-20) (ISBN 9780672325700) 
* 📕 [Microsoft .NET Compact Framework (Core Reference)](https://www.amazon.com/s/ref=as_li_ss_tl?url=search-alias=aps&field-keywords=9780735617254&rh=i:aps,k:9780735617254&tag=hpcfactor00-20) (ISBN 9780735617254) 
* 📕 [.NET Compact Framework](https://www.amazon.com/s/ref=as_li_ss_tl?url=search-alias=aps&field-keywords=9781861007001&rh=i:aps,k:9781861007001&tag=hpcfactor00-20) (ISBN 9781861007001) 
* 📕 [Programming Microsoft Windows CE .NET](https://archive.org/details/bitsavers_microsoftwingProgrammingMicrosoftWindowsCE.NET3ed2_112784267) 

### .net projects
* [TicTacToe](https://github.com/HPC-Factor/TicTacToe)

## Visual Basic

TODO

## Java

There are numerous Java runtimes for Windows CE. Sun created PortableJava, a somewhat limited runtime which was compatible with Java SE 1.2. Other companies also created JREs, but since they're commercial products that need a paid license, these won't be covered here.
Another notable product was Microsoft Visual J++, which was part of the embedded Visual Toolkit until support was dropped in embedded Visual Tools 6.0, meaning it was not possible to use J++ for creating Windows CE 3.0 apps, at least not for ARM processors.

* [Microsoft Java VM for Windows CE](https://www.hpcfactor.com/scl/1044/Microsoft_Corporation/Microsoft_Virtual_Machine_for_Java_MSVM/version_1.0.0.0)

### PersonalJava

* [Personal Java runtime](https://www.hpcfactor.com/scl/842/Sun_Microsystems/Personal_JAVA_Virtual_Machine/version_1.0) 
* [Setting up Eclipse for PersonalJava development](http://www.ohnitsch.net/2014/05/03/personaljava-tutorial/)

### SuperWaba
[SuperWABA](https://en.wikipedia.org/wiki/SuperWaba) is a java-like VM developed for low-power devices
* [SuperWaba sources & binaries](https://sourceforge.net/projects/superwaba/files/VM/Release%204.50a/)
* [WabaSoft website](http://web.archive.org/web/20070205081050/http://www.wabasoft.com/howto.shtml)

### Ewe
* [Ewe](https://www.hpcfactor.com/scl/7/Eve_Soft/Ewe_Virtual_Machine/version_1.49) - A Java-like VM.

### Java Projects

* [MindTerm](https://www.hpcfactor.com/scl/1072/Appgate/MindTerm_SSH_Client/version_2.4.2) - A Java 1.1 SSH client with sources and libraries that can be used in other applications. SSH1 and SSH2 compatible.

## Python
* [PythonCE](http://pythonce.sourceforge.net/) - Python port for Windows CE ([mirror](https://www.hpcfactor.com/scl/1073/PythonCE/Python/version_2.3.4))

## Books

* 📕 [Inside Microsoft Windows CE](https://archive.org/details/bitsavers_microsoftweMicrosoftWindowsCE1998_36633028) - A book discussing history and technical decisions of Windows CE 1.0-2.11
