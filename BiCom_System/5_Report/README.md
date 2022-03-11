
# Description


Bicom System
A Bicom system is the extention of the unidirectional RKE to bidirectional RKE. This systems shows alarm statuts, window status, car battery information and door status.Each of these functions are displayed with the help of LED. For window status blue switch on all led on at the same time. For alarm status blue switch pressed two times all led off at the same time. For battery switch press Three times all led in clockwise manner and for Door status press switch four times all led in anticlockwise direction.


# Features
It will dislay Window status of the car when Button is pressed one time
It will display alarm statusof the car when Button is pressed two time
It will display battery status of car when the Button is pressed three times
It will display door statusof car when the Button is pressed four times

# High Level Requirements
|ID|	Description |
|---:|:-----------|
|HLR1|	It should Display Window status.|
|HLR2|	It should Display Alarm Status.|
|HLR3	|It Should Display Battery status.|
|HLR4	|It Should Display Door status.|

# Low Level Requirements

|ID|	Description|
|----:|:-------------------------------------------------|
|LLR1	|Press blue button 1 time, All led ON at the same time.|
|LLR2|	Press blue button 2 time, All led OFF at the same time.|
|LLR3|	Press blue button 3 time, All led glows in clockwise manner.|
|LLR4	|Press blue button 4 time, All led glows in anticlockwise manner.|


 # SWOT

## Strength:

* we can check our window,alarm,battery and door status with button click.

## Weakness:

* It has limited range and Replacing a lost fob costs much more than a traditional key.

# Opportunities

Allow users to use their smartphones for checking the security factor of car and even controlling extra features.
Threats: * Thieves, however, are rising to the challenge, using radio transmitters to perform ‘relay’ car hacks to capture the signal from the car’s fob possibility for hackers to manipulate the technology and steal your vehicle.

# 5W's And 1H
## Who
* People who own a car.

## What
* The system can control the feature of car by wireless key.
* The status of different features of the car is given by LED's or display.

## When
* When the user wants to know the status of windows , alarm ,battery and door.

## Where
* Where the owner want to use the features of ther car provided .

## Why
* To know the working and status of different features of the car.
* To use different feature of the car with ease .

## How
* The features can be used by buttons of your remote or device .

# Behavioural Diagram
![Bicom system (1)](https://user-images.githubusercontent.com/98838344/157845520-9403535f-ff74-4a39-96b5-818670e9664c.png)

# Test Plan

# High Level Test Plan

| Test ID | Description | Input | Expected Output | Actual Output |
|---------:|:----------:|:------:|:--------------:|:---------------|
|01 | Print window status | User presses button once | Print window status of car | Print window status of car |
|02 | Print alarm status | User presses button twice | Print alarm status of car | Print alarm status of car |
|03 | Print car battery info | User presses button three times | Print car battery info |  Print car battery info |
|04 | Print door status | User presses button four times | Print door status of car | Print door status of car |

# Low Level Test Plan 

| Test ID | Description | Input | Expected Output | Actual Output | Passed |
|--------:|:-----------:|:-----:|:---------------:|:--------------:|:-------|
| 01      | check print window status |User presses button once| All LEDs should on | All LEDs should on | Pass |
|02 | Check print alarm status | User presses button twice | All LEDs should off | All LEDs should off | Pass |
|03 | Check print car battery info | User presses button three times | LEDs should on once clockwise | LEDs should on once clockwise | Pass |
|04 | check print door status |  User presses button four times | LEDs should on once anticlockwise | LEDs should on once anticlockwise | Pass |





