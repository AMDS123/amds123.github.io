---
layout: post
title: "Globally Tuned Cascade Pose Regression via Back Propagation with Application in 2D Face Pose Estimation and Heart Segmentation in 3D CT Images"
date: 2015-03-30 20:17:23
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Face Pose_Estimation
author: Peng Sun, James K. Min, Guanglei Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, a successful pose estimation algorithm, called Cascade Pose Regression (CPR), was proposed in the literature. Trained over Pose Index Feature, CPR is a regressor ensemble that is similar to Boosting. In this paper we show how CPR can be represented as a Neural Network. Specifically, we adopt a Graph Transformer Network (GTN) representation and accordingly train CPR with Back Propagation (BP) that permits globally tuning. In contrast, previous CPR literature only took a layer wise training without any post fine tuning. We empirically show that global training with BP outperforms layer-wise (pre-)training. Our CPR-GTN adopts a Multi Layer Percetron as the regressor, which utilized sparse connection to learn local image feature representation. We tested the proposed CPR-GTN on 2D face pose estimation problem as in previous CPR literature. Besides, we also investigated the possibility of extending CPR-GTN to 3D pose estimation by doing experiments using 3D Computed Tomography dataset for heart segmentation.

##### Abstract (translated by Google)
最近，文献中提出了一种成功的姿态估计算法，称为级联姿态回归（CPR）。训练过的姿态指数特征，CPR是一个类似于Boosting的回归集合。在本文中，我们展示了如何将CPR表示为神经网络。具体而言，我们采用图形变换网络（GTN）表示，并相应地训练具有反向传播（BP）的CPR，以允许全局调整。相比之下，以前的CPR文献只是采取了一个层次明智的训练，没有任何后期的微调。我们凭经验证明，全球BP培训优于分层（预）培训。我们的CPR-GTN采用多层Percetron作为回归器，利用稀疏连接学习局部图像特征表示。我们测试提出的CPR-GTN的二维人脸姿态估计问题，如以前的CPR文献。此外，我们还通过使用3D计算机断层扫描数据集进行心脏分割实验，研究了将CPR-GTN扩展到三维姿态估计的可能性。

##### URL
[https://arxiv.org/abs/1503.08843](https://arxiv.org/abs/1503.08843)

##### PDF
[https://arxiv.org/pdf/1503.08843](https://arxiv.org/pdf/1503.08843)

