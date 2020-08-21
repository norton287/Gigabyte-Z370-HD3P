# Gigabyte-Z370-HD3P
SSDT for USBInjectAll and **OpenCore EFI** I am using for Gigabyte **Z370 HD3P** with an **I7-8700K** CPU.  I am currently running the **F10** bios with no problems with macOS 10.15.6 installed.  Sleep/Wake works well and I have Power Nap running as well.

I am using a ***Sapphire RX580 Pulse*** video card and have the iGPU configured to run headless.

Here is my hardware installed:

- I7-8700K CPU (Overclocked to 4.9Ghz)
- Kingston Technology HyperX Fury Black 32GB 2666MHz DDR4 CL16 DIMM Kit of 2 (HX426C16FBK2/32)
- 2 Samsung 970 EVO 1TB NVMe PCIe M.2 2280 SSD (MZ-V7E1T0BW) (Primary macOS drive and one for my Home directory on macOS)
- 2 Samsung 960 EVO 1TB SSD (One for Windows and the other for my second macOS installation)
- PCI-E Wi-Fi Adapter BCM943602CD– 802.11 a/b/g/n/ac
- Cooler Master Hyper 212 Evo (RR-212E-20PK-R2) CPU Cooler with PWM Fan, Four Direct Contact Heat Pipes
- Rosewill Gaming ATX Full Tower Computer Case Cases THOR V2 Black

For my BIOS settings see the [BIOS](BIOS.md) settings information.  GA released the F12 bios last month, and like F11b it does not boot with an M.2 NVME drive.  The macOS NVME driver fails to load on boot.

I am now running OpenCore 0.6.0 and have uploaded my EFI folder here with all my files.  If you want to use it then edit the config.plist and under Platform enter your machines serial number and motherboard serial as well.  It works well and allowed me to install Big Sur Beta 3 with hardly any problems.

## macOS Beta

I am running macOS Big Sur Beta 5 Release now on my Beta drive installed in my system.