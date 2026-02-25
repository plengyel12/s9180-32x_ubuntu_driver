# S9180-32X Driver
Tested on ubuntu 24.04 LTS

Dependencies:
sudo apt install -y i2c-tools

To build:
dpkg-buildpackage -us -uc -b
To install:
sudo dpkg -i ../sonic-platform-ingrasys-s9180-32x_1.1.0_amd64.deb 

To confirm, check status:
sudo systemctl status s9180-32x-monitor.service --no-pager