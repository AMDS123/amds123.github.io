---
layout: post
title: "Real-Time 6DOF Pose Relocalization for Event Cameras with Stacked Spatial LSTM Networks"
date: 2018-03-04 13:55:15
categories: arXiv_CV
tags: arXiv_CV RNN
author: Anh Nguyen, Thanh-Toan Do, Darwin G. Caldwell, Nikos G. Tsagarakis
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new method to relocalize the 6DOF pose of an event camera solely based on the event stream. Our method first creates the event image from a list of events that occurs in a very short time interval, then a Stacked Spatial LSTM Network (SP-LSTM) is used to learn the camera pose. Our SP-LSTM is composed of a CNN to learn deep features from the event images and a stack of LSTM to learn spatial dependencies in the image feature space. We show that the spatial dependency plays an important role in the relocalization task and the SP-LSTM can effectively learn this information. The experimental results on a publicly available dataset show that our approach generalizes well and outperforms recent methods by a substantial margin. Overall, our proposed method reduces by approx. 6 times the position error and 3 times the orientation error compared to the current state of the art. The source code and trained models will be released.

##### Abstract (translated by Google)
我们提出了一种新方法，仅基于事件流重新定位事件相机的6DOF姿态。我们的方法首先根据发生在很短时间间隔内的事件列表创建事件图像，然后使用堆叠空间LSTM网络（SP-LSTM）学习相机姿态。我们的SP-LSTM由CNN组成，用于从事件图像学习深度特征和一堆LSTM，以学习图像特征空间中的空间依赖关系。我们表明，空间依赖性在重新定位任务中扮演着重要角色，SP-LSTM可以有效地学习这些信息。在公开可用的数据集上的实验结果表明，我们的方法具有很好的泛化能力，并且大大超出了最近的方法。总体而言，我们提出的方法减少了约。与现有技术相比，是位置误差的6倍和定向误差的3倍。源代码和训练有素的模型将被发布。

##### URL
[http://arxiv.org/abs/1708.09011](http://arxiv.org/abs/1708.09011)

##### PDF
[http://arxiv.org/pdf/1708.09011](http://arxiv.org/pdf/1708.09011)

