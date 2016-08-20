---
layout: page
title: System Design
---

### Overview

Most science projects will require you to build a device to gather data for testing your project's hypothesis. This device can be quite complex and will often comprise of components each playing a specific role to the success of the overall system.

After you have defined your hypothesis and the data required, it's critical to define the system required with each of these subcomponents which will help you gather that data. This will guide for a plan to complete the project, the materials required, and overall procedures. 

This definition includes the following:

1. Device objectives 
2. Operating requirements
3. Procedures for testing the device to ensure it meets the requirements
4. Device sub-components
    * Objective of that subcomponents
    * Requirement
    * Procedure for testing each sub-component
    
### Example - earthquake detector

Suppose that your hypthesis calls for building a remote-sensing earthquake detector to p-waves and send a communication to you when an earthquake event occurs. Here is an example of the device objectives, requirements, procedures for testing, and required sub-systems. 

1. Objectives
    * Ability to detect a earthquake p-waves (surface waves @ 10Hz)

2. Operating Requirements
    * An automated way to capture the earthquake waves and transmit scientific data
    * Need local processing to filter out environmental noise
    * Device must remain operable in the field 24x7 for at least 30 days
    * Package which will keep system free from environmental damage (water, wind, sun, pests, etc..)
    * Package located in "low-noise" location
    * Package located in spot which allows GPRS data connection

3. Procedure for testing
    * Obtain source that can generate 10Hz p-waves and validate that device can detect.
    * Monitor USGS earthquake detection and compare results to your earthquake detector.

4. Required sub-systems
    * Probe to detect 10hz waves
    * Local storage to capture details of the earthquake event
    * Microcontroller to process and store p-wave data
    * GPRS compatible processor with antennea to wirelessly communicate data
    * Website to receive data and store results
    * Battery and Solar Panel charging system 
    * An enclosure to protect the device from environmental harm


