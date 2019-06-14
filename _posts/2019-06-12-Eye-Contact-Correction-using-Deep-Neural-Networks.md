---
layout: post
title: "Eye Contact Correction using Deep Neural Networks"
date: 2019-06-12 21:15:12
categories: arXiv_CV
tags: arXiv_CV CNN
author: Leo F. Isikdogan, Timo Gerasimow, Gilad Michael
mathjax: true
---

* content
{:toc}

##### Abstract
In a typical video conferencing setup, it is hard to maintain eye contact during a call since it requires looking into the camera rather than the display. We propose an eye contact correction model that restores the eye contact regardless of the relative position of the camera and display. Unlike previous solutions, our model redirects the gaze from an arbitrary direction to the center without requiring a redirection angle or camera/display/user geometry as inputs. We use a deep convolutional neural network that inputs a monocular image and produces a vector field and a brightness map to correct the gaze. We train this model in a bi-directional way on a large set of synthetically generated photorealistic images with perfect labels. The learned model is a robust eye contact corrector which also predicts the input gaze implicitly at no additional cost. Our system is primarily designed to improve the quality of video conferencing experience. Therefore, we use a set of control mechanisms to prevent creepy results and to ensure a smooth and natural video conferencing experience. The entire eye contact correction system runs end-to-end in real-time on a commodity CPU and does not require any dedicated hardware, making our solution feasible for a variety of devices.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05378](https://arxiv.org/abs/1906.05378)

##### PDF
[https://arxiv.org/pdf/1906.05378](https://arxiv.org/pdf/1906.05378)

