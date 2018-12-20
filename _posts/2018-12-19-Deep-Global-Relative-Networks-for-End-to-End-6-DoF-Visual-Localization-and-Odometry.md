---
layout: post
title: "Deep Global-Relative Networks for End-to-End 6-DoF Visual Localization and Odometry"
date: 2018-12-19 10:51:09
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN
author: Yimin Lin, Zhaoxiang Liu, Jianfeng Huang, Chaopeng Wang, Guoguang Du, Jinqiang Bai, Shiguo Lian, Bill Huang
mathjax: true
---

* content
{:toc}

##### Abstract
For the autonomous navigation of mobile robots, robust and fast visual localization is a challenging task. Although some end-to-end deep neural networks for 6-DoF Visual Odometry (VO) have been reported with promising results, they are still unable to solve the drift problem in long-range navigation. In this paper, we propose the deep global-relative networks (DGRNets), which is a novel global and relative fusion framework based on Recurrent Convolutional Neural Networks (RCNNs). It is designed to jointly estimate global pose and relative localization from consecutive monocular images. DGRNets include feature extraction sub-networks for discriminative feature selection, RCNNs-type relative pose estimation subnetworks for smoothing the VO trajectory and RCNNs-type global pose regression sub-networks for avoiding the accumulation of pose errors. We also propose two loss functions: the first one consists of Cross Transformation Constraints (CTC) that utilize geometric consistency of the adjacent frames to train a more accurate relative sub-networks, and the second one is composed of CTC and Mean Square Error (MSE) between the predicted pose and ground truth used to train the end-to-end DGRNets. The competitive experiments on indoor Microsoft 7-Scenes and outdoor KITTI dataset show that our DGRNets outperform other learning-based monocular VO methods in terms of pose accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07869](http://arxiv.org/abs/1812.07869)

##### PDF
[http://arxiv.org/pdf/1812.07869](http://arxiv.org/pdf/1812.07869)

