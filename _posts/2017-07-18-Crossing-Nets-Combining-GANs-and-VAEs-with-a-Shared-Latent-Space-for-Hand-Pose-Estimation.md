---
layout: post
title: "Crossing Nets: Combining GANs and VAEs with a Shared Latent Space for Hand Pose Estimation"
date: 2017-07-18 18:30:33
categories: arXiv_CV
tags: arXiv_CV GAN Pose_Estimation Relation
author: Chengde Wan, Thomas Probst, Luc Van Gool, Angela Yao
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art methods for 3D hand pose estimation from depth images require large amounts of annotated training data. We propose to model the statistical relationships of 3D hand poses and corresponding depth images using two deep generative models with a shared latent space. By design, our architecture allows for learning from unlabeled image data in a semi-supervised manner. Assuming a one-to-one mapping between a pose and a depth map, any given point in the shared latent space can be projected into both a hand pose and a corresponding depth map. Regressing the hand pose can then be done by learning a discriminator to estimate the posterior of the latent pose given some depth maps. To improve generalization and to better exploit unlabeled depth maps, we jointly train a generator and a discriminator. At each iteration, the generator is updated with the back-propagated gradient from the discriminator to synthesize realistic depth maps of the articulated hand, while the discriminator benefits from an augmented training set of synthesized and unlabeled samples. The proposed discriminator network architecture is highly efficient and runs at 90 FPS on the CPU with accuracies comparable or better than state-of-art on 3 publicly available benchmarks.

##### Abstract (translated by Google)
用于从深度图像进行3D手姿态估计的最先进的方法需要大量的注释训练数据。我们建议使用具有共享的潜在空间的两个深度生成模型来模拟3D手姿势和相应深度图像的统计关系。通过设计，我们的架构允许以半监督的方式从未标记的图像数据中学习。假设姿势和深度图之间的一对一映射，可以将共享的潜在空间中的任何给定点投影到手姿势和相应的深度图中。通过学习一个鉴别器来估计潜在姿势的后部，给出一些深度图，可以完成手部姿态的回归。为了改进泛化和更好地利用未标记的深度图，我们共同训练一个发生器和一个鉴别器。在每一次迭代中，发生器用来自鉴别器的向后传播的梯度进行更新以合成关节手的真实深度图，而鉴别器从合成和未标记样本的增广训练集中受益。所提出的鉴别器网络架构是高效的，并且在CPU上以90FPS运行，其准确度可以比3个公开可用的基准测试的先进水平相当或更好。

##### URL
[https://arxiv.org/abs/1702.03431](https://arxiv.org/abs/1702.03431)

##### PDF
[https://arxiv.org/pdf/1702.03431](https://arxiv.org/pdf/1702.03431)

