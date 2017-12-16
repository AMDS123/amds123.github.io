---
layout: post
title: "Hybrid Learning of Optical Flow and Next Frame Prediction to Boost Optical Flow in the Wild"
date: 2017-04-07 13:01:12
categories: arXiv_CV
tags: arXiv_CV Attention Classification Prediction
author: Nima Sedaghat, Mohammadreza Zolfaghari, Thomas Brox
mathjax: true
---

* content
{:toc}

##### Abstract
CNN-based optical flow estimation has attracted attention recently, mainly due to its impressively high frame rates. These networks perform well on synthetic datasets, but they are still far behind the classical methods in real-world videos. This is because there is no ground truth optical flow for training these networks on real data. In this paper, we boost CNN-based optical flow estimation in real scenes with the help of the freely available self-supervised task of next-frame prediction. To this end, we train the network in a hybrid way, providing it with a mixture of synthetic and real videos. With the help of a sample-variant multi-tasking architecture, the network is trained on different tasks depending on the availability of ground-truth. We also experiment with the prediction of "next-flow" instead of estimation of the current flow, which is intuitively closer to the task of next-frame prediction and yields favorable results. We demonstrate the improvement in optical flow estimation on the real-world KITTI benchmark. Additionally, we test the optical flow indirectly in an action classification scenario. As a side product of this work, we report significant improvements over state-of-the-art in the task of next-frame prediction.

##### Abstract (translated by Google)
基于CNN的光流估计最近引起了人们的注意，这主要是由于它的帧速率非常高。这些网络在综合数据集上表现良好，但在实际视频中仍然落后于传统方法。这是因为没有地面真实光流来训练这些网络的真实数据。在本文中，我们利用自由监督的下一帧预测任务，在实际场景中提高基于CNN的光流估计。为此，我们以混合方式对网络进行培训，为其提供合成和真实视频的混合。借助于样本变化的多任务架构，网络根据地面实况的可用性在不同的任务上进行训练。我们也对“下一流”的预测进行了实验，而不是对当前流量的估计，这直观地接近下一帧预测的任务并产生有利的结果。我们证明了现实世界KITTI基准测试中光流估计的改进。另外，我们在动作分类场景中间接测试光流。作为这项工作的一个副产品，我们报告了在下一帧预测任务中最先进的技术。

##### URL
[https://arxiv.org/abs/1612.03777](https://arxiv.org/abs/1612.03777)

##### PDF
[https://arxiv.org/pdf/1612.03777](https://arxiv.org/pdf/1612.03777)

