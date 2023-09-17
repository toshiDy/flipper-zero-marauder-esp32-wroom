# Flipper Zero Marauder ESP32-WROOM

### This project based on:
[UberGuidoZ Flipper](https://github.com/UberGuidoZ/Flipper)  
[SkeletonMan03 FZEasyMarauderFlash](https://github.com/SkeletonMan03/FZEasyMarauderFlash)


# Getting started:
1. Install **WiFi Marauder** on Flipper Zero:
- Download: [github](https://github.com/UberGuidoZ/Flipper/blob/main/Applications/Custom%20(UL%2C%20RM%2C%20XFW)/RogueMaster/GPIO/ESP32/wifi_marauder.fap)
- Put downloaded file to Flipper's SD Card. Path: SD Card/apps/GPIO/"here"  

2. Download [FZEasyMarauderFlash](https://github.com/SkeletonMan03/FZEasyMarauderFlash)
3. Follow instructions [**here**](https://github.com/SkeletonMan03/FZEasyMarauderFlash#readme) to flash Marauder to ESP32
4. Connecting ESP32-WROOP to Flipper Zero:

    1. **TURN OFF FLIPPER ZERO!!!**
        - Flipper Zero → Settings → Power → Power OFF
    2.

    |     ESP32    	|                  Flipper Zero                 	|
    |:------------:	|:---------------------------------------------:	|
    | TX0 [GPIO 1] 	|                    RX [14]                    	|
    | RX0 [GPIO 3] 	|                    TX [13]                    	|
    |      GND     	| GND [8 or 11(keeps all wires together) or 18] 	|
    |      3v3     	|                    3v3 [9]                    	|

5. Turn on Flipper Zero by holding "⏎" button
6. Flipper Zero → Apps → GPIO → wifi_marauder
7. Enjoy

# Disclaimer:

The information provided on this site is not intended for illegal use. Users are solely responsible for their own actions and should exercise discretion and caution when using this information. The author, administrator, or host of this site does not assume any responsibility for the actions, decisions, or consequences of its users. The information provided here is not meant to provide legal advice and users are encouraged to seek appropriate professional guidance when needed. The author disclaims any liability for any direct or indirect damages, losses, or liabilities that may arise from the use of this information.