---
layout: post
title: "Forecasting Time-to-Collision from Monocular Video: Feasibility, Dataset, and Challenges"
date: 2019-08-09 15:26:47
categories: arXiv_RO
tags: arXiv_RO CNN Deep_Learning Prediction Detection
author: Aashi Manglik, Xinshuo Weng, Eshed Ohn-Bar, Kris M. Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the possibility of using a single monocular camera to forecast the time to collision between a suitcase-shaped robot being pushed by its user and other nearby pedestrians. We develop a purely image-based deep learning approach that directly estimates the time to collision without the need of relying on explicit geometric depth estimates or velocity information to predict future collisions. While previous work has focused on detecting immediate collision in the context of navigating Unmanned Aerial Vehicles, the detection was limited to a binary variable (i.e., collision or no collision). We propose a more fine-grained approach to collision forecasting by predicting the exact time to collision in terms of milliseconds, which is more helpful for collision avoidance in the context of dynamic path planning. To evaluate our method, we have collected a novel dataset of over 13,000 indoor video segments each showing a trajectory of at least one person ending in a close proximity (a near collision) with the camera mounted on a mobile suitcase-shaped platform. Using this dataset, we do extensive experimentation on different temporal windows as input using an exhaustive list of state-of-the-art convolutional neural networks (CNNs). Our results show that our proposed multi-stream CNN is the best model for predicting time to near-collision. The average prediction error of our time to near collision is 0.75 seconds across the test videos.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09102](http://arxiv.org/abs/1903.09102)

##### PDF
[http://arxiv.org/pdf/1903.09102](http://arxiv.org/pdf/1903.09102)

