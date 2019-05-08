---
layout: post
title: "Frame-wise Motion and Appearance for Real-time Multiple Object Tracking"
date: 2019-05-06 23:37:05
categories: arXiv_CV
tags: arXiv_CV Re-identification Tracking Object_Tracking Inference RNN
author: Jimuyang Zhang, Sanping Zhou, Jinjun Wang, Dong Huang
mathjax: true
---

* content
{:toc}

##### Abstract
The main challenge of Multiple Object Tracking (MOT) is the efficiency in associating indefinite number of objects between video frames. Standard motion estimators used in tracking, e.g., Long Short Term Memory (LSTM), only deal with single object, while Re-IDentification (Re-ID) based approaches exhaustively compare object appearances. Both approaches are computationally costly when they are scaled to a large number of objects, making it very difficult for real-time MOT. To address these problems, we propose a highly efficient Deep Neural Network (DNN) that simultaneously models association among indefinite number of objects. The inference computation of the DNN does not increase with the number of objects. Our approach, Frame-wise Motion and Appearance (FMA), computes the Frame-wise Motion Fields (FMF) between two frames, which leads to very fast and reliable matching among a large number of object bounding boxes. As auxiliary information is used to fix uncertain matches, Frame-wise Appearance Features (FAF) are learned in parallel with FMFs. Extensive experiments on the MOT17 benchmark show that our method achieved real-time MOT with competitive results as the state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.02292](https://arxiv.org/abs/1905.02292)

##### PDF
[https://arxiv.org/pdf/1905.02292](https://arxiv.org/pdf/1905.02292)

