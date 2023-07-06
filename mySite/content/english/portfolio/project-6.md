---
title: "RL on Tiny Robots"
date: 2023-05-10T12:14:34+06:00
image: "images/portfolio/Bittle.png"
categories: ["NVIDIA","machine learning"]
description: "This is meta description."
draft: false
project_info:
- name: "Project Website"
  icon: "fas fa-link"
  content: "https://coms-bc3997-sp23.github.io/website-habeeba-mansour/"
- name: "Github Link"
  icon: "fas fa-link"
  content: "https://github.com/A2R-Lab/TinyRobotsML"
---

This project focuses on the ongoing development of a
reinforcement learning model that results in the Petoi Bittle
learning to walk in a natural looking gait on an Isaac Sim
simulated environment. 

#### Project Details

This projects uses Isaac Sim as method for applying reinforcement learning to quadruped robot motion. Many of the necessary pipelines to begin training are completed and full scale deployment on Isaac Sim is still undergoing. There is motivation to test the performance of multiple RL algorithms to learn from the interaction with the environment and provide optimal control strategy. For preliminary testing, there were a few algorithms that stood out to test: 
* Soft Actor-Critic (SAC)
* Proximal Policy Optimization (PPO)
* Deep Deterministic Policy Gradient (DDPG)
* Trust Region Policy Optimization (TRPO)

This is an especially applicable tool in robot learning, an area that is at the intersection of ML and robotics. 

<figure class="video_container">
  <iframe src="https://www.youtube.com/embed/FeY6DwH4gxs" frameborder="0" allowfullscreen="true" width="730" height="440"> </iframe>
</figure>

