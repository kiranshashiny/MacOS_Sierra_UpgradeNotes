# MacOS_Sierra_UpgradeNotes

## Arduino 

##### USB Serial driver- Crash and resolution
    After the upgrade from Yosemite to Sierra the laptop started rebooting repeatedly without a break.
    I could not stop it - and it would happen the minute I login.
    On further investigation It would happen once I connected the Arduino - and would stop the minute I unplugged the Arduino.

    This URL was the closest I got to reporting my symptoms and had to reinstall the packages.

    The existing CH340 Serial port had to removed first and then newer version had to be installed.
    pkgutil --pkgs  |grep 34 # get the usb package here.
    pkgutil --files <usb_serial>.pkg # list installed files
   
    Install the newer version of Arduino 1.6.12
    https://blog.arduino.cc/2016/09/22/ide-1-6-12-released-with-sierra-support-and-more/


Snap 1
![alt tag](https://cloud.githubusercontent.com/assets/14288989/19014628/b7d1cfae-880f-11e6-9d5b-0c69830953a2.png)


Snap 2 200
<img src="https://cloud.githubusercontent.com/assets/14288989/19014636/f7f41b3c-880f-11e6-90ca-73572e6eb8ac.png" width="200">
Snap 2 800
<img src="https://cloud.githubusercontent.com/assets/14288989/19014636/f7f41b3c-880f-11e6-90ca-73572e6eb8ac.png" width="800">
Snap 2 1000
<img src="https://cloud.githubusercontent.com/assets/14288989/19014636/f7f41b3c-880f-11e6-90ca-73572e6eb8ac.png" width="1000">

Snap 3
![alt tag](https://cloud.githubusercontent.com/assets/14288989/19014633/e7af42b0-880f-11e6-806e-ff5c17063d64.png)

Snap 4
<img src="https://cloud.githubusercontent.com/assets/14288989/19014636/f7f41b3c-880f-11e6-90ca-73572e6eb8ac.png" width="24">

Snap 5
![alt tag](https://cloud.githubusercontent.com/assets/14288989/19014642/3637045e-8810-11e6-97c7-c18c9e2517ef.png)

## Sametime had to be reinstalled
    https://w3.the.ibm.com/mac/#/en-US/support/connect_to_network_at_ibm/connect_at_ibm_overview

## Mobility Client had to be reinstalled
    From same location as above.
