OURphone v2

Goal:
- Faster CPU
- Thinner handset
- Longer battery life
- More usable
- More features
- More phone-like OS
- Better screen
- More attractive design
- More desireable

(better in every way)

Join the discussion on:
https://t.me/ourphonechat

Crowd-funding campaign: 
https://buymeacoffee.com/ourphone

Design principles:
A standardised compute module (CM4) will provide the computer and OS capability (incl bluetooth and wifi). 
This will dock with our custom PCB which will offer power management, a built-in SIM7600 chip for calls, SMS and 4G internet, a sound amp, headphone jack and USB camera.
We hope to stack all of this together between 12 - 15mm total height.

Update 8 Dec 2024:
Current Telegram group members: 103
Crowd-funding raised so far: $400
We have raised enough to hire a professional PCB designer on UpWork to design v1 of our new PCB. He is busy. 
We are working on the outstanding issues listed in our wiki document (find link in Telegram group).

Update 6 Apr 2025:
Current Telegram group members: 127
Crowd-funding raised so far: $1,100
After much debate we took the SIM7600 modem chip off the PCB board so that it becomes more modular and the PCB is cheaper to produce and iterate on. The SIM7600 will now plug in via an M2 connector.
I will start uploading the EasyEDA files into the V2 folder as they become available.
Next step is to order a PCB and test it.

Update 22 Oct 2025:
Current Telegram group members: 150
Crowd-funding raised so far: $1,910
After trying to order the PCB we discovered that a 3 layer PCB with filled vias cost an extra ~$300 to manufacture. This requirement was due to the power management chip we were using which was in a BGA form factor. We switched PCB designers, chose a different chip and simplified the design so that it now costs $66 to manufacture and assemble incl components.
The board has been manufactured and is being couriered now for testing.

Update 7 Mar 2026:
Current Telegram group members: 168
Crowd-funding raised so far: $2,660
Latest PCB board is working well! We have gotten these parts of the system working so far: Charging, battery power supply, HDMI out, speaker audio, headphone audio, microphone in, WIFI, cellphone (calls, SMS, 4G data), GPIO buttons, webcam. Have chosen a 5 inch touchscreen from Waveshare to incorporate. Booted into an Armbian image for Ubuntu and Phosh immediately worked perfectly to create a phone-like experience. Busy working on the spec for the next PCB board iteration: incorporating screen and upgrading OrangePi CM4 to OrangePi CM5 (with compatible pins for Raspberry Pi CM5). Still to figure out: How to make one GPIO button perform the sleep and wake commands, how to pipe through battery levels into the OS, how to setup GPS.
