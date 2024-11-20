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

### Required Downloads and Installations

List any required downloads and installations here.
Make sure to include tutorials on how to install them.
You can either make your own tutorials or include a link to them.

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

## Part 01: Name

### Introduction

Briefly introduce what  you are teaching in this section.

### Objective

- List the learning objectives of this section

### Background Information

Give a brief explanation of the technical skills learned/needed
in this challenge. There is no need to go into detail as a
separation document should be prepared to explain more in depth
about the technical skills

### Components

- List the components needed in this challenge

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
