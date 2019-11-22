---
layout: post
title:  "Story behind the development of UNIX operating system"
author: Swapnil
categories: [ Technology, History]
image: assets/images/Story Behind.PNG
tags: [sticky]
---

>This article relates the story behind the development of the UNIX operating system — how it became the world’s most popular OS, the visionaries and organizations behind its success, and how it is related to the open source world.

All of us know that UNIX is the world’s first operating system and was developed at Bell Labs. Till date, it is the most powerful, versatile and flexible server operating system in the computing world. 

#### The development of UNIX

In 1960, the AT&T Bell Laboratories, the Massachusetts Institute of Technology and General Electric started developing a time-sharing operating system called MULTICS (Multiplexed Information and Computing Service) for mainframe computers. The project was ambitious, and development went on till early 1967. As it became very complex at this stage, the management at GE was dissatisfied with this system and decided to withdraw support to the project in the later part of 1967. In 1970, GE sold its computer business to Honeywell.

Dennis Ritchie and Ken Thompson were the programmers at the Bell Labs computing and research department who worked on project MULTICS from start to end. Thompson found an old PDP-7 machine, and developed his own application programs and operating system from scratch, aided by Ritchie and others. This operating system was renamed UNIX.

In November 1971, the first version of UNIX was released along with a book called ‘The UNIX Programmers Manual’. This was the systematic development approach at that time – a product would be released with proper documentation so that researchers could read the manual and look at the OS details.

The following year, a new version of UNIX and a high-level programming language, referred to as B, were both released at the same time. Researchers and users of UNIX were able to write their own programs using this language, and no more assembly language instructions were required. B was the first high-level programming language, and was easy to understand. Later, B was rewritten and renamed as the C programming language by Dennis Ritchie. The C language is still used to write system level programs and time critical applications. It is easy to understand, which is why all universities consider C as the primary programming language for students

#### How UNIX became the world’s most popular OS

In November 1973, Ken Thompson and Dennis Ritchie formally presented the UNIX operating system to the outside world for the first time at a conference called ‘The Symposium on Operating Systems Principles at Purdue University, USA. A number of students, researchers, professors and representatives from private organizations were present at the event.

>There was also one special person present that day, who changed the direction of UNIX development — Prof. Bob Fabry from the University of California, Berkeley, was responsible for taking UNIX to Berkeley.
After the conference, UNIX become public and the buzzword for computing power. Newspapers and magazines featured stories about this new computing system. UNIX was made available to the government, the military and to universities on a licensed basis.

Prof. Bob Fabry obtained a copy of UNIX for US$ 99 in order to cut costs when setting up the campus computing resources for research at the university. At that time, a UNIX licence also came with the entire source code, and researchers could modify and extend it. Graduate student Bill Joy, along with researchers and hackers from Berkeley, started working on making changes to the original UNIX.

The word had spread, and the Berkeley-modified version of UNIX became more and more popular amongst research scientists, educational institutes and universities.
In early 1977, Joy released Berkeley UNIX under the name BSD (Berkeley Software Distribution), while AT&T continued developing UNIX under the names ‘System III’ and later ‘System V’. Till 1980, AT&T Bell Labs developed multiple versions of UNIX for internal use with different hardware compatibility.
At that time, there were two UNIX development tracks running in parallel — one at AT&T Bell Labs and another by the academic community, led by the Computer Systems Research Group (CSRG) at the University of California, Berkeley.

In the late 1980s through the early 1990s, the wars between these two major strains continued to rage. After many years, each variant adopted many of the key features of the other. Commercially, System V won the standards’ battle (getting most of its interfaces into the formal standards), and most hardware vendors switched to AT&T’s System V.

In the 1980s, many companies started building their own OSs, with UNIX as a base. They would obtain a UNIX copy either from AT&T Bell Labs or from Berkeley Software Distribution, and adapt it for their own hardware. In this way, many popular UNIX based OSs such as FreeBSD, NetBSD, Sun Solaris, Zenix, IBM-AIX and HP-UX came into existence.

