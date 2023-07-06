---
title: "Robot Grasp Pipeline"
date: 2023-04-26T12:14:34+06:00
image: "images/portfolio/Robotics2.png"
categories: ["robotics", "machine learning", "GCP"]
description: "This is meta description."
draft: false
project_info:
- name: "Github Link"
  icon: "fas fa-link"
  content: "https://github.com/HabeebaMansour/robot-grasping"
---

RRT algorithm implemented for path planning to move the robot from one location to another while avoiding collisions with obstacle.


#### Project Details

The pipeline for the project is as follows: 
* train segmentation network
* predict segmentation mask
* generate point cloud of objects
* use ICP to align the original object to the segmented object point cloud
* grasp object
* transfer to other bin using RRT while avoiding collisions

