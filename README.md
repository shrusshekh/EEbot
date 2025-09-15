# EEbot Navigation Maze
# Microcontroller Navigation Project – HC12 Microcontroller
Toronto Metropolitan University
Course: COE538 – Microprocessor Systems
Group Project

This project programs an Eebot robot with a navigation system to move through a maze, performing functions such as moving forwards, backwards, reverse, and turning. 

## Main Features
1. The robot is started at the entry point and tracks down the guidance line.
2. The robot must navigate the S turns to demonstrate that the guidance algorithm is working correctly.
3. Whenever the eebot encounters a junction, it should make a decision which branch to take.
4. If the branch comes to a dead end, the robot will encounter a barrier that actuates the front bumper. It should then execute a 180 degree turn, retrace the path, and take the other branch. It should also note that the branch taken was the incorrect one, and note the correct branch.
5. If the robot does not encounter a dead end on that path, it should remember that the branch it chose was the correct one.
6. This process continues until the robot reaches the maze forward destination point. The operator taps the rear bumper to indicate this to the robot.

## Key Files

- `main.asm` – Core assembly program
- `derivative.inc` – MCU register definitions
- `Full_Chip_Simulation.ini` – Project and simulator config 

## Tools

- CodeWarrior for HC12 microcontroller board and Eebot

## Run

This project is intended for use within CodeWarrior. Use the provided `.mcp` and `.ini` files to simulate execution.


