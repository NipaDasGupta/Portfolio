---
title: Project I
summary: Detect Driver Drowsiness Face Expression Using Convolutional Neural Networks.
tags:
  - deep Learning
date: '2021-10-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by Nipa
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/nipa_das_gupta/status/1544613920434171904
url_code: https://github.com/NipaDasGupta/DrowsinessDetection
url_pdf: https://drive.google.com/file/d/1htvj1831e5e6gS9CmRm2sp6Q-7VRsb-I/view?usp=sharing
url_slides: 'https://docs.google.com/presentation/d/1ArsuSQyBqu8DCzIm1v86Vn44eKfQJ8RR/edit?usp=sharing&ouid=100227760510168348656&rtpof=true&sd=true'
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

This project is a deep learning object detection problem that aims to predict if a driver is in a drowsy or awake state to avoid fatal and serious accidents in real-time for driver health and safety. Several deep learning models were trained for this project and the SSD MobileNet V2 had the best performance among the model trained.

The following task were carried out in this project:

+ Utilized Python to develop an supervised deep learning drowsiness detection system model using techniques such as SSD MobileNet V2 FPNLite 320x320 algorithm for detecting the facial key attributes as fatigue

+ To predict drowsy driver using a detection box by combining the features of the facial expression on 1.83 GB of the unstructured dataset using TensorFlow Object Detection API, which accomplished total precision & recall by approximately 88%

+ Training and testing were implemented on Jupyter Notebook
