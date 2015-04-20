# Riski
Torrent based Automated Media Center with Raspberry Pi (RPi)

### Installation
1. Install the Raspbian OS image into a SD card following https://www.raspberrypi.org/documentation/installation/installing-images/README.md

2. Create a personal DNS  (e.g. mydns.duckdns.org) throughout http://duckdns.org/ 

3. Plug the flashed SD card in the step 1 into the RPi card slot and connect an external USB  self powered HDD to your Raspberry Pi (Important!!! Data inside will be erased). Additionally, connect an external USB keyboard to the RPi and finally and plug the RPi into a 5V micro USB power source, your RPi will boot for the first time and a configuration menu will pop-up. 
    
    By navigating through menu with keyboard, (1) expand the file system, (2) configure the Time Zone and (3) configure the LOCALE. By pressing Finish, the RPi will reboot. 

5. A login prompt will appear. Type user: pi and password: raspberry. Once the command line prompt $ appears, type:
    ```sh
    $ git clone https://github.com/polstein/riski
    $ sh riski/riski.sh
```
    The Riski installation will start and some input parameters will be prompted during the installation:

5. Open port 9091 of your Router to use Transmission remotely out of your private network.

