# EFI for My Hackintosh ITX

---

This is the EFI file for my sexy ITX.

Thanks for the [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/). I won't get this far without this thorough tutorial.

## Hardware

---

- Motherboard: ***ROG STRIX B360-I GAMING***
- CPU: ***Intel Core i5-9400***
- Memory: ***Klevv DDR4 U-DIMM STANDARD MEMORY 2666 8GBx2***
- Wireless Card: ***BCM94360CS2***（Replaced the original onboard wireless card)
- GPU: ***GIGABYTE Radeon RX5500XT OC 8G***

## Software

---

- OpenCore: ***0.6.6***

- BIOS: 
  - Version: ***Latest***. You can get it [here](https://rog.asus.com/us/motherboards/rog-strix/rog-strix-b360-i-gaming-model/helpdesk_bios).
  - Setup: According to [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#intel-bios-settings)
- USB Creation Platform: ***MacOS***
- Tested Compatible MacOS: ***MacOS Big Sur 11.2.3***

## Precautions

---

- To make the iMessage and FaceTime work, you need to find a set of ***Serial***, ***Board Serial*** and ***SmUUID***.
- I won't be responsible for any potential hardware issue or data loss. So make sure you ***over-thought the risk*** and ***backup your data*** before using this EFI.
- ***I'm using an original disassembled Apple wireless card***. If you don't have one, you won't be able to use Wi-Fi, Airdrop, handoff and other functions that require this hardware support.

## Current Progress

---

- Multiple video output works (one 4K Monitor through DP and one 1080p Monitor through HDMI).
- Wi-Fi and Bluetooth work. Including AirDrop, Handoff, Sidecar due to the BCM94360CS2.
- CPU turbo works.
- Hardware accelerating with eGPU and iGPU works.
- USB works.
- Sleep and wake up ***partly works*** (see ***Issue*** section for detail).
- Audio works (may not be the most suitable layout, several layouts worked for me).
- iMessage and FaceTime work.
- Apple ID works.

## Issue

---

The only problem that concerns me is sleep.

The fans may start to spin automatically but won't light the monitor up. Except for this "issue", she can sleep and wake up perfectly.

I don't know if this is normal. If anyone knows it's normal or the solution, please let me know :)

## Tail

---

If you have any suggestion or question, here's my email: alexander2d6@outlook.com

Hope you will enjoy this EFI.

Bon appetite!

