# raptor_infiltrate19
[![](https://img.shields.io/badge/license-MIT%20License-red.svg)](https://opensource.org/licenses/MIT) [![](https://img.shields.io/badge/twitter-%400xdea-blue.svg)](https://twitter.com/0xdea)

#INFILTRATE19 raptor's party pack

> "Sometimes, hacking is just someone spending more time on something than anyone else might reasonably expect." -- Jerry Gamblin

This repository contains all materials related to my talk *"A bug's life: story of a Solaris 0day"* presented at #INFILTRATE19 on May 2nd, 2019.

Related links:
https://techblog.mediaservice.net/2019/05/raptor-at-infiltrate-2019/ (blog post)
https://vimeo.com/335197685 (video)

## advisory
* **2019-01-cde-dtprintinfo.txt**. Official advisory for the 0day local privilege escalation via CDE dtprintinfo.

## exploits
* **raptor/raptor_dtprintname_intel.c**. CDE dtprintinfo 0day exploit for Solaris/Intel (2019).
* **raptor/raptor_dtprintname_sparc.c**. CDE dtprintinfo 0day exploit for Solaris/SPARC (2004).
* **raptor/raptor_dtprintname_sparc2.c**. CDE dtprintinfo 0day exploit for Solaris/SPARC with noexec stack (2004).
* **dave/***. Original exploits for Solaris CDE dtprintinfo written by Dave Aitel during his time at @stake (2001).
* **bas/aix_ppc_dtprintinfo.c**. A bonus exploit for IBM AIX CDE dtprintinfo (thanks for sharing this, Bas!).

## fuzzer
* **sharefuzz1.0.tar.gz**. Dave's fuzzer that lead to the original discovery of the vulnerability in 2001.

## slides
* **abugslife.pdf**. Slide deck presented at #INFILTRATE19 (PDF version).
* **abugslife.pptx**. Slide deck presented at #INFILTRATE19 (PowerPoint version).
