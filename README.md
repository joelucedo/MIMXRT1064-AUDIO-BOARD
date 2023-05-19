# MIMXRT1064 MCU Module
## STATUS
Work in progress.  
</br>
The goal is to have a powerfull small audio system on module supported by the FAUST audio DSP programming language.  
Something like small form factor(4x4) low profile module with castellated pads to be solder on carrier board.
## SPECS
#### MCU : MIMXRT1064CVL5B 
* ***Cores*** : 1 x ARM Cortex M7 (32KB L1 Cache - FPU)
* ***Clock frequency*** : 528 MHz  
* ***On chip Flash*** : 4MB  
* ***On chip RAM*** : 1MB
* ***USB*** : Two USB 2.0 HS OTG controllers with integrated PHY interfaces
#### SDRAM : IS42S16160J-6BLI
* ***Memory Size*** : 256Mb
* ***Data Bus Width*** : 16 Bit
* ***Maximum clock frequency*** : 166MHz
#### QSPI Flash : IS25WP064A-JBLE
* ***Memory Size*** : 64Mbit
* ***Data Bus Width*** : 8 Bit
* ***Maximum clock frequency*** : 133MHz
#### SD Memory Card Socket
* ***Capacity*** : Up to 2TB SDHX card
* ***Data transfer rate*** : Up to 104 MB/s (UHS-I SDR104)
#### Audio codec : WM8978CGEFL/RV
* ***Sampling rate*** : Up to 48MHz
* ***Bit Depth*** : 24 bits (ADC & DAC)
* ***Nbr of Channels*** : 1 channel (LADC - RADC - LDAC - RDAC)
* ***On-chip Headphone Driver***
* ***1W output power for 8ohm BTL speaker***
* ***Mic preamps (stereo differential or mono)***
* ***Multiple Line inputs & outputs*** 
