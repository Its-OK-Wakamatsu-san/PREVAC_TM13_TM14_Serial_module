# PREVAC TM-13/TM-14 thickness (frequency) monitor 
PREVAC TM-13/TM-14 serial on Python
### Keyword
Python , module , method , library , PREVAC , TM-13 , TM-14 , serial IF , Binary I/O comunication , frequency , thickness ,

![PREVAC TM-13/TM-14](https://github.com/user-attachments/assets/fa39de1d-921b-412e-9dc7-44177fc06020)

## Overview
It helps to operate an OMRON digital controller from an external PC.  The device used is an OMRON E5AC-TCX4ASM-000[^1] digital controller without an RS-485 communication IF.

### Function
Below functions are available, as libraries for Omron Digital Controllers.
1. Allocate serial IF communication
2. Typical CompoWay/F protocol command and response
3. Enable Manual Mode
4. Read temperature 
5. Set output value

> [!TIP]
> 1. CompoWay/F bautrates is 38400bps, not 9600bps.
> 2. BCC(Block Check Character) is 8-bit value that is the result of an EXCLUSIVE OR sequentially performed between each 8-bit in a transmission.[^2][^3]
> 3. The EXCLUSIVE OR module: copied from GitHUB TurBoss website.[^4]

### Hardware Environment
  1. Temperature Controller : OMRON E5AC-TCX4ASM-000 Digital Controller without RS-485 communication IF.[^1][^5][^6]
  2. USB: OMRON USB Serial Conversion Cable E58-CIFQ2 [^7]
  3. PC: windows PC
### Software Environment
  1. OS: Windows11
  2. Python: Version 3.9.13
  3. Libraries: PySerial
### Known issue
  1. None
### Rerated Webpages
[^1]: [OMRON Digital Temperature Controllers E5AC Catalog](https://www.fa.omron.co.jp/products/family/3157/download/catalog.html)
[^2]: [Frame Checksum (FCS)....EXCLUSIVE OR ...expressed in ASCII Characters](https://www.manualslib.com/manual/1538556/Omron-Sysmac-Cv-Series.html?page=60)
