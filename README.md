# WRO-2026-Future-Engineers-MASAAR-VISION
MASAAR VISION | WRO 2026 Future Engineers - Autonomous Vehicle   
<p align="center">
  <img src="MASAAR%20VISION.jpeg" width="300">
</p>

# MASAAR VISION

Hi! We are **MASAAR VISION**, a team participating in the WRO 2026 Future Engineers challenge.

Our project is a self-driving car that can move around the WRO track without remote control. Our goal is to make the car complete three laps, detect the red and green traffic signs, avoid them from the correct side, and finally park by itself.

## Our Car

We decided to build our own chassis because we wanted the car to be small, strong and easy to modify.

Our current design uses:
- ESP32 as the main controller
- MG90S servo for steering
- One DC motor for driving the rear wheels
- HuskyLens camera for detecting colors and traffic signs
- MPU6050 for measuring turns and direction
- VL53L0X distance sensors around the car

We are still building and testing the car, so some parts may change after our tests.

## How We Are Developing It

We did not start with the final car immediately.

First, we designed the chassis and steering system. Then we started testing the parts we already had in our lab. Because some of our final components had not arrived yet, we also planned to use temporary parts to test the electronics and programming.

Every time we find a problem, we test a solution and record what happened. We will add these tests and changes to this repository as we continue building the car.
