# SNFR - Safety Before Entry

## Project Overview

Senior design capstone project involving the development of a remotely operated hazard detection rover capable of detecting carbon monoxide (CO), hydrogen sulfide (H2S), and methane (CH4).
An integrated Ground Penetrating Radar (GPR) system was used to detect subsurface anomalies, including corroded rebar and void pockets within concrete to assist in determining the source of detected gas leaks.

## Personal Contributions

I independently designed, implemented, and tested the Ground Penetrating Radar (GPR) systems, including:

- Designed and evaluated multiple iterations of wideband antenna prototypes, culminating in a Balanced Antipodal Vivaldi Antenna (BAVA) design optimized for the Stepped Frequency Continuous Wave (SFCW) bandwidth
- Developed GPR RF front end by integrating BAVA antennas with a Raspberry Pi 5b and a commercial Nano VNA
- Developed a Python based software for SFCW signal processing and data visualization, including a live B-Scan for testing purposes as well as a wiggle-plot A-Scan snapshot triggered when an anomaly is detected
- Testing and calibration of RF systems
- Baseband analog signal amplification
- System integration with other rover systems
