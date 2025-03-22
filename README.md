# RyzenTosh B450-AII/5600G/Radeon™ Integrated Graphics
OpenCore EFI for B450 Chipset Motherboard with AMD Ryzen 5 5600G Processor + Radeon™ Integrated Graphics.
- Buy now here: https://druchill.web.app/store/efi-ryzentosh-amd/

# Important!
At the time of starting macOS can give you a black screen, if that is your case change SMBios and it will be solved.

- first test with MacPro 7.1
- then with the iMac 20.1
- OpenCore 0.9.4

## Specification

- Motherboard     : Asus Prime B450M - AII
- BIOS      : AMI BIOS LAST VERSION
- CPU       : AMD Ryzen 5 5600G with Radeon Graphics
- RAM       : 2 x 8GB DDR4 3200Mhz
- Storage   : 500GB SSD + 1TB HDD
- iGPU      : Radeon™ Integrated Graphics
- Ethernet  : Realtek RTL8111 Ethernet
- Audio     : Realtek ALC892
- Boot Mode : UEFI
- Bootloader : OpenCore 0.9.3
- OS : macOS Ventura 13.5 + Windows 11 Pro

## Whats Work?

- CPU Power Management
- Shutdown and Restart
- All USB Ports
- Ethernet
- HDMI
- Audio (Rear & Front)
- TRIM Support for SSD
- Etc

> [!TIP]
> The BIOS configuration is very important. Read more below.

## AMD BIOS Settings
- Note: Most of these options may not be present in your firmware, we recommend matching up as closely as possible but don't be too concerned if many of these options are not available in your BIOS.

### Disable
- Fast Boot
- Secure Boot
- Serial/COM Port
- Parallel Port
- Compatibility Support Module (CSM) (Must be off in most cases, GPU errors/stalls like gIO are common when this option is enabled)
- IOMMU

## Results
[![Captura-de-pantalla-2023-09-03-a-la-s-20-16-58.png](https://i.postimg.cc/L6Q8pm5g/Captura-de-pantalla-2023-09-03-a-la-s-20-16-58.png)](https://postimg.cc/QH53gGpj)

[![Captura-de-pantalla-2023-08-27-a-la-s-17-03-50.png](https://i.postimg.cc/RFx0DGFP/Captura-de-pantalla-2023-08-27-a-la-s-17-03-50.png)](https://postimg.cc/Mctxc71R)

[![Captura-de-pantalla-2023-08-27-a-la-s-17-14-38.png](https://i.postimg.cc/wxVBwXdV/Captura-de-pantalla-2023-08-27-a-la-s-17-14-38.png)](https://postimg.cc/6T8w3Gq2)

[![Captura-de-pantalla-2023-08-27-a-la-s-17-06-26.png](https://i.postimg.cc/NfjjSKsw/Captura-de-pantalla-2023-08-27-a-la-s-17-06-26.png)](https://postimg.cc/WtxVJbq9)

[![Captura-de-pantalla-2023-08-27-a-la-s-17-09-24.png](https://i.postimg.cc/sxwD1rJ8/Captura-de-pantalla-2023-08-27-a-la-s-17-09-24.png)](https://postimg.cc/cttN5P2M)
