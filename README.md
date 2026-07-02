# Security for a Fictional Building - Tea House
## Description
This repository contains a comprehensive design for an alarm security system (PZS) for a fictional tea house. The project was created as a term paper for the course BPC-ZSY.

### Description of the building
Location: The property is located in the center of Frýdek-Místek (approx. 55,000 residents).  
Layout: A detached building with a rectangular floor plan (total area 255 m²) featuring 10 interior rooms.  
Entrances and Windows: The building has two possible entrances (the main door to the lobby and a roll-up door to the storage area) and a total of 13 windows, two of which—in the restroom—are protected by iron bars. 

### Security Analysis
* Value of Assets: The total estimated value of assets and cash is 760,000 Kč. The most valuable items are located in the office (safe, 250,000 Kč), in the warehouse (merchandise, 200,000 Kč), and at the main bar (120,000 Kč).  
* Security Level: Based on the data collected, the facility has been classified as Security Level 2.  
* Attacker Profile: The attacker is expected to have basic knowledge of the facility and basic tools (crowbar, drill), and will primarily target cash and high-value merchandise (alcohol, tobacco). 

### PZS System Design
* Central Control: The system is controlled by a JA-103KR control panel with an integrated radio module and a backup battery with a 48-hour runtime.
* Communication: The control panel is equipped with a JA-194Y LTE module for immediate sending of notifications (SMS, MyJablotron app) to the owner and the Central Monitoring Station (CMS).
* Perimeter Protection: The system uses 11 wireless PIR detectors (JA-150P) set to fan-shaped detection patterns.
* Perimeter Protection: All openable windows (11) are protected by concealed magnetic contacts (JA-152M), and the entrances are guarded by 2 mini detectors (JA-151M).
* Alarm Signaling: Local alarms are triggered by a wireless indoor siren and an outdoor battery-powered siren protected by an anthracite cover.
* Control: The system is operated via the JA-153E access module (keypad) at the main entrance using a PIN code or RFID tags.
