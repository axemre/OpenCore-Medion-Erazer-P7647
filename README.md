# Hackintosh - Medion Erazer P7647
Hackintosh configuration (EFI) for the Medion Erazer P7647 (OpenCore 0.6.0, Big Sur)

## Disclaimer
This configuration or EFI is for reference purposes, it may be outdated. Use these files as a reference for your configuration made using following guide: [Dortania's OpenCore guide](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html)

Specs:


* CPU: Intel Core i5-7200U, Kaby-Lake, up to 3,1GHz
* iGPU: Intel HD Graphics 620 (this is the GPU being used by macOS)
* dGPU: Nvidia GeForce GTX 950M, 4 GB VRAM (disabled using -wegnoegpu)
* RAM: 8 GB DDR3L
* SSD: 128 GB
* HDD: 1,5 TB
* macOS BigSur
* SMBIOS MacBookPro 14,2
* OpenCore Version 0.6.0

What works?

* Boot 
* WiFi (works using itlwm)
* Bluetooth (works using IntelBluetoothFirmware + IntelBluetoothInjector)
* Display brightness ( set using Fn+Pause (+) and Fn+NumLk (-) )
* USB ports (all)
* Webcam + Microphone
* Sound 
* Keyboard
* Touchpad (including gestures, multi-touch)
* everything else except the "not working" list below..

What does not work?

* HDMI (not tested, probably working, I personally don't need HDMI output on this particular laptop)
* Lid-Sleep/Wake (Lid-Wake does not even work in Windows on this laptop, sleep using Menu (Apple logo > Hibernate) does work and wake using power button works perfectly fine)
* SMC (fan control) 
* NVIDIA dGPU (does not work, has Optimus, disabled using -wegnoegpu)
* maybe something else I have missed?

Picture of the laptop:


![1284989](https://user-images.githubusercontent.com/19302720/117622059-8626a600-b172-11eb-94f7-04802814bb2d.jpg)


Screenshot of booted Big Sur:


![Bildschirmfoto 2020-07-27 um 12 53 58](https://user-images.githubusercontent.com/19302720/117622126-976fb280-b172-11eb-9bbb-39b0415ef247.png)



