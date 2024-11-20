---
title: Battery Indicator with ESP32
date: 2024-11-20
authors:
  - name: Andy Tu
  - name: Madeline Fruin
  - name: Will Luong
---

![relevant graphic or workshop logo](image/path)

## Introduction

Write a short section on what the tutorial is aiming to accomplish.
What is the motivation behind the tutorial?
What do you want readers to gain from the tutorial?

This tutorial will teach readers how to use ESP32's ADC pins to measure a battery's charge. Since the ADC pins can take in a max of 3.3V, we will be covering how to implement a voltage divider to lower the maximum voltage of a battery to an amount allowed by the ESP32. For the coding section, we will use the Arduino IDE to write code that will read, display, and convert the battery readings to a charge percentage using a custom library.

### Learning Objectives

- Voltage Dividers
- ESP32 ADC/GPIO Pins
- Arduino C
- Battery Charge State

### Background Information

Describe your topic here. What does it do? Why do you use it?
Are there other similar things to use? What are the pros and cons?
Explain important concepts that are necessary to understand.
Include (and cite if needed) any visuals that will help the audience understand.

## Getting Started

For any software prerequisites, write a simple excerpt on each
technology the participant will be expecting to download and install.
Aim to demystify the technologies being used and explain any design
decisions that were taken. Walk through the installation processes
in detail. Be aware of any operating system differences.
For hardware prerequisites, list all the necessary components that
the participant will receive. A table showing component names and
quantities should suffice. Link any reference sheets or guides that
the participant may need.
The following are stylistic examples of possible prerequisites,
customize these for each workshop.

You will receive an ESP32 board and USB-C to USB-C connector cable. The ESP32 is (INSERT BASIC DESCRIPTION HERE). We will be using it very simply, you do not need to understand everything it can do for this tutorial.

We will be using the Arduino IDE.  

### Required Downloads and Installations

List any required downloads and installations here.
Make sure to include tutorials on how to install them.
You can either make your own tutorials or include a link to them.

If you don't have the Arduino IDE already, download it <a href="https://www.arduino.cc/en/software"><here>here.</a>

You will also need to install the Pangodream Arduino Library. This can be found in the lefthand bar of your Arduino IDE under add-ons. Or, you can download it <a href="https://github.com/pangodream/18650CL"><here>here.</a>

### Required Components

List your required hardware components and the quantities here.

| Component Name | Quanitity |
| -------------- | --------- |
|     ESP32      |     1     |
|Resistors (47kΩ)|     2     |
| 18650 Battery  |     1     |
| Battery Holder |     1     |
|  Breadboard    |     1     |
| Jumper Cables  |     2     |


### Required Tools and Equipment

Computer, Arduino IDE, Cable to connect ESP32 to your computer

## Part 01: Setting up the Circuit

### Introduction

In this section, we will be discussing the voltage divider and circuit setup. We will not be writing any code, so a computer is not needed yet.

### Objective

- To understand how to pick values for a voltage divider
- How to properly connect the battery, resistors, and ESP32.

### Background Information

Give a brief explanation of the technical skills learned/needed
in this challenge. There is no need to go into detail as a
separation document should be prepared to explain more in depth
about the technical skills

### Components

- Breadboard
- Battery and Battery Holder
- Resistors
- ESP32
- Jumper Cables

### Instructional

Teach the contents of this section

## Part 02: Writing the Code

### Introduction

In this section, we will be discussing the voltage divider and circuit setup. We will not be writing any code, so a computer is not needed yet.

### Objective

- To understand how to pick values for a voltage divider
- How to properly connect the battery, resistors, and ESP32.

### Background Information

Give a brief explanation of the technical skills learned/needed
in this challenge. There is no need to go into detail as a
separation document should be prepared to explain more in depth
about the technical skills

### Components

- Breadboard
- Battery and Battery Holder
- Resistors
- ESP32
- Jumper Cables

### Instructional

Teach the contents of this section

## Example

### Introduction

Introduce the example that you are showing here.

### Example

Present the example here. Include visuals to help better understanding

### Analysis

Explain how the example used your tutorial topic. Give in-depth analysis of each part and show your understanding of the tutorial topic

## Additional Resources

### Useful links

List any sources you used, documentation, helpful examples, similar projects etc.
