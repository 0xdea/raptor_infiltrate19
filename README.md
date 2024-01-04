# raptor_infiltrate19
[![](https://img.shields.io/github/stars/0xdea/raptor_infiltrate19.svg?style=flat&color=yellow)](https://github.com/0xdea/raptor_infiltrate19)
[![](https://img.shields.io/github/forks/0xdea/raptor_infiltrate19.svg?style=flat&color=green)](https://github.com/0xdea/raptor_infiltrate19)
[![](https://img.shields.io/github/watchers/0xdea/raptor_infiltrate19.svg?style=flat&color=red)](https://github.com/0xdea/raptor_infiltrate19)
[![](https://img.shields.io/badge/twitter-%400xdea-blue.svg)](https://twitter.com/0xdea)
[![](https://img.shields.io/badge/mastodon-%40raptor-purple.svg)](https://infosec.exchange/@raptor)

> "Sometimes, hacking is just someone spending more time on something than anyone else might reasonably expect."
>
> -- Jerry Gamblin

This repository contains all materials related to my talk *"A bug's life: story of a Solaris 0day"* presented at #INFILTRATE19 on May 2, 2019.

Related links:  
https://web.archive.org/web/20200518045907/https://techblog.mediaservice.net/2019/05/raptor-at-infiltrate-2019/ (blog post)  
https://vimeo.com/335197685 (video)

## advisory
* [**2019-01-cde-dtprintinfo.txt**](https://github.com/0xdea/raptor_infiltrate19/blob/master/advisory/2019-01-cde-dtprintinfo.txt). Official advisory for the 0day local privilege escalation via CDE dtprintinfo.

## exploits
* [**raptor/raptor_dtprintname_intel.c**](https://github.com/0xdea/raptor_infiltrate19/blob/master/exploits/raptor/raptor_dtprintname_intel.c). CDE dtprintinfo 0day exploit for Solaris/Intel (2019).
* [**raptor/raptor_dtprintname_sparc.c**](https://github.com/0xdea/raptor_infiltrate19/blob/master/exploits/raptor/raptor_dtprintname_sparc.c). CDE dtprintinfo 0day exploit for Solaris/SPARC (2004).
* [**raptor/raptor_dtprintname_sparc2.c**](https://github.com/0xdea/raptor_infiltrate19/blob/master/exploits/raptor/raptor_dtprintname_sparc2.c). CDE dtprintinfo 0day exploit for Solaris/SPARC with noexec stack (2004).
* [**raptor/raptor_dtprintname_sparc3.c**](https://github.com/0xdea/raptor_infiltrate19/blob/master/exploits/raptor/raptor_dtprintname_sparc3.c). Revised CVE-2019-2832 exploit (2020).
* [**dave/**\*](https://github.com/0xdea/raptor_infiltrate19/tree/master/exploits/dave). Original exploits for Solaris CDE dtprintinfo written by Dave Aitel during his time at @stake (2001).
* [**bas/aix_ppc_dtprintinfo.c**](https://github.com/0xdea/raptor_infiltrate19/blob/master/exploits/bas/aix_ppc_dtprintinfo.c). A bonus exploit for IBM AIX CDE dtprintinfo (thanks for sharing this, Bas!).
* [**bas/sol_sparc_dtp.c**](https://github.com/0xdea/raptor_infiltrate19/blob/master/exploits/bas/sol_sparc_dtp.c). Another CDE dtprintinfo 0day exploit for Solaris/SPARC, also courtesy of Bas.

## fuzzer
* [**sharefuzz1.0.tar.gz**](https://github.com/0xdea/raptor_infiltrate19/blob/master/fuzzer/sharefuzz1.0.tar.gz). Dave's fuzzer that led to the original discovery of the vulnerability in 2001.

## slides
* [**abugslife.pdf**](https://github.com/0xdea/raptor_infiltrate19/blob/master/slides/abugslife.pdf). Slide deck presented at #INFILTRATE19 (PDF version).
* [**abugslife.pptx**](https://github.com/0xdea/raptor_infiltrate19/blob/master/slides/abugslife.pptx). Slide deck presented at #INFILTRATE19 (PowerPoint version).
