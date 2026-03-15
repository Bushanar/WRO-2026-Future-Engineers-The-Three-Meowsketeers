# WRO-2026-Future-Engineers-The-Three-Meowsketeers

## Team Members

>Coach
- [Baganj Igor]
>Members
- [Selymesi Arnold] – Electronics and Integration
- [Balázs Piri Ede] – Software Development
- [Csőke Olivér] – Mechanical Design

## Project Overview

This repository documents the development of our autonomous robot for the Future Engineers category of the World Robot Olympiad. The goal of the project is to design a robot capable of navigating the competition track autonomously while reacting to obstacles and changes in the environment.

As the project progresses, this repository will contain the engineering documentation, design files, software, and testing results related to the development of the robot.

---

## Robot Idea

Our robot is designed to complete a full loop around the competition track while making correct navigation decisions. Because the track does not contain continuous guiding lines, the robot cannot rely on traditional line-following methods.

Instead, our main navigation strategy is based on maintaining a stable distance from the outer wall using distance sensors. This allows the robot to follow the shape of the track and remain stable while moving.

The robot will also use a front-facing color sensor to detect the colored poles placed on the track. When a pole is detected, the robot will decide which direction to turn in order to avoid it and then return to its normal navigation mode.

The robot will use two distance sensors, one color sensor, and two motors in a differential drive configuration. The mechanical design will be slim and lightweight to allow fast and stable movement through the track.

---

## Engineering Journal

The full engineering documentation describing the development process, design decisions, and testing will be included in the Engineering Journal.

Location in this repository:

[Engineering Journal v1](engineering_journal/engineering_journal_v1.pdf)

Future versions will include additional design iterations, testing results, and improvements made during development.

---

## Repository Structure

```
engineering_journal
mechanical
electronics
software
diagrams
images
```

Each folder will contain documentation and files related to that subsystem as the project develops.

---

## Project Status

**Current Stage:** Concept and Planning

**Next Steps:**

1. Develop the first mechanical design of the robot
2. Select electronic components and sensors
3. Design the initial software architecture
4. Build and test the first prototype
