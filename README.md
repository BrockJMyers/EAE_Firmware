# EAE_Firmware
Firmware exam solution for problem set provided by Epiroc.

Hello!
From the 7 and 7.1 assignments, I attempted to solve the problem denoted in 7 using the methods outlined in 7.1. My apologies, but I was not able to add all the items from 7.1 into 7 within C.

Within the code I did complete, I made the following assumptions:
1.	There exists a pointer to a clock within the microcontroller hardware that I can use to tell the present time. 
    a.	This is later used to create timers, as well as set up the 100ms loop.
2.	There is an alarm reporting system, that I can pass a struct to, which will alert the user through a UI.
    a.	Throughout the code, I denoted where alarms should be and set up a struct with the relevant information of the alarm. I am making the assumption that these structs can be read later.
3.	I am assuming the code needs to run continuously, as an RTOS system. Because of this, I set While(1) to continuously run the code.
    a.	Please feel free to disable this if you are running in VScode and dont wish to see timeout errors.

