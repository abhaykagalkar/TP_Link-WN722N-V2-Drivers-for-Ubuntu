# TP Link WN722N V2 Drivers for Ubuntu

TP LINK TP-WN722N V2 150Mbps HIGH-GAIN WiFi- Receiver Ubuntu drivers

Follow instructions given below to install WiFi Drivers on Ubuntu 16.04 LTS with kernel 4.4

# NOTE : THE WIFI DRIVERS IS FOR VERSION 2 OF TP-LINK TL-WN722N.
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

# For further assistance on device visit the offical site
http://www.tp-link.in/download/TL-WN722N.html

