---
layout: post
title: "Learning by Inertia: Self-supervised Monocular Visual Odometry for Road Vehicles"
date: 2019-05-05 08:58:35
categories: arXiv_CV
tags: arXiv_CV CNN RNN SLAM
author: Chengze Wang, Yuan Yuan, Qi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present iDVO (inertia-embedded deep visual odometry), a self-supervised learning based monocular visual odometry (VO) for road vehicles. When modelling the geometric consistency within adjacent frames, most deep VO methods ignore the temporal continuity of the camera pose, which results in a very severe jagged fluctuation in the velocity curves. With the observation that road vehicles tend to perform smooth dynamic characteristics in most of the time, we design the inertia loss function to describe the abnormal motion variation, which assists the model to learn the consecutiveness from long-term camera ego-motion. Based on the recurrent convolutional neural network (RCNN) architecture, our method implicitly models the dynamics of road vehicles and the temporal consecutiveness by the extended Long Short-Term Memory (LSTM) block. Furthermore, we develop the dynamic hard-edge mask to handle the non-consistency in fast camera motion by blocking the boundary part and which generates more efficiency in the whole non-consistency mask. The proposed method is evaluated on the KITTI dataset, and the results demonstrate state-of-the-art performance with respect to other monocular deep VO and SLAM approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01634](http://arxiv.org/abs/1905.01634)

##### PDF
[http://arxiv.org/pdf/1905.01634](http://arxiv.org/pdf/1905.01634)

