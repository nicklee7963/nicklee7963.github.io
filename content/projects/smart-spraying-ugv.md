---
title: "Smart Spraying UGV"
date: 2026-01-21
description: "An autonomous ground vehicle using Computer Vision for precision agriculture."
tags: ["Robotics", "ROS2", "Computer Vision", "Python"]
weight: 10
---

## Project Overview
This project aims to develop an **Unmanned Ground Vehicle (UGV)** capable of detecting crops and performing targeted spraying to reduce pesticide usage.

### 🛠️ Technology Stack
* **Hardware:** Arduino, Jetson Nano, Custom 3D Printed Chassis
* **Software:** ROS2 (Robot Operating System), Python, OpenCV
* **Algorithms:** Color segmentation for crop detection, PID Control for navigation

### 🎥 Demo
*(未來這裡可以放你的 YouTube 影片連結)*

### 🚧 Challenges & Solutions
**Challenge:** The vehicle struggled to move straight on uneven terrain.
**Solution:** Implemented a **PID controller** using the MPU6050 IMU sensor to correct the heading error in real-time.
