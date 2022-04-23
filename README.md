# Hackintosh
# EFI Acer Aspire 5 (model:A515-54-712U)

### Currently Running On MacOS Monterey 12.3.1 


## Hardware - Hackintosh Config

|       Type       | Item                                             |
|:----------------:|--------------------------------------------------|
|     **CPU**      | [ Intel(R) Core(TM) i7-10510U CPU @ 2.30GHz ]    |
|     **RAM**      | [ 20GB DDR4 2666Mhz (upgraded from 8gb)]         |
|     **GPU**      | [ Intel Graphics 620]                            |
|     **SSD**      | [ NVMe 512gb - Default from Factory]             |
|    **WI-FI**     | [ Swapped to a BCM94360ng for AirDrop fix]       |
|                  |                                                  |
|    **SMBIOS**    | [ MacbookPro16,1 ]                               |
|    **MacOS**     | [ Monterey - 12.3.1 ]                            |
|   **Opencore**   | [ 0.7.8 ]                                        |


## BIOS Setting

### BIOS Version: F15b

### Disable

```
* Fast Boot
* Secure Boot
* VT-d
```

### Enable

```
* SATA Mode: AHCI (If not showing, press Control + S)
```

## DO NOT FORGET TO Change Serial,MLB,SMUUID according to the Guide

## Guide<br>

- [Open Core Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)


[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)