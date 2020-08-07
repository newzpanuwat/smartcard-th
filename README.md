# smartcard-th
POC Smartcard reader Python3

# Dependencies
Dowload pyscard then install
Ubuntu20 install pcscd python-pyscard python-pil

if got problem see this (not see modules)
https://sourceforge.net/p/pyscard/support-requests/7/

pcsc tools for ubuntu
https://justrocketscience.com/post/install-card-reader-ubuntu-vm/

# Driver
driver for this reader
https://drive.google.com/file/d/1dEC21wo-AfpPjrbU9McELYYLRtmBog8B/view



#Step
1.sudo apt install python3-pyscard
2. sudo apt-get install libusb-1.0-0-dev libpcsclite-dev pcscd pcsc-tools
3. insert card -> test -> pcsc_scan if correct not see any errors
