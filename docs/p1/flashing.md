# Flashing OS

!!! warning
    Before flashing your device, make sure you back up your pipeline settings and camera calibration as the flashing process will wipe these settings. 

    If you are using PhotonVision, you can usually just use the Offline Update feature instead of flashing the OS, which will preserve your settings.

## Prerequisites
1. Download and install RPIBoot tool
    * Windows: [Download](https://github.com/raspberrypi/usbboot/raw/master/win32/rpiboot_setup.exe)
    * Mac/Linux: [Build from source](https://github.com/raspberrypi/usbboot)
2. Download and install [balenaEtcher](https://etcher.balena.io/)
3. Download the [latest PhotonVision image for Luma P1](https://github.com/PhotonVision/photonvision/releases) or other raspberry pi compatible vision solutions

## Put P1 in Flash Mode
1. Ensure P1 is not powered
2. Connect a USB C cable between your laptop and the device's USB C flash port
3. Run the RPIBoot tool to mount P1 as a mass storage device
    * Windows: Search "cm5" in the windows start menu, then run the `rpiboot-CM4-CM5 - Mass Storage Gadget` app
    * Mac/Linux: Run `sudo ./rpiboot` from the directory you built the usbboot tool in

## Flash the OS
1. Open balenaEtcher
2. Click "Flash From File" and select your OS image
3. Click "Select Target" and select the device labeled `mmcblk0`
4. Click "Flash" and wait for the flashing process to finish
5. Unplug USB C cable from device