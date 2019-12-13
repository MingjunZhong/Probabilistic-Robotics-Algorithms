# SLAM Algorithm Implementation - Probabilistic Robotics
#### Chenge Yang, 2019 Winter, Northwestern University
-----------------------------------------------------------------------------------------
## 1. Introduction
This project contains Python3 implementations and results of a variety of state estimation and SLAM algorithms in Sebastian Thrun's book Probabilistic Robotics  using UTIAS Multi-Robot Cooperative Localization and Mapping Dataset.

As a beginner in SLAM, I always found it difficult to understand the non-intuitive mathematical equations, and I can barely find straightforward instructions on implementing these algorithms. Therefore, I created this repo to demonstrate the basic concepts behind the book, paired with results running on a simple dataset.

If you are new to SLAM problem and is reading the book Probabilistic Robotics, this repo will be perfect for you - I programmed in Python not C++ with abundant inline comments and good demonstrations of the results.

If you find anything wrong with my implementations, such as wrong understanding or code bugs, please leave a comment!

#### Table of Contents
- [1. Introduction](#1-Introduction)
- [2. Dataset](#2-Dataset)
- [3. Localization](#3-Localization)
  - [3.1. EKF Localization](#31-EKF-Localization)
  - [3.2. Particle Filter Localization](#32-Particle-Filter-Localization)
- [4. EKF SLAM](#4-EKF-SLAM)
  - [4.1. EKF SLAM with Known Correspondence](#41-EKF-SLAM-with-Known-Correspondence)
  - [4.2. EKF SLAM with Unknown Correspondence](#42-EKF-SLAM-with-Unknown-Correspondence)
- [5. Graph SLAM](#5-Graph-SLAM)
  - [5.1. Graph SLAM with Known Correspondence](#51-Graph-SLAM-with-Known-Correspondence)
- [6. Fast SLAM 1](#6-Fast-SLAM-1)
  - [6.1. Fast SLAM 1 with Known Correspondence](#61-Fast-SLAM-1-with-Known-Correspondence)
  - [6.2. Fast SLAM 1 with Unknown Correspondence](#62-Fast-SLAM-1-with-Unknown-Correspondence)
- [7. Fast SLAM 2](#7-Fast-SLAM-2)
  - [7.1. Fast SLAM 2 with Unknown Correspondence](#71-Fast-SLAM-2-with-Unknown-Correspondence)
-----------------------------------------------------------------------------------------
## 2. Dataset
<p align = "center">
  <img src = "doc/Odometry.png" height = "360px" style="margin:10px 10px">
</p>
-----------------------------------------------------------------------------------------
## 3. Localization

### 3.1. EKF Localization
<p align = "center">
  <img src = "doc/EKF_Localization_known_correspondences.png" height = "360px" style="margin:10px 10px">
</p>
### 3.2. Particle Filter Localization
<p align = "center">
  <img src = "doc/PF_Localization_known_correspondences.gif" height = "360px" style="margin:10px 10px">
</p>
-----------------------------------------------------------------------------------------
## 4. EKF SLAM

### 4.1. EKF SLAM with Known Correspondence
<p align = "center">
  <img src = "doc/EKF_SLAM_known_correspondences.gif" height = "360px" style="margin:10px 10px">
</p>
### 4.2. EKF SLAM with Unknown Correspondence
<p align = "center">
  <img src = "doc/EKF_SLAM_unknown_correspondences.gif" height = "360px" style="margin:10px 10px">
</p>
-----------------------------------------------------------------------------------------
## 5. Graph SLAM

### 5.1. Graph SLAM with Known Correspondence
<p align = "center">
  <img src = "doc/Graph_SLAM_known_correspondences.png" height = "360px" style="margin:10px 10px">
</p>
-----------------------------------------------------------------------------------------
## 6. Fast SLAM 1

### 6.1. Fast SLAM 1 with Known Correspondence
<p align = "center">
  <img src = "doc/Fast_SLAM_1_known_correspondences.gif" height = "360px" style="margin:10px 10px">
</p>
### 6.2. Fast SLAM 1 with Unknown Correspondence
<p align = "center">
  <img src = "doc/Fast_SLAM_1_unknown_correspondences.gif" height = "360px" style="margin:10px 10px">
</p>
-----------------------------------------------------------------------------------------
## 7. Fast SLAM 2

### 7.1. Fast SLAM 2 with Unknown Correspondence
<p align = "center">
  <img src = "doc/Fast_SLAM_2_unknown_correspondences.gif" height = "360px" style="margin:10px 10px">
</p>
-----------------------------------------------------------------------------------------
