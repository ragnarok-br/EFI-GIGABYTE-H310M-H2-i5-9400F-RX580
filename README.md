# EFI Gigabyte H310M H 2.0 + i5 9400F + RX 580

**Power Management Full**:

![Power Management-12 3 1](https://github.com/ragnarok-br/EFI-GIGABYTE-H310M-H2-i5-9400F-RX580/blob/main/Images/PWMan.png)

**About this mac**:

![about-12 3 1](https://github.com/ragnarok-br/EFI-GIGABYTE-H310M-H2-i5-9400F-RX580/blob/main/Images/About.png)

**Latest working macOS**: Ventura 13.2
<br>
**Current OpenCore**: 0.8.9

## Complete hardware specs
- Intel i5 9400F
- Gigabyte H310M H 2.0 @ BIOS F14a
- RX 580 - Nitro+ Special Edition (Sapphire)
- 2x 8Gb DDR4 2666MHz Crucial Ballistix Sport LT
- SSD Crucial 500GB

## What works
- macOS Big Sur, macOS Catalina, macOS Monterey and macOS Ventura
- Audio
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- Shutdown/Reboot/Update to newer macOS builds over time

## Kexts used:
- AppleALC.kext
- Lilu.kext
- RealtekRTL8111.kext
- RestrictEvents.kext
- SMCProcessor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Inclused in SSDT:
- EC, USBX, PMC, AWAC e PLUG

## Fix Patches used:
- HPET _CRS to XCRS, GPRW to XPRW, _DSM to XDSM, RTC IRQ e TMR IRQ

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- Gabriel Luchina and Maldon

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
