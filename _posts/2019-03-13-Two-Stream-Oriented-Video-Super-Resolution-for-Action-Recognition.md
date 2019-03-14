---
layout: post
title: "Two-Stream Oriented Video Super-Resolution for Action Recognition"
date: 2019-03-13 16:22:36
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Action_Recognition CNN Recognition
author: Haochen Zhang, Dong Liu, Zhiwei Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
We study the video super-resolution (SR) problem not for visual quality, but for facilitating video analytics tasks, e.g. action recognition. The popular action recognition methods based on convolutional networks, exemplified by two-stream networks, are not directly applicable on videos of different spatial resolutions. This can be remedied by performing video SR prior to recognition, which motivates us to improve the SR procedure for recognition accuracy. Tailored for two-stream action recognition networks, we propose two video SR methods for the spatial and temporal streams respectively. On the one hand, we observe that the added details by image SR methods can be either helpful or harmful for recognition, and we propose an optical-flow guided weighted mean-squared-error loss for our spatial-oriented SR (SoSR) network. On the other hand, we observe that existing video SR methods incur temporal discontinuity between frames, which also worsens the recognition accuracy, and we propose a siamese network for our temporal-oriented SR (ToSR) that emphasizes the temporal continuity between consecutive frames. We perform experiments using two state-of-the-art action recognition networks and two well-known datasets--UCF101 and HMDB51. Results demonstrate the effectiveness of our proposed SoSR and ToSR in improving recognition accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05577](http://arxiv.org/abs/1903.05577)

##### PDF
[http://arxiv.org/pdf/1903.05577](http://arxiv.org/pdf/1903.05577)