In 1982, Sun Microsystems developed a UNIX operating system called SunOS for its workstations and server computing systems. It was based on the Berkeley Software Distribution UNIX, from version 1 to version 5.0. Later versions were based on AT&T Bell Labs’ UNIX System V Release 4 and were marketed under the brand name Solaris, as proprietary operating system software. In June 2005, Sun Microsystems released most of the code base under the CDDL (Common Development and Distribution License) and founded the OpenSolaris open source project. Sun wanted to build a developer and user community around the software. But after the acquisition of Sun Microsystems by Oracle in January 2010, the latter decided to discontinue the OpenSolaris distribution and development model.

In 1984, HP came up with HP-UX, which was based on AT&T Bell Labs’ UNIX version System V.

In 1986, technology giant IBM obtained UNIX version System V with 4.3BSD-compatible extensions from AT&T Bell Laboratories. The company made it compatible with IBM architecture-based hardware systems and started selling it under the brand IBM-AIX (Advanced Interactive eXecutive). It became the most popular UNIX commercial distribution in the 90s and even later. Originally, AIX was released for the IBM RT PC RISC workstation. It now supports a wide variety of hardware platforms, including the IBM RS/6000 series as well as POWER and PowerPC-based systems, IBM System i, System/370 mainframes, PS/2 personal computers and the Apple Network Server.

The final UNIX release from Berkeley was in 1995 — the 4.4BSD-Lite Release 2, after which the Computer Systems Research Group was dissolved, and the development of BSD at Berkeley ceased. Since then, several variants based directly or indirectly on 4.4BSD-Lite (such as FreeBSD, NetBSD, OpenBSD and DragonFly BSD) have been maintained by the open source community.

In 1980, a UNIX-like operating system called NeXTSTEP was developed by Steve Jobs’ company called NeXT. The NeXTSTEP kernel was based on the Mach kernel which was originally developed by Carnegie Mellon University (the Mach kernel was based on BSD UNIX). Later, NeXT was acquired by Apple Inc. This OS got rebranded as the MacOS, which is now a proprietary operating system of Apple Inc. and there is no direct relation with UNIX.

#### Linux enters the picture

The obvious question now is that if UNIX contains everything — one branch for enterprises, driven by AT&T, and another university developed BSD UNIX — how did Linux enter the picture and become more popular?

In 1984, AT&T started selling UNIX as a proprietary product, and entered into a courtroom battle with BSD. It took AT&T five years to win that legal battle. During this time, businesses went with AT&T’s clean room implementation to avoid any problems — people were looking for a System V style OS rather than a BSD style OS; so the popularity of BSD UNIX went down.

>The Linux operating system was introduced in 1991. It was primarily developed for personal computers whereas UNIX was designed for server computers. So, researchers, students and businesses got attracted to Linux, mainly because Linux installation was economical and did not require much specific and high-end hardware.

Enterprises were much slower to take on Linux, but soon commercial support was available with Red Hat and others. Commercial software vendors started porting their applications to Linux. It was only a matter of time before Linux took over from proprietary UNIX derivatives. Linux was UNIX at a much lower cost.

#### How UNIX is related to Linux and other open source software systems

In 1983, the GNU project was started by Richard Stallman with the goal of creating a completely free UNIX-like operating system. By early 1990, programs required for operating systems like compilers, text editors, UNIX shell, etc, were completed, but low-level elements such as device drivers were still under development. The Richard Stallman-inspired, free, UNIX-like operating system was not ready with a kernel.

In 1991, that wait was over. Linus Torvalds, a student from the University of Helsinki, introduced the Linux kernel, which was developed as part of an educational project. Later, it merged with Stallman’s GNU project that was UNIX-like but free.

The Linux operating system shares most of its components with UNIX. Text editors like Emacs, Vi, the UNIX shell, compilers and many more utilities are common in both Linux and UNIX.
