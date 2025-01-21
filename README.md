[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/UwCBxwld)
# project1-template
Making a heartbeat LED with delay loops and timers


# EELE 465: Project 1 - Heartbeat LED Implementation Report

This repository contains my implementation of the "heartbeat" LED indicator project for the MSP-EXP430FR2355 Launchpad Evaluation Board. I successfully created two independently controlled LEDs flashing at 0.5 Hz using assembly language, implementing both delay loop and timer interrupt approaches.

## Project Results

I achieved the following requirements:
- Implemented two LEDs flashing at exactly 0.5 Hz (1 second on, 1 second off)
- Created modular, reusable code in assembly language
- Verified timing accuracy using oscilloscope measurements
- Successfully demonstrated both implementation methods

## Implementation Details

### 1. Delay Loop Method (P1.0 LED)
![alt text](Project01-flowchart1.png)


#### Timing Results

![alt text](IMG_0556.HEIC)

### 2. Timer Interrupt Method (P6.6 LED)

#### Flowchart
![alt text](Project01-flowchart2.png)


#### Timing Results
![alt text](IMG_0557.HEIC)
