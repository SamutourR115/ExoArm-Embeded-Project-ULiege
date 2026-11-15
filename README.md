# ExoArm

Wearable exoskeleton arm for real-time teleoperation of a custom 6-DOF robot arm.
Embedded Systems course project — University of Liège.

## Overview

ExoArm captures the motion of the operator's arm and reproduces it in real time
on a small robot arm designed from scratch.

- **Motion capture**: two IMUs (shoulder and elbow) and flex sensors for the hand
- **Robot arm**: 6 degrees of freedom (3 shoulder, 1 elbow, 2 hand) with a gripper
- **Firmware**: bare-metal, written entirely in assembly on [MCU]
- **Mechanics**: 3D-printed parts, STL files available in this repository

## Repository structure

```
firmware/     Assembly source code
mechanical/   3D models (STL)
docs/         Reports, diagrams and photos
```

## Status

🚧 Work in progress. A custom PCB is planned after the proof of concept.

## Team

- Samuel Mastroscianni — maintainer
- Morgan Phemba
- Romain Christiaens

## License

To be defined.
