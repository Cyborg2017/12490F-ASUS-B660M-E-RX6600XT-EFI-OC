**i5-12490F-ASUS-B660M-E-GIGABYTE-RX6600XT OC EFI**

**Based on [EFI](https://github.com/zemise/12490F-MSI-B660-MORTAR-WiFi-RX6600-EFI-OC)**

**Core parameters**

| **Hardware** | **Parameter**                         |
| ------------------ | :---------------------------------------------- |
| CPU          | Intel i5 12490F                        |
| Mainboard    | ASUS B660M-E                           |
| GPU          | AMD Radeon RX6600XT 8GB (GIGABYTE)     |
| RAM          | Gloway DDR4 2400 3200MHz*2             |
| SSD          | Disk1(MacOS)： WD BLACK SN770 500GB PCIE4.0     |
|                    | Disk2(Windows 11)：Samsung 980 PRO 1TB PCIE4.0  |
|                    | Disk3(Free)：GLOWAY STK512GS3-S7 500GB SATA     |
| WiFi + BT          | Intel AX211                               |

**Mirror**

MacOS Ventura 13.6.5 22G621 with OC 0.9.8

**BIOS**

Closed in BIOS:

- Secure Boot
- CSM（Custom - Only UEFI)
- Fast Boot
- Intel VT-D
- CFG Lock

**Additions**

Model：MacPro7,1  

CPU: Intel Xeon W-3245M CPU3.20 GHz

**Current Progress**



***
2024/03/24
- Initial changes for ASUS Mainboard
- Update intel wifi drivers from OpenIntelWireless/v2.3.0-alpha
- Custom USB port for asus b660m-e
- Update to MacOS Ventura 13.6.5 22G621 with OC 0.9.8


**WIP**
- All AirDrop related services.(limited by Wi-Fi and Bluetooth)
- After "sleep", can‘t wake up through USB devices.(only support the power button)
- After "sleep", bluetooth will excessively occupy the CPU process.(temporary solution: https://github.com/odlp/bluesnooze)

**Details**

About Device:

<img width="471" alt="image" src="https://github.com/Cyborg2017/12490F-ASUS-B660M-E-RX6600XT-EFI-OC/assets/29827082/87a1579c-ef9a-4b4f-9d70-1f9dbc7134f9">

WIFI(AX211):

<img width="468" alt="image" src="https://github.com/Cyborg2017/12490F-ASUS-B660M-E-RX6600XT-EFI-OC/assets/29827082/62fd2fc8-485c-4310-8b9d-7813c52b966c">

Bluetooth(AX211):

<img width="807" alt="image" src="https://github.com/Cyborg2017/12490F-ASUS-B660M-E-RX6600XT-EFI-OC/assets/29827082/48e2b267-b223-41a4-b803-2933e665321f">

Kernel:

<img width="1561" alt="image" src="https://github.com/Cyborg2017/12490F-ASUS-B660M-E-RX6600XT-EFI-OC/assets/29827082/a81f8dc7-c266-471d-bf95-144babedd7fe">

USB Ports:

<img width="885" alt="image" src="https://github.com/Cyborg2017/12490F-ASUS-B660M-E-RX6600XT-EFI-OC/assets/29827082/070226e3-d2b9-43b7-884c-abb5cf5795aa">

Geekbench6 Test(CPU):

<img width="788" alt="image" src="https://github.com/Cyborg2017/12490F-ASUS-B660M-E-RX6600XT-EFI-OC/assets/29827082/615bc08b-5276-45dc-a9df-22297ce3a46d">

Geekbench6 Test(GPU):

![image](https://github.com/Cyborg2017/12490F-ASUS-B660M-E-RX6600XT-EFI-OC/assets/29827082/217a7a4d-8db7-4fe1-98f8-f5908217212f)

**Thanks for**

1.国光 (https://apple.sqlsec.com)

2.黑果小兵 (https://blog.daliansky.net)
