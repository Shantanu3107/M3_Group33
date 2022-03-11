# Report

## Contents
* Abstract
* Features
* High Level Requierment
* Low Level Requierment
* SWOT Analysis
* 4W' and 1H
* Behavioural Flowchart
* Structural Diagram
* Test Plan And Output


# Remote Keyless Entry(RKE)
# Abstract
Remote keyless entry (RKE) is an electronic access system that can be controlled from a distance. RKEs, which are typically used to remotely lock or unlock doors, require the end user to initiate an action that will cause a physical or software key fob to transmit a radio signal to a receiver that controls an electronic lock. Typically, the action is to press a button on a physical fob or mobile app.

# Features
 * It will Lock the car when Button is pressed one time
 * It will Unlock the car when Button is pressed two time
 * It will activation/deactivation alarm when the Button is pressed three times
 * It will approach light when the Button is pressed four times

# High Level Requirements
|ID  | Description                                            |	
|:--:|:------------------------------------------------------:|
|HLR1| It should lock the car door.
|HLR2| It should unlock the car door.	
|HLR3| It alarm should ring for security purpose 	
|HLR4| The aproach light should glow.

                            
# Low Level Requirements
| ID |    Description                                                                                                                   
|:--:|:----------------------------------------------------------------------------------------------------------------------------------
|LLR1|Press blue button 1 time, All led ON at the same time and door is lock.
|LLR2|Press blue button 2 time, All led OFF at the same time and door is unlock.
|LLR3|Press blue button 3 time, All led  glows in clockwise manner  and alarm is activated.
|LLR4|Press blue button 4 time, All led glows in anticlockwise manner and aproach light glow.                                                                  
 

![1_Yf7Ku0L_P7wTaYJ4QCHxUw](https://user-images.githubusercontent.com/98872208/157809021-00eca78f-48f9-41b6-b145-8d0152f5bd8f.png)

# SWOT Analysis
   * Strength 
     * Optimized power and range and Advance security
   * Weakness
	   * Replacing a lost fob costs much more than a traditional key
	   * it consist of electronic components which may damge easly when drop on hard surface.
   * Opportunities
	   * allow users to use their smartphones as keys and we can controlling extra features like remote start from anywhere within range
   * Threats
	   * Thieves, however, are rising to the challenge, using radio transmitters to perform ‘relay’ car hacks to capture the signal from the car’s fob 
       possibility for hackers to manipulate the technology and steal your vehicle.
# 4W and 1H
  * Who : 
      *  One who is owner of the vehicle
  * What :
      *  Keyless entry systems are used to remotely lock, unlock,alarm and can have various features.
  * When :
      *  It will work within a range of distance a button is pushed, it sends a coded signal by radio waves to a receiver unit in the car, which locks or unlocks the door And            do the task require.
  * Why :
      *   Remote keyless entry systems alarm the vehicle against theft and lock and unlock the doors
  * How :
      *   Keyless entry to a vehicle is usually attained by sending a radio frequency signal from a remote transmitter to the receiver in the car.
     
#  Behavioural FlowChart

![Blank diagram](https://user-images.githubusercontent.com/98769359/157842463-6fba8b3f-9c44-4fa8-87d7-a09fd583887d.png)

# Structural diagram
![Blank diagram (3)](https://user-images.githubusercontent.com/98872208/157844431-cb8e04c1-fb6e-4dd3-b52b-2d7481b0f48d.png)


# Test Plan and Output

## High level test plan

| Test ID | Description | Input  |      Expected output | Actual output |
|---------:|:-----------:|:------------------:|:----------------:|:---------------|
| 01       | Lock        |  User presses button once | Lock the car | Lock the car |
| 02       | Unlock      | User presses button twice  | Unlock the car | Unlock the car |
| 03       | Alarm Activate / Deactivate |  User presses button three times | Activate or Deactivate alarm | Activate or Deactivate alarm |
| 04       | Approach light  |  User presses button four times | Turn on approach light | Turn on approach light |

## Low level test plan

| Test ID  | Description | Input |  Expected output | Actual output | Passed |
|------------:|:-----------------:|:----------------:|:-----------------:|:------------------:|:---------|
| 01 | check for lock | User presses button once | All LEDs should on | All LEDs should on | Pass |
| 02 | Check for unlock | User presses button twice | All LEDs should off | All LEDs should off | Pass |
| 03 | Check for alarm activate/deactivate | User presses button three times | LEDs should on clockwise | LEDs should on clockwise | Pass |
| 04 | Check for approach light | User presses button four times | LEDs should on anticlockwise |  LEDs should on anticlockwise | Pass|



