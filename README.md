# SDCard-Interface-STM32 Ported from CubeIDE to SeggerStudio

An interface between the STM32F407VET and a micro-SD card. 
Just simple munt SD-card, create text file and write string into it.

***
## Objective:
- [x] Implement SDIO communications
- [x] Interface the micro-SD card with the MCU for storage capabilities.
- [x] Provide LED light indication for card detection
- [x] Condense the program to a callable function
- [x] Store the output as a CSV file
- [ ] Improve modularity for a swappable interface
- [ ] Build a report generator with Excel and/or MatLab, or use DFR's DataAnalyzer


## Technologies:
* General Purpose I/O (GPIO)
* 4-bit SDIO communication protocol
* [File Handling Library by Controllers Tech](https://controllerstech.com/interface-sd-card-with-sdio-in-stm32/) (Modified)
* HAL drivers & [FAT FS](http://elm-chan.org/fsw/ff/00index_e.html)

## Hardware and Equipment:

1. [STM32F407VET board from Aliexpress.com (MCU)](URL add here) - Equipped with the ARM Cortex M4 processor


## Pinout
* PC8 ---> DAT0
* PC9 ---> DAT1
* PC10 --> DAT2
* PC11 --> DAT3
* PC12 --> CLK
* PD2 ---> CMD
* PD3 ---> CD (Card Detection)

***

