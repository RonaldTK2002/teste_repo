# Technical Report  
## Jackal Operations

### Ronaldo Dutra, Camila Chagas, Vitor Ortega, and Manuela Moura

**Computer Science Graduate Program**  
**Federal University of Minas Gerais**  
**Belo Horizonte, Brazil**

---

## Abstract

This is a report on the in-laboratory Jackal tests concerning safety and battery issues.

## Keywords

Battery, Safety, Robot

---

## Introduction

In this task, we have manually operated Jackal to ensure that it is properly working and to learn about its safety mechanisms.

## Methodology

### Batteries

Four Lithium-ion batteries labeled from \#1 to \#4 are available for use with some concerns:

- **\#1**. This is a 24 V battery with 264 Wh energy and 11.6Ah capacity. Unfortunately, it is not charging correctly, so it is recommended not to use it.
- **\#2, \#3, and \#4**. These are 26 V batteries with 302 Wh energy and 11.6Ah capacity. All of them are working perfectly, being able to fully charge (4 hours charging time using the Clearpath battery charger) and fully discharge (2-8 hours depending on the use).

*To be able to maintain the batteries' health, it is recommended to store them with approximately 80% capacity and not to fully discharge them.*

### Robot

A general test of the robot was conducted, checking the Human-Machine Interface indicators and buttons. A teleoperated ride was also conducted, ensuring that the motors and MCU are operating correctly. Some observations are listed below:

- It was expected to find an override button; however, the Motor Stop Button implemented on Jackal's interface should not be the only safety option to stop the robot due to the difficulty of reaching it while the robot is moving.
- Jackal can reach high speeds, so every test ride should be conducted in clear areas and with a safe human-robot distance.

## Conclusion

It is expected that a safer override motor button will be developed, which is bigger and easier to reach. Additionally, the \#1 battery needs to be fixed so that it can charge properly.

---

## References
[Jackal user manual](https://docs.clearpathrobotics.com/docs/robots/outdoor_robots/jackal/user_manual_jackal/)
