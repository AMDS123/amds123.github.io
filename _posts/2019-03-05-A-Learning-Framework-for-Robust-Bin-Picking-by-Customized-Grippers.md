---
layout: post
title: "A Learning Framework for Robust Bin Picking by Customized Grippers"
date: 2019-03-05 04:29:44
categories: arXiv_AI
tags: arXiv_AI Face CNN Optimization
author: Yongxiang Fan, Hsien-Chung Lin, Te Tang, Masayoshi Tomizuka
mathjax: true
---

* content
{:toc}

##### Abstract
Customized grippers have specifically designed fingers to increase the contact area with the workpieces and improve the grasp robustness. However, grasp planning for customized grippers is challenging due to the object variations, surface contacts and structural constraints of the grippers. In this paper, we propose a learning framework to plan robust grasps for customized grippers in real-time. The learning framework contains a low-level optimization-based planner to search for optimal grasps locally under object shape variations, and a high-level learning-based explorer to learn the grasp exploration based on previous grasp experience. The optimization-based planner uses an iterative surface fitting (ISF) to simultaneously search for optimal gripper transformation and finger displacement by minimizing the surface fitting error. The high-level learning-based explorer trains a region-based convolutional neural network (R-CNN) to propose good optimization regions, which avoids ISF getting stuck in bad local optima and improves the collision avoidance performance. The proposed learning framework with RCNN-ISF is able to consider the structural constraints of the gripper, learn grasp exploration strategy from previous experience, and plan optimal grasps in clutter environment in real-time. The effectiveness of the algorithm is verified by experiments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.08546](http://arxiv.org/abs/1809.08546)

##### PDF
[http://arxiv.org/pdf/1809.08546](http://arxiv.org/pdf/1809.08546)

