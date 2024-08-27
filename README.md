# PREVAC TM-13/TM-14 thickness (frequency) monitor 
PREVAC TM-13/TM-14[^1] thickness monitor on Python
### Keyword
Python , module , method , library , PREVAC , TM-13 , TM-14 , serial IF , Binary I/O comunication , frequency , thickness ,

![PREVAC TM-13/TM-14](https://github.com/user-attachments/assets/fa39de1d-921b-412e-9dc7-44177fc06020)

## Overview
It helps to operate an PREVAC TM-13/TM-14 on Python.

### Function
Below functions are available, as libraries for PREVAC thickness monitor.
#### PREVAC_read_freq_module.py
1. Allocate serial IF communication
2. Receive frequency [^2]

 ![ Example ](https://github.com/user-attachments/assets/ac9b62b3-6478-4fed-b362-121585f916a0)

#### PREVAC_Thickness.py
1. Thickness code is copied from Prevac thickness LabVIEW module.
   

### Hardware Environment
  1. thickness (frequency) monitor : PREVAC TM-14
  2. USB: MOXA UPort® 1100 Series of USB-to-serial converter [^3]
  3. PC: windows PC
     
### Software Environment
  1. OS: Windows11
  2. Python: Version 3.9.13
  3. Libraries: PySerial
     
### Known issue
  1. CRC8 [^2]: It is not possible to resolve the CRC8 code for me, so it can only receive frequency data.
     
### Rerated Webpages
[^1]: [PREVAC TM-13/TM-14](https://prevac.eu/product/thickness-monitors-tm13-tm14/)
[^2]: [PREVAC TM-13/TM-14 Users Manual](https://moplink.prevac.pl/sharing/syM1c2nOM)
[^3]: [MOXA UPort® 1100 Series of USB-to-serial converter](https://www.moxa.com/en/products/industrial-edge-connectivity/usb-to-serial-converters-usb-hubs/usb-to-serial-converters/uport-1100-series)
