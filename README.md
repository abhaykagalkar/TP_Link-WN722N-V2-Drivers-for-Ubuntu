# TP Link WN722N V2 Drivers for Ubuntu
## TL-WN722N-V2

![TP_Link-WN722N-V2-Drivers-for-Ubuntu](device_img.jpg?raw=true "TP_Link-WN722N-V2-Drivers-for-Ubuntu")

TP LINK TP-WN722N V2 150Mbps HIGH-GAIN WiFi- Receiver Ubuntu drivers

Follow instructions given below to install WiFi Drivers on Ubuntu 16.04 LTS with kernel 4.4

## NOTE : THE WIFI DRIVERS IS FOR VERSION 2 OF TP-LINK TL-WN722N.
To know how to find the version of the USB Adapter visit the official site of TP-Link
http://www.tp-link.in/faq-46.html

 INSTRUCTIONS TO INSTALL WIFI DRIVERS ON UBUNTU 16.04 LTS
```
sudo apt-get install git dkms git make build-essential
cd /usr/src
sudo git clone https://github.com/abhaykagalkar/TP_Link-WN722N-V2-Drivers-for-Ubuntu.git
sudo dkms add ./TP_Link-WN722N-V2-Drivers-for-Ubuntu
sudo dkms build 8188eu/1.0
sudo dkms install 8188eu/1.0
sudo modprobe 8188eu
```
 After successfully installation reboot your system.

## Donate
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](http://www.paypal.me/abhaykagalkar)

## Assistance
If you want to help please ping me on Email.
abhay@codesexplorer.com

## Contributors

[Abhay Kagalkar](http://www.codesexplorer.com/p/about.html)
1. Github: https://github.com/abhaykagalkar
2. Email: abhay@codesexplorer.com or abhaykagalkar@gmail.com


# For further assistance on device visit the offical site
http://www.tp-link.in/download/TL-WN722N.html

