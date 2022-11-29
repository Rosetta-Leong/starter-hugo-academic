---
title: Intelligent tour guide robot
summary: National Undergraduate Training Program for Innovation and Entrepreneurship
tags:
  - Robotics
date: "2021-05-14T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: Photo by rawpixel on Unsplash
  # focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: "https://github.com/Rosetta-Leong/ROS_Voice_Goal"
url_pdf: ""
url_slides: ""
url_video: "https://www.bilibili.com/video/BV1fL411W77s/?spm_id_from=333.999.0.0&vd_source=598adc8c235b2c61f220e1d6b1d27b93"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This project is based on the cartographer_ros open source framework, using 2D LiDAR to build a map of unknown environments, and using rapid exploration random tree (RRT) and elastic time band (teb_local_planner) as navigation algorithms to achieve the goal of intelligent robots with the ability to automatically guide visitors in unknown environments such as school history museums and museums. It will also be further expanded for its voice function to communicate with visitors and give timely answers to achieve intelligent voice interaction.

Based on the study of machine vision for mobile robot navigation technology, the overall scheme and hardware and software design of the tour guide robot control system are briefly introduced based on the hierarchical structure. The robot is able to automatically avoid obstacles and stop at the target point in a structured road environment, and to provide visitors with a guided tour.

The innovation of this project is that the cartographer_ros is an open-source simultaneous localization and mapping (SLAM) algorithm, and the hardware solution is LIDAR, which fits the professional background and mature solutions in industry. As the most interactive and practical core technology in the field of artificial intelligence, intelligent speech recognition has a great prospect in smart home and smart driving. In addition, this project needs to use the elastic time band algorithm (teb_local_planner) to solve the specific problems of how to autonomously plan the travel route of intelligent robots and how to avoid obstacles, which is a key technology in the direction of the popular autonomous driving nowadays, thus the project is very innovative and practical.

Traditional path planning does not explicitly incorporate the temporal and dynamical aspects of motion, and therefore ignores the temporal and dynamical aspects of motion or dynamic motion. The constraints imposed by a model with limited speed and acceleration are therefore ignored. To address this situation, the time-elastic band algorithm is introduced into the local path The temporal elastic band algorithm is introduced into the local path optimization to effectively optimize the dynamical constraints on the robot trajectory while explicitly incorporating temporal information to ensure that the target point is reached in the shortest possible time, ensuring that the robot can be reached in the shortest possible time. This ensures the rapidity of mobile robot navigation by explicitly incorporating time information to ensure that the target point is reached in the shortest possible time.

This project was approved as a “National Undergraduate Training Program for Innovation and Entrepreneurship”
