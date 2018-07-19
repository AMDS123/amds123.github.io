---
layout: post
title: "Accel: A Corrective Fusion Network for Efficient Semantic Segmentation on Video"
date: 2018-07-17 20:45:23
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference Prediction
author: Samvit Jain, Xin Wang, Joseph Gonzalez
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present Accel, a novel semantic video segmentation system that achieves high accuracy at low inference times by combining the predictions of two network branches: (1) a reference branch that extracts high-detail features on a reference keyframe, and warps these features forward using frame-to-frame optical flow estimates, and (2) an update branch that computes features of adjustable quality on the current frame, performing a temporal update at each video frame. The modularity of the update branch, where feature subnetworks of varying layer depth can be inserted (e.g. ResNet-18 to ResNet-101), enables operation over a new, state-of-the-art accuracy-throughput trade-off spectrum. Over this curve, Accel models achieve both higher accuracy and faster inference times than the closest comparable single-frame segmentation networks. In general, Accel significantly outperforms previous work on efficient semantic video segmentation, correcting warping-related error that compounds on datasets with complex dynamics. Accel is end-to-end trainable and highly modular: the reference network, the optical flow network, and the update network can each be selected independently, depending on application requirements, and then jointly fine-tuned. The result is a robust, general system for fast, high-accuracy semantic segmentation on video.

##### Abstract (translated by Google)
在本文中，我们介绍了Accel，一种新颖的语义视频分割系统，通过结合两个网络分支的预测，在低推理时间内实现高精度：（1）在参考关键帧上提取高细节特征的参考分支，以及扭曲这些特征使用帧到帧光流估计来转发，以及（2）更新分支，其在当前帧上计算可调质量的特征，在每个视频帧处执行时间更新。可以插入具有不同层深度的特征子网的更新分支的模块性（例如ResNet-18到ResNet-101）使得能够在新的，最先进的精度 - 吞吐量折衷频谱上操作。在此曲线上，与最接近的可比较的单帧分割网络相比，Accel模型实现了更高的准确性和更快的推理时间。总的来说，Accel明显优于以前的有效语义视频分割工作，纠正了与复杂动态数据集相关的扭曲相关误差。 Accel端到端可训练且高度模块化：参考网络，光流网络和更新网络均可根据应用要求独立选择，然后进行联合微调。结果是一个强大的通用系统，可以对视频进行快速，高精度的语义分割。

##### URL
[https://arxiv.org/abs/1807.06667](https://arxiv.org/abs/1807.06667)

##### PDF
[https://arxiv.org/pdf/1807.06667](https://arxiv.org/pdf/1807.06667)

