---
layout: post
title: "DOB-Net: Actively Rejecting Unknown Excessive Time-Varying Disturbances"
date: 2019-07-10 05:31:35
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Optimization RNN Prediction
author: Tianming Wang, Wenjie Lu, Zheng Yan, Dikai Liu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an observer-integrated Reinforcement Learning (RL) approach, called Disturbance OBserver Network (DOB-Net), for robots operating in environments where disturbances are unknown and time-varying, and may frequently exceed robot control capabilities. The DOB-Net integrates a disturbance dynamics observer network and a controller network. Originated from classical DOB mechanisms, the observer is built and enhanced via Recurrent Neural Networks (RNNs), encoding estimation of past values and prediction of future values of unknown disturbances in RNN hidden state. Such encoding allows the controller generate optimal control signals to actively reject disturbances, under the constraints of robot control capabilities. The observer and the controller are jointly learned within policy optimization by advantage actor critic. Numerical simulations on position regulation tasks have demonstrated that the proposed DOB-Net significantly outperforms a canonical feedback controller and classical RL algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04514](http://arxiv.org/abs/1907.04514)

##### PDF
[http://arxiv.org/pdf/1907.04514](http://arxiv.org/pdf/1907.04514)

