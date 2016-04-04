# Sweetwater Trolley

GTFS files and future map for Sweetwater Trolley

See the Installation wiki page for more details

# Status

Beta (Testing in progress)

# Screenshots
A snap shot of the Sweetwater Trolley application
![sweetwatertrolleyscreenshot](https://cloud.githubusercontent.com/assets/8550894/14267215/49cbfc74-fa9c-11e5-8fd6-9aedb651f5ef.jpg)

Photo of the GPS Tracker as installed in the bus
![GPS Tracker 1](https://github.com/qtrandev/busTrackingGps/blob/master/images/GPS-Tracker1.jpg)  

A photo showing the various components of the GPS Tracker
![GPS Tracker 2](https://github.com/qtrandev/busTrackingGps/blob/master/images/GPS-Tracker2.jpg) 

# Press

None

# Why

We need a cheap open-source solution to track transit buses, and the Sweetwater Trolley system is one more system to be integrated into the entire Miami-Dade transit system

# Who

Dan Duffy's fork of Quyen Tran's Steetwater Trolley developed for Code for Miami so I can make changes, including this README.md file

<img src="https://github.com/Code-for-Miami/tasks/files/192773/SweetwaterTrolleyScreenShot.pdf">
Bus Tracking GPS
Included original Ada Fruit GPS program, original GPRS HTTP POST program (from Pachube), and both programs combined and modified which is the one that is actually loaded to the Arduino. Just copy the combined program to the Arduino SDK and uploaded to the Arduino. For GPS model and wiring visit https://learn.adafruit.com/adafruit-ultimate-gps/arduino-wiring. The GPRS Shield is from SeeedStudio.

# How

Hardware

Arduino board (Amazon link)
GPRS shield (Amazon link)
GPS board (Amazon link, Adafruit link)
Case for Arduino board (Amazon link)
SIM card with data plan (T-Mobile link)

Costs

Arduino board $21
GPRS shield $29
GPS board $40
Case for Arduino board $10
SIM card with data plan $40/month

Software

Miami Transit API LeafletTransit

# Deploy

See the Miami Transit wiki for Installation and assembly instructions.

# Testing

1) Connect GPS Tracker to USB power supply in the vehicle.
2) Place tracker in a location open to the sky for a good GPS signal.
3) Wait about 5 minutes for the signal to be obtained.
4) Open the Code for Miam LeafletTransit web app to view the location of the GPS Tracker.

# Contribute

Contact Code for MIA

# License

Code for America LICENSE.md file.

# More Information

Wiki of discussion of Miami-Dade county's bus tracking system (Wiki link)

# Attribution

Google Maps

Leaflet
