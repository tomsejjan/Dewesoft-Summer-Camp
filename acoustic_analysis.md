# Acoustic Analysis

## Objective

The objective of the acoustic challenge was to perform a practical
sound-level measurement on the Mini Cooper using a measurement microphone,
Dewesoft data-acquisition hardware, and the Sound Level Meter module
in DewesoftX.

The challenge provided hands-on experience with acoustic measurement,
microphone configuration, signal acquisition, and sound-pressure-level
analysis.

## Measurement Principle

A measurement microphone converts small variations in acoustic pressure
into an electrical signal. The signal is acquired by the DAQ system and
processed in DewesoftX.

Sound pressure level (SPL) is expressed logarithmically in decibels:

$$
L_p = 20 \log_{10}\left(\frac{p_\mathrm{RMS}}{p_0}\right)
$$

where:

- $p_\mathrm{RMS}$ is the RMS sound pressure,
- $p_0 = 20\ \mu\mathrm{Pa}$ is the reference sound pressure in air.

## Measurement Setup

The acoustic measurement chain consisted of:

- measurement microphone,
- Dewesoft data-acquisition hardware,
- DewesoftX,
- Sound Level Meter module.

The microphone signal was acquired simultaneously with the other
measurement channels available on the vehicle.

![Acoustic measurement setup](images/acoustic_setup.jpg)

## Sound Level Analysis

The Sound Level Meter module in DewesoftX was used to evaluate the
measured acoustic signal.

An important part of sound-level measurement is frequency weighting.
A-weighting can be applied to approximate the frequency-dependent
sensitivity of human hearing.

The acquired signal can therefore be evaluated both as a physical
pressure signal and in terms of its perceived sound level.

![Sound level measurement](images/acoustic_analysis.jpg)

## Practical Challenge

The measurement setup was used to characterize the noise produced by
the Mini Cooper under the specified test conditions.

This required the complete measurement chain to be correctly configured,
from the microphone and DAQ input to the sound-level analysis in
DewesoftX.

## What I Learned

The challenge provided practical experience with:

- measurement microphones,
- acoustic signal acquisition,
- sound pressure level (SPL),
- logarithmic representation in decibels,
- frequency weighting,
- Sound Level Meter configuration in DewesoftX,
- practical automotive noise measurement.

[← Back to project overview](README.md)
