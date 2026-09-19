# Autonomous Delivery Bot for NERC

## Project Overview

An autonomous robotic system developed for the NERC competition to deliver dominoes to a designated blue target box.

The robot combines mechanical design, autonomous navigation, colour detection, servo-based aiming, and a domino launching mechanism to complete the delivery task.

## Main Mission

1. Preload dominoes into the robot.
2. Navigate the competition route autonomously using line-following control.
3. Detect the designated blue delivery box using a colour sensor.
4. Position the launching mechanism using servo motors.
5. Launch the domino into the blue box.
6. Complete the programmed autonomous sequence.

## Key Technologies

- Differential-drive mobile robot
- N20 DC geared motors
- IBT-2 motor drivers
- QTR-8A 8-channel line sensor
- TCS3200 colour sensor
- Servo motors for aiming
- Relay-controlled launching mechanism
- Arduino-based control
- PD line-following control
- Junction detection and state-machine navigation
- Mechanical design and FEA

## Mechanical Design

The robot chassis and mechanical components were designed and analyzed as part of the project.

Key analysis areas included:

- Shaft strength
- Fastener strength
- Motor bracket analysis
- Sensor bracket analysis
- Wheel analysis
- Chassis stress and deformation
- Factor of safety

## Autonomous Navigation

The robot uses a QTR-8A sensor for line detection and a PD control strategy for maintaining its path.

Junction detection and programmed navigation states allow the robot to follow the required competition route.

## Colour-Based Target Detection

A TCS3200 colour sensor is used to identify the blue delivery target.

The colour detection system uses RGB measurements and predefined ratios/thresholds to distinguish the target colour.

## Domino Delivery Mechanism

After detecting the blue target, two servo motors are used to position the launching mechanism.

A relay-controlled actuator then fires the domino toward the blue delivery box.

## Project Documentation

The detailed project report is available in this repository:

**Autonomous Delivery Bot for NERC – Detailed Project Report**

## Project Focus

This project integrates:

**Mechanical Design → Electronics → Control → Autonomous Navigation → Colour Detection → Targeting → Domino Delivery**
