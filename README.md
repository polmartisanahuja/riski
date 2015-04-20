# Riski
Torrent based Automated Media Center with Raspberry Pi

### Installation
1. Install Raspbian in an SD card following https://www.raspberrypi.org/documentation/installation/installing-images/README.md

2. From your computer, ssh to your Raspberry Pi:
```sh
$ ssh pi@192.168.X.X
```
Once inside:
```sh
$ git clone https://github.com/polstein/riski
$ cp riski/riski.sh .
$ sh riski.sh
```
The installation will start and some input parameters will be prompted.

3. Open port 9091 of your Router to use Transmission remotely out of your private network.
4. 
