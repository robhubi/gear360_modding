# Gear 360 modding
This is a Fork of https://github.com/ottokiksmaler/gear360_modding for the Samsung Gear 360 (2017)

Please see ottokiksmaler for more detailed commands and modding information.

I only added the time-lapse photo function.

## Features of this mod

* When ‘Photo’ mode is selected on the Gear 360, time-lapse shooting begins after 2 seconds. The interval time is 1.9 seconds

* When you exit Photo mode on the Gear 360, time-lapse shooting stops

* Does not do the ISO commands of the original mod, but only the NR commands


**Limitations**:

* The minimum constant interval time is 1.9 seconds (sleep=1s). With sleep=0.5s, the interval times are irregular: 70% of the intervals are 1.3 seconds long and 30% of the intervals are 2.2 seconds long

* Normal photo mode is not available

* Control via the Samsung app is not possible


## Instructions

* Download the file [gear360_mods_SD.zip](https://github.com/robhubi/gear360_modding/raw/master/gear360_mods_SD.zip) and extract it to the root directory of the microSD card (so that it contains `DCIM` and `mods` directories and `info.tg`, `mod.sh` and `nx_cs.adj` files)

* Put the card in the camera and power on the camera

* The blue LED above the power button flashes three times and a beep sounds (standard response)

* 2 seconds later you should see the blue light above the Power button light up for a second
* Double-click the [Power] button on the camera. 2 seconds later you should see a top light cycle green-orange-green to indicate telnet is working

* After 3 seconds, the top LED should flash red to indicate that time-lapse photo mode is ready..

* Select Photo mode using the menu button. Time-lapse recording will start

* Exiting photo mode will stop time-lapse recording. You may need to press the menu button several times before it is recognised