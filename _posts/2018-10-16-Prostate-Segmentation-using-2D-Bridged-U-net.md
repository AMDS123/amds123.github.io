---
layout: post
title: "Prostate Segmentation using 2D Bridged U-net"
date: 2018-10-16 11:50:42
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning Prediction
author: Wanli Chen, Yue Zhang, Junjun He, Yu Qiao, Yifan Chen, Hongjian Shi, Xiaoying Tang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we focus on three problems in deep learning based medical image segmentation. Firstly, U-net, as a popular model for medical image segmentation, is difficult to train when convolutional layers increase even though a deeper network usually has a better generalization ability because of more learnable parameters. Secondly, the exponential ReLU (ELU), as an alternative of ReLU, is not much different from ReLU when the network of interest gets deep. Thirdly, the Dice loss, as one of the pervasive loss functions for medical image segmentation, is not effective when the prediction is close to ground truth and will cause oscillation during training. To address the aforementioned three problems, we propose and validate a deeper network that can fit medical image datasets that are usually small in the sample size. Meanwhile, we propose a new loss function to accelerate the learning process and a combination of different activation functions to improve the network performance. Our experimental results suggest that our network is comparable or superior to state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.04459](http://arxiv.org/abs/1807.04459)

##### PDF
[http://arxiv.org/pdf/1807.04459](http://arxiv.org/pdf/1807.04459)

