# Wiggles — Autonomous Object Retrieval Robot

Wiggles is an ESP32-controlled autonomous robot developed as part of a group mechatronics design project.

The robot was designed to identify, collect, return, and sort valuable erasers within a 120-second time limit.

## My Contributions

My main contributions were:

- Designing and prototyping the object-retrieval claw
- Working on the scoop-lifting mechanism
- Writing the robot-control code
- Integrating and testing the retrieval system

The claw used an N20 DC motor for extension and retraction, with an SG90 servo controlling its angle. The lifting mechanism used an MG996R servo and lever arm to raise the scoop and transfer collected objects into the sorting system.

## Project Features

- ESP32/MSEduino control system
- Autonomous drivetrain
- Encoder-based return-to-base movement
- Motor-driven collection claw
- Servo-actuated lifting mechanism
- Colour-based sorting system
- Iterative mechanical prototyping and testing

## Results

The final prototype completed the demonstration in approximately **60 seconds**, within the required 120-second limit.

The robot successfully operated autonomously, returned to base, lifted the scoop, and sorted target objects. Collection repeatability—particularly the transfer from the scoop into the sorting funnel—remained an area for improvement.

## Demonstration

[Watch the full test run](https://youtu.be/EpNwdiVKVe4)

<!--![Wiggles robot](media/photos/wiggles-overview.jpg)-->

## Repository Contents

```text
cad/             CAD files for the claw and lifting mechanism
media/           Photos and demonstration videos
prototypes/      Prototype development files
src/             Relevant robot-control code
docs/            Additional project documentation
