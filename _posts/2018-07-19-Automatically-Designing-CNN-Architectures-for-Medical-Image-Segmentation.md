---
layout: post
title: "Automatically Designing CNN Architectures for Medical Image Segmentation"
date: 2018-07-19 23:47:12
categories: arXiv_CV
tags: arXiv_CV Segmentation Reinforcement_Learning
author: Aliasghar Mortazi, Ulas Bagci
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network architectures have traditionally been designed and explored with human expertise in a long-lasting trial-and-error process. This process requires huge amount of time, expertise, and resources. To address this tedious problem, we propose a novel algorithm to optimally find hyperparameters of a deep network architecture automatically. We specifically focus on designing neural architectures for medical image segmentation task. Our proposed method is based on a policy gradient reinforcement learning for which the reward function is assigned a segmentation evaluation utility (i.e., dice index). We show the efficacy of the proposed method with its low computational cost in comparison with the state-of-the-art medical image segmentation networks. We also present a new architecture design, a densely connected encoder-decoder CNN, as a strong baseline architecture to apply the proposed hyperparameter search algorithm. We apply the proposed algorithm to each layer of the baseline architectures. As an application, we train the proposed system on cine cardiac MR images from Automated Cardiac Diagnosis Challenge (ACDC) MICCAI 2017. Starting from a baseline segmentation architecture, the resulting network architecture obtains the state-of-the-art results in accuracy without performing any trial-and-error based architecture design approaches or close supervision of the hyperparameters changes.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.07663](https://arxiv.org/abs/1807.07663)

##### PDF
[https://arxiv.org/pdf/1807.07663](https://arxiv.org/pdf/1807.07663)

