---
layout: post
title: "CRAVES: Controlling Robotic Arm with a Vision-based Economic System"
date: 2019-07-02 13:26:04
categories: arXiv_CV
tags: arXiv_CV Attention Pose_Estimation Reinforcement_Learning Optimization Recognition
author: Yiming Zuo, Weichao Qiu, Lingxi Xie, Fangwei Zhong, Yizhou Wang, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Training a robotic arm to accomplish real-world tasks has been attracting increasing attention in both academia and industry. This work discusses the role of computer vision algorithms in this field. We focus on low-cost arms on which no sensors are equipped and thus all decisions are made upon visual recognition, e.g., real-time 3D pose estimation. This requires annotating a lot of training data, which is not only time-consuming but also laborious. 
 In this paper, we present an alternative solution, which uses a 3D model to create a large number of synthetic data, trains a vision model in this virtual domain, and applies it to real-world images after domain adaptation. To this end, we design a semi-supervised approach, which fully leverages the geometric constraints among keypoints. We apply an iterative algorithm for optimization. Without any annotations on real images, our algorithm generalizes well and produces satisfying results on 3D pose estimation, which is evaluated on two real-world datasets. We also construct a vision-based control system for task accomplishment, for which we train a reinforcement learning agent in a virtual environment and apply it to the real-world. Moreover, our approach, with merely a 3D model being required, has the potential to generalize to other types of multi-rigid-body dynamic systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00725](http://arxiv.org/abs/1812.00725)

##### PDF
[http://arxiv.org/pdf/1812.00725](http://arxiv.org/pdf/1812.00725)

