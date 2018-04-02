---
layout: post
title: "Cross-modal Deep Variational Hand Pose Estimation"
date: 2018-03-30 10:27:06
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Detection
author: Adrian Spurr, Jie Song, Seonwook Park, Otmar Hilliges
mathjax: true
---

* content
{:toc}

##### Abstract
The human hand moves in complex and high-dimensional ways, making estimation of 3D hand pose configurations from images alone a challenging task. In this work we propose a method to learn a statistical hand model represented by a cross-modal trained latent space via a generative deep neural network. We derive an objective function from the variational lower bound of the VAE framework and jointly optimize the resulting cross-modal KL-divergence and the posterior reconstruction objective, naturally admitting a training regime that leads to a coherent latent space across multiple modalities such as RGB images, 2D keypoint detections or 3D hand configurations. Additionally, it grants a straightforward way of using semi-supervision. This latent space can be directly used to estimate 3D hand poses from RGB images, outperforming the state-of-the art in different settings. Furthermore, we show that our proposed method can be used without changes on depth images and performs comparably to specialized methods. Finally, the model is fully generative and can synthesize consistent pairs of hand configurations across modalities. We evaluate our method on both RGB and depth datasets and analyze the latent space qualitatively.

##### Abstract (translated by Google)
人的手以复杂和高维的方式移动，从图像估计3D手姿势配置本身就是一项具有挑战性的任务。在这项工作中，我们提出了一种方法，通过生成的深度神经网络来学习由跨模态训练的潜在空间表示的统计手模型。我们从VAE框架的变分下界推导出一个目标函数，并联合优化得到的跨模态KL散度和后向重建目标，自然而然地接受了一个导致跨越多种模态（如RGB图像）的连贯潜在空间的训练机制，2D关键点检测或3D手形配置。此外，它还提供了使用半监督的简单方法。这个潜在的空间可以直接用于估计RGB图像中的3D手势，在不同的设置中胜过现有技术。此外，我们表明，我们提出的方法可以在不改变深度图像的情况下使用，并且与专门的方法相当。最后，该模型是完全生成的，可以在不同的模式下合成一致的手对配置。我们在RGB和深度数据集上评估我们的方法并定性分析潜在空间。

##### URL
[https://arxiv.org/abs/1803.11404](https://arxiv.org/abs/1803.11404)

##### PDF
[https://arxiv.org/pdf/1803.11404](https://arxiv.org/pdf/1803.11404)

