# DAQ Setup and IMU Initialization

## Objective

The objective of this challenge was to install the measurement equipment
in the Mini Cooper and correctly initialize the DS-IMU-N1 inertial
navigation system before performing the subsequent measurement tasks.

## Measurement Setup

The vehicle was equipped with a Dewesoft DS-IMU-N1 inertial navigation
system together with the main data-acquisition system.

The IMU combines:
- accelerometers,
- gyroscopes,
- GNSS positioning,
- real-time sensor fusion

using a Kalman filter.

This provides information about the vehicle's position, orientation,
acceleration and motion.

## Installation

The IMU was rigidly mounted to the vehicle so that its motion corresponded
directly to the motion of the vehicle.

Important considerations included:
- correct alignment of the IMU coordinate axes,
- rigid mechanical mounting,
- suitable GNSS antenna placement,
- cable management,
- reliable power supply.

![DAQ setup](images/daq_setup.jpg)

## Power Supply

The measurement system was powered from the vehicle electrical system
using a DC/DC converter and a backup battery to maintain operation during
voltage drops.

![Power supply](images/power_supply.jpg)

## IMU Initialization

Before the measurements, the DS-IMU-N1 was initialized and its operation
was verified in DewesoftX.

Correct initialization was important because errors in the navigation
solution would propagate into the recorded measurement data.

## Result

The complete DAQ and navigation setup was successfully installed and
prepared for the subsequent vehicle measurement challenges.

[← Back to project overview](README.md)
