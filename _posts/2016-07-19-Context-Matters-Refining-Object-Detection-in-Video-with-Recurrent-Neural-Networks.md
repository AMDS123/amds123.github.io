---
layout: post
title: "Context Matters: Refining Object Detection in Video with Recurrent Neural Networks"
date: 2016-07-19 03:00:35
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection CNN RNN Detection
author: Subarna Tripathi, Zachary C. Lipton, Serge Belongie, Truong Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
Given the vast amounts of video available online, and recent breakthroughs in object detection with static images, object detection in video offers a promising new frontier. However, motion blur and compression artifacts cause substantial frame-level variability, even in videos that appear smooth to the eye. Additionally, video datasets tend to have sparsely annotated frames. We present a new framework for improving object detection in videos that captures temporal context and encourages consistency of predictions. First, we train a pseudo-labeler, that is, a domain-adapted convolutional neural network for object detection. The pseudo-labeler is first trained individually on the subset of labeled frames, and then subsequently applied to all frames. Then we train a recurrent neural network that takes as input sequences of pseudo-labeled frames and optimizes an objective that encourages both accuracy on the target frame and consistency across consecutive frames. The approach incorporates strong supervision of target frames, weak-supervision on context frames, and regularization via a smoothness penalty. Our approach achieves mean Average Precision (mAP) of 68.73, an improvement of 7.1 over the strongest image-based baselines for the Youtube-Video Objects dataset. Our experiments demonstrate that neighboring frames can provide valuable information, even absent labels.

##### Abstract (translated by Google)
鉴于大量的在线视频，以及静态图像对象检测方面的最新突破，视频中的对象检测提供了一个前景广阔的前景。然而，运动模糊和压缩伪像会导致大量的帧级变化，即使在视频看起来平滑的视频中也是如此。另外，视频数据集倾向于具有稀疏的注释帧。我们提出了一个新的框架，改善视频中的对象检测捕获时间上下文，并鼓励预测的一致性。首先，我们训练一个伪标签，即用于物体检测的一个适应领域的卷积神经网络。伪标签首先在标签帧的子集上单独训练，然后应用于所有帧。然后，我们训练一个循环神经网络，将伪标签帧作为输入序列，并优化一个目标，以提高目标帧的精度和连续帧的一致性。该方法包括对目标帧的强大监督，对上下文帧的弱监督以及通过平滑惩罚进行正规化。我们的方法实现了68.73的平均精确度（mAP），比Youtube视频对象数据集的最强基于图像的基线提高了7.1。我们的实验表明，相邻的框架可以提供有价值的信息，甚至没有标签。

##### URL
[https://arxiv.org/abs/1607.04648](https://arxiv.org/abs/1607.04648)

##### PDF
[https://arxiv.org/pdf/1607.04648](https://arxiv.org/pdf/1607.04648)

