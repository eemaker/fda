# FDA
yet another FULL DIGITAL AUDIO project

## create another FDA from scratch

## my experience

- UAC2 project with FX2LP + CPLD
  - complete CPLD alpha version code but need more effect for tuning
  - complete FX2LP alpha version code, but need more debugging
  - not good for a share project, as the requirment of CPLD programming tool
- UAC2 project with ATMEL SAM3U
  - no opensouce fork, my code did not complete, only play 48K in UAC1 mode now
  - the chip is near EOL ?
- UAC2 project with ATMEL AT32U
  - fork from http://www.pavouk.org/hw/audiosystem20/at32uc3a3256usbi2s.html
  - the chip is near EOL, high cost
  - software ready to use

## the goal of this project

- use STM32F4 to rebuild
  - popular chip, not expensive
  - ST released UAC sample code
  - firmware will be easy to install/upgrade with DFU tool and STM32 built-in boot loader
  
## delivery

- share my information collection
- share schematic in PDF format
- share binary code
