# Smart_Helmet_for_Coal_Miners 🛣️

This code helps to colaboration with various sensors assembled on the Helmet. 


## Code Requirements 🦄
You can install Arduino IDE to run the code which resolves all the dependencies of the sensors.
You also have to install the required libries given in `Requirements.txt`


## Description 🏎️
A Smart Helmet has been produced to help miners running withinside the mining industry. Many volatile incidents typically arise within the mining sector, which can cause life-threatening accidents or deaths. A miner's helmet is one of the best protection system for workers and hence it must have some advance features. With the use of various sensors, this helmet may be capable of perceive catastrophic situations, together with dangerous gases like Carbon-Monoxide, CH4, LPG, etc. Each sensor has a  threshold value that, if exceeds, the buzzer blows and the LEDs illuminates, warning the miners and supervisors about the feasible threats. All of the information from the sensors is seen on a  web application which allows the mining authorities to get a overview of the underground environment.


### Setup 🖥️

1) First connect all the hardware as shown in the `Circuit_Diagram.jpg`
2) Now you need to install the required libraries in Arduino IDE, to do so go through the libraries given in `Requirements.txt`.
3) Change the WiFi Name and Password in `Code.ino` and upload the code in NodeMCU and run the hardware.
4) Now the hardware gets connected to the local Wifi network. Use the IP mentioned in Serial moniter on a webpage to display the live results. 


### Results 📊

#### Assembly of the Hardware
<img src="https://github.com/anmolmaske/Imp_Files/blob/main/Helmet_Result1.jpg">

#### Live Web-page Result
<img src="">

## References 🔱
 
 - Yingli Zhu,Guoping You, “Monitoring system for coal mine safety based on wireless sensor network”,IEEE 2019 
 - Pranay Mangukar and Urmila Sharawankar, “Monitoring and Safety System for Underground Calamities”, Research Gate April 2018. 
 - A.J. Pudke And Sanket Banger, “Coal Mine Monitoring And Alert System With Data Acquisition” IEEE September 2017 
