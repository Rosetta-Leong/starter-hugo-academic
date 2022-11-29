---
title: Intelligent garbage sorting robot
summary: The First Prize of the National University Students’Opt-Sci-Tech Competition
tags:
  - Deep Learning
  - Robotics
date: "2021-08-31T00:00:00Z"

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
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://www.bilibili.com/video/BV1Uq4y1K755/?spm_id_from=333.999.0.0&vd_source=598adc8c235b2c61f220e1d6b1d27b93"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

We designed the optoelectronic intelligent garbage sorting vehicle, a four-wheeled omnidirectional motion system based on STM32 microcontroller control with a large field of view. It is equipped with a high-performance vision computing platform that uses deep learning to differentiate between garbage types and traditional vision to identify the location of garbage and the location of the stacking area. The vehicle is equipped with a simple and stable garbage capture device, which captures garbage by snapping it, takes it away by pushing it and puts it in the dumping area, and sorts five types of garbage into four different areas. A variety of high-precision sensors such as gyroscopes, encoders, laser distance measurement, and color sensors are used to assist the robot in its fully autonomous, accurate, and efficient trash identification, picking, sorting, and placement functions.

In this project, I was mainly responsible for the garbage recognition and classification part, i.e., the real-time deployment of the object detection algorithm on the embedded edge computing platform. By accelerating the YOLOv5 object detection algorithm with TensorRT, we finally achieved a balance of frame rate and accuracy on the hardware platform, which provided a reliable guarantee for the competition win. During this competition, I was responsible for all five algorithm deployment processes: dataset annotation, server environment setup, model training, deployment side environment setup, and model deployment and integration. During the process, I experienced the complexity and challenge of implementing the model, and the excellent performance of the algorithm eventually increased my interest and curiosity in the ever-changing field of deep learning, and ignited my desire to continue exploring in this field in graduate school.

This project won the first prize of the national university students’ opt-sci-tech Competition.
