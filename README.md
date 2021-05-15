usb-tl-wn727n-v.5.20-Kali-Linux-2021.1-vbox-amd64

Kernel version 5.10.0-kali3-amd64

sudo apt-get install linux-headers-$(uname-r)

Clone the repo with "git clone https://github.com/aircrack-ng/rtl8188eus -b v5.7.6.1"


Enter the folder with "cd rtl8188eus"

Before installation check issue and repair it.

https://github.com/aircrack-ng/rtl8188eus/issues/114#issue-824185114

sudo apt-get install bc

after sudo -i

Then run "make && make install"

And reboot in order to blacklist the module and load this module instead.

After you can use usb-adapter in monitore mode

sudo airomon-ng check kill

ip link set wlan0 down

iwconfig wlan0 mode monitore
