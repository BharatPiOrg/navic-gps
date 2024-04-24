# Bharat Pi ##
NavIC Live Location Tracker Dev Module
##
The Indian Regional Navigation Satellite System (IRNSS), with an operational name of 
NavIC (acronym for Navigation with Indian Constellation; also, nāvik 'sailor' or 'navigator' 
in Indian languages), is an autonomous regional satellite navigation system that provides 
accurate real-time positioning and timing services. It covers India and a region extending 
1,500 km (930 mi) around it, with plans for further extension. The system currently 
consists of a constellation of eight satellites, with two additional satellites on ground as 
stand-by.

Bharat Pi NavIC module is designed in a way to simplify development of live 
tracking/navigation devices and applications based on NavIC satellites. The module used 
is built for an India’s AIS-140 market needs with 2m CEP accuracy.

The module is capable of using NavIC L5, GAGAN L1, and GPS L1 signal to provide 3D
navigation in a single compact SMD module. It can track all in‐view GPS, GAGAN and 
NavIC satellites. It is fully autonomous such that once power is applied, the receiver 
automatically searches, acquires, and tracks satellite signals. When enough satellites are 
tracked with valid measurements, the receiver produces 3D position and velocity outputs.
NavIC + GPS dual‐satellite capability enables using greater number of satellite signal than 
GPS‐only receivers. The increased satellite number offers superior performance in
challenging urban canyon and multipath environments. The module contains single‐chip 
Phoenix positioning engine inside, featuring high sensitivity and fast TTFF (Time to First 
Fix). It can acquire, track, and get position fix autonomously in difficult weak signal 
environment. Its high tracking sensitivity allows continuous position coverage in nearly 
all outdoor application environments. The high-performance signal parameter search 
engine is capable of testing 16 million time‐frequency hypotheses per second, offering 
superior signal acquisition and TTFF speed.

## Key Features
- L1 / L5 signal reception
- Works with NavIC, GAGAN, GPS
- Less than 30 second cold start TTFF
- ~ 1 second hot start
- ~2.5m CEP accuracy
- Multipath detection and suppression
- Works with passive and active antenna
- Complete receiver in 12.2mm x 16.0mm size
- Operating temperature ‐40 ~ +85ºC
- Pb‐free RoHS compliant

## Technical Specifications

| Parameter               | Specification                                            |
|-------------------------|----------------------------------------------------------|
| Receiver Type           | NavIC L5, GAGAN/GPS L1 C/A code Phoenix engine          |
| Accuracy                | Position – 2.5m CEP                                      |
|                         | Velocity – 0.1m/sec                                      |
|                         | Time – 12nsec                                            |
| Startup Time            | ~1sec hot start                                          |
|                         | < 30sec cold start                                       |
| Sensitivity             | Better than ‐145 / ‐144dBm GPS / NavIC cold‐start       |
|                         | Better than ‐154 / ‐153dBm GPS / NavIC hot‐start        |
|                         | Better than ‐155 / ‐154dBm GPS / NavIC re‐acquisition   |
|                         | Better than ‐165 / ‐156dBm GPS / NavIC tracking          |
| Multi‐path Mitigation   | Multi‐path detection and suppression                     |
| A‐GPS                   | 7‐day server‐based AGPS   Self‐aided ephemeris estimation                                    |
| Update Rate             | 1 / 2 / 4 / 5 / 8 / 10 Hz, default 1Hz                   |
| Dynamics                | 4G (39.2m/sec2) acceleration                            |
| Operational Limits      | Altitude < 80,000m and velocity < 515m/s, not exceeding both|
| Serial Interface        | 3.3V LVTTL level UART, selectable 4800 ~ 115200 baud rate|
| Protocol                | NMEA‐0183 V3.01, SkyTraq binary, 115200 baud, 8, N, 1   |
| Datum                   | Default WGS‐84, User definable                           |
| Input Voltage           | 3.3V DC +/‐10%                                          |
| Current Consumption     | 80mA acquisition, 60mA tracking                         |
| Dimension               | 12.2mm W x 16.0mm L x 2.9mm H                           |
| Operating Temperature   | ‐400C ~ +850C                                           |
| Storage Temperature     | ‐550C ~ +1000C                                          |
| Humidity                | 5% ~ 95%                                                 |

## NavIC Pinout

![Alt text](https://i0.wp.com/bharatpi.net/wp-content/uploads/2024/02/Bharat-Pi-NavIC-Module-Pinout-R1.png?fit=2122%2C1490&ssl=1)

## NavIC Applications

Bharat Pi NavIC module can be easily mounted on Bharat Pi 4G boards for building live 
location tracking applications like GPS trackers, Asset monitoring etc. Bharat Pi 4G 
board comes with SD card for offline data caching. Any operator 4G/2G or even M2M 
sim card from Airtel, Jio, Vodaphone, BSNL can be used for cloud sync and live location 
tracking.

![Alt text](https://i0.wp.com/bharatpi.net/wp-content/uploads/2023/12/IMG20240104144244-scaled.jpg?fit=2560%2C1920&ssl=1)





