---
title: "Visual Affordance"
date: 2023-05-02T12:14:34+06:00
image: "images/portfolio/Robotics3.png"
categories: ["robotics","machine learning","GCP"]
description: "This is meta description."
draft: false
project_info:
- name: "Github Link"
  icon: "fas fa-link"
  content: "https://examplesite.com/"
---

Visual Affordance algorithm with labelled data implemented on robot arm to transfer unseen objects from one bin to another.


#### Project Details

Generated training dataset by labelling 5 training objects with 12 attempts each. To implement Visual Affordance the MiniUNet architecture is used. The gaussian score map used allows this model to perform well on unseen objects. The test time performance is also improved upon by picking a different pixel if the initial attempt is unsuccessful by suppressing the initial pixel and surrounding pixels. 
