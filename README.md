# Proximity-Based-Message-Broadcast-System
The "Proximity Based Message Broadcast System" is an embedded system designed to detect proximity and broadcast messages wirelessly upon detection. 

# Project Explanation

The main objective of this project is to create an embedded system that uses an Ultrasonic Sensor with the STM32L475 microcontroller to detect objects within a 1-meter range. When an object is detected, the system wirelessly sends a message. This system accurately measures proximity in real-time and transmits the data to a mobile app, which shows the distance of the detected object. Additionally, an LED indicator will blink when an object is within the 1-meter range, providing an immediate visual alert. The hardware uses the low power modes for the implementation of the project task. 

This system utilizes an STM32L475VGT6 microcontroller and an Ultrasonic Sensor HC-SR04 to meet critical communication needs in applications such as security, smart environments, and asset tracking. The STM32 microcontroller, based on the ARM Cortex-M processor core, offers high-performance processing and low power consumption, making it suitable for real-time applications.

# Software & Tools Used

The software and tools used in this project are as follows:

•	STM32CubeIDE

Integrated Development Environment (IDE) specifically designed for STM32 microcontrollers, providing a comprehensive set of tools for development, and debugging.

•	STM32CubeHAL

It is a set of hardware abstraction libraries provided by STMicroelectronics for STM32 microcontrollers, facilitating the development process.

•	Timer Interrupts

Utilized to manage the timing operations within the microcontroller, enabling precise control and scheduling of tasks such as sensor readings and message broadcasting.
