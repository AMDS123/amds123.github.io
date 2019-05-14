---
layout: post
title: "Fast Skill Learning for Variable Compliance Robotic Assembly"
date: 2019-05-11 02:44:46
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Prediction
author: Tianyu Ren, Yunfei Dong, Dan Wu, Ken Chen
mathjax: true
---

* content
{:toc}

##### Abstract
The robotic assembly represents a group of benchmark problems for reinforcement learning and variable compliance control that features sophisticated contact manipulation. One of the key challenges in applying reinforcement learning to physical robot is the sample complexity, the requirement of large amounts of experience for learning. We mitigate this sample complexity problem by incorporating an iteratively refitted model into the learning process through model-guided exploration. Yet, fitting a local model of the physical environment is of major difficulties. In this work, a Kalman filter is used to combine the adaptive linear dynamics with a coarse prior model from analytical description, and proves to give more accurate predictions than the existing method. Experimental results show that the proposed model fitting strategy can be incorporated into a model predictive controller to generate good exploration behaviors for learning acceleration, while preserving the benefits of model-free reinforcement learning for uncertain environments. In addition to the sample complexity, the inevitable robot overloaded during operation also tends to limit the learning efficiency. To address this problem, we present a method to restrict the largest possible potential energy in the compliance control system and therefore keep the contact force within the legitimate range.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04427](http://arxiv.org/abs/1905.04427)

##### PDF
[http://arxiv.org/pdf/1905.04427](http://arxiv.org/pdf/1905.04427)

