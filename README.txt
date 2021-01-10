1.  sudo apt install dkms git
2.  cd Downloads/
3.  git clone -b v5.6.4.2 https://github.com/aircrack-ng/rtl8812au.git
4.  cd rtl8812au/
5.  ls -ltr
6.  sudo make dkms_install
7. After Restart, you will see usb wifi blinks, it means it has been detected by linux kernel.
8. Main Menu> Go to Network > You will see PCI Wifi and USB Wifi. make sure wifi network in PCI wifi are all forgotten and Connect a fresh wifi from "USB Wifi". Check speed... :)

