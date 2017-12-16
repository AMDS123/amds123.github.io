---
layout: post
title: "Real-Time Pose Estimation for Event Cameras with Stacked Spatial LSTM Networks"
date: 2017-08-22 18:59:22
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation RNN
author: Anh Nguyen, Thanh-Toan Do, Darwin G. Caldwell, Nikos G. Tsagarakis
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new method to estimate the 6DOF pose of the event camera solely based on the event stream. Our method first creates the event image from a list of events that occurs in a very short time interval, then a Stacked Spatial LSTM Network (SP-LSTM) is used to learn and estimate the camera pose. Our SP-LSTM comprises a CNN to learn deep features from the event images and a stack of LSTM to learn spatial dependencies in the image features space. We show that the spatial dependency plays an important role in the pose estimation task and the SP-LSTM can effectively learn that information. The experimental results on the public dataset show that our approach outperforms recent methods by a substantial margin. Overall, our proposed method reduces about 6 times the position error and 3 times the orientation error over the state of the art. The source code and trained models will be released.

##### Abstract (translated by Google)
我们提出了一种新的方法来估计事件相机的6DOF姿态完全基于事件流。我们的方法首先从事件发生在一个非常短的时间间隔的列表中创建事件图像，然后使用堆叠空间LSTM网络（SP-LSTM）来学习和估计摄像机姿态。我们的SP-LSTM包含一个CNN，用于从事件图像学习深度特征和一堆LSTM，以学习图像特征空间中的空间依赖关系。我们发现空间依赖在姿态估计任务中起着重要的作用，SP-LSTM可以有效地学习这些信息。公共数据集上的实验结果表明，我们的方法大大超过了最近的方法。总的来说，我们提出的方法在现有技术水平上减少了大约6倍的位置误差和3倍的定向误差。源代码和训练有素的模型将被释放。

##### URL
[https://arxiv.org/abs/1708.09011](https://arxiv.org/abs/1708.09011)

##### PDF
[https://arxiv.org/pdf/1708.09011](https://arxiv.org/pdf/1708.09011)

