# 4-Way-Remote-RF-Switch
Remote RF Switch with WiFi control and power-over-coax.




Docs for the XCR Maker WiFi Antenna Switch - 4 Way Version

This project is a WORK IN PROGRESS!!!
XCR Maker is a very losely disorganized group of retired Collins Radio engineers who feel the need to develop new or better things. 

Contact WØIY (ok via QRZ)

Abstract
This project is Remote Antenna Switch KIT. A Bias T supplies 12VDC via the main coax from the shack. Control is via WiFi (either direct or LAN). A very nice weather RESISTANT enclosure is provided so the switch can be located in a garage or outdoors*. Mechanical assembly and soldering required, possibly some minor drilling.

Details
The concept for the remote switch has been around for awhile. After working on the matrix, it became clear it would be a huge effort to go into production. The 4 Way is a way to dip a toe in the water. There are currently (2021-03) a few units (kits). There are 2 PCB: a RF switch with SO239 and relays, and a CPU board with ESP32 (wifi capable cpu).

WiFi may be either direct access (no router, think FD) or via a LAN (home router). As of 2021-02 the user SSID and PW must be hard coded. Future software will support user configuration (ETA May 2021). There is no way to have sw upgraded other than to swap the CPU board. This save sw development and improves security, but is a logistical pain. Software efforts will be applied to the 4 Way, but will also support the 6 Way and Matrix.

The enclosure is VERY nice. There is a lip around the door and the bottom has foam to conform to the cables. The case should be considered Weather RESISTANT, not weatherproof. A lot depends on the mounting location, local weather conditions, etc. 
RG58 will easily fit the existing entry foam. RG8 will require cutting the plastic finger to enlarge the gap.

A mailing list and/or forum for posting updates is available at:      https://groups.io/g/xcrmaker
Please join the group to keep up to date on news and to assist other users.

Full Disclosure
1. The kits will become available slowly (10-20/month) as best can be managed. PCB's come from China; most other parts are purchased from US distributors (who probably get them from China). 
2. The 4 way is a way to ease into production and distribution. 
3. There will be a 6 Way (maybe Summer 2021) and the 2x6 Matrix about the same time. The 6 Way will have a similar (but larger) weather resistant enclosure. The Matrix will NOT.
4. Lightning protection is entirely up to the user. A ground wire should be installed from the metal shelf to Ground. If there is a direct strike, this will be destroyed (WA9ENA agrees with this assessment). A fully hardened version may be available later for an estimated $20K. Please sign up on the (nonexsisten) waiting list. 
5. There will be a low cost Bias T kit about in Spring 2021. Refer to the mailing list for details

Photos
The RF PCB is user assembled with Through-Hole parts. The CPU board is SMD and comes mostly assembled. The user installs a 90 degree male header connector. 
The ESP32 CPU comes with either a builtin WiFi antenna or a version with a connector for an external antenna which the user can install by drilling a hole for an SMA connector and adding a rubber duck whip. 

A thin metal shield is being developed which will fit over the relays and wrap around. The bracket is being tested in a slightly different configuration (bent up rather than down).
These photos will be updated as needed.



![20210201_201440](https://user-images.githubusercontent.com/24881873/109878645-2b387600-7c3a-11eb-9a53-ac7dac92179b.jpg)


Here you can see the CPU PCB, this one with integral WiFi antenna.
![20210201_201527](https://user-images.githubusercontent.com/24881873/109878732-43a89080-7c3a-11eb-93bf-5517d89ac186.jpg)

This is browser window of the control. It is very small and can be left open beside your logging software. This software version is alive and working now.
![RF Switch op page](https://user-images.githubusercontent.com/24881873/109885652-81121b80-7c44-11eb-8628-c905c2b63c45.jpg)


