---
layout: post
title: "Deep Global-Relative Networks for End-to-End 6-DoF Visual Localization and Odometry"
date: 2019-05-10 08:11:42
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yimin Lin, Zhaoxiang Liu, Jianfeng Huang, Chaopeng Wang, Guoguang Du, Jinqiang Bai, Shiguo Lian, Bill Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Although a wide variety of deep neural networks for robust Visual Odometry (VO) can be found in the literature, they are still unable to solve the drift problem in long-term robot navigation. Thus, this paper aims to propose novel deep end-to-end networks for long-term 6-DoF VO task. It mainly fuses relative and global networks based on Recurrent Convolutional Neural Networks (RCNNs) to improve the monocular localization accuracy. Indeed, the relative sub-networks are implemented to smooth the VO trajectory, while global subnetworks are designed to avoid drift problem. All the parameters are jointly optimized using Cross Transformation Constraints (CTC), which represents temporal geometric consistency of the consecutive frames, and Mean Square Error (MSE) between the predicted pose and ground truth. The experimental results on both indoor and outdoor datasets show that our method outperforms other state-of-the-art learning-based VO methods in terms of pose accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07869](http://arxiv.org/abs/1812.07869)

##### PDF
[http://arxiv.org/pdf/1812.07869](http://arxiv.org/pdf/1812.07869)

