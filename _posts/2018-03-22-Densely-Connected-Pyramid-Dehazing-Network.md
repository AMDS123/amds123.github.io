---
layout: post
title: "Densely Connected Pyramid Dehazing Network"
date: 2018-03-22 15:09:53
categories: arXiv_CV
tags: arXiv_CV Adversarial Embedding
author: He Zhang, Vishal M. Patel
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new end-to-end single image dehazing method, called Densely Connected Pyramid Dehazing Network (DCPDN), which can jointly learn the transmission map, atmospheric light and dehazing all together. The end-to-end learning is achieved by directly embedding the atmospheric scattering model into the network, thereby ensuring that the proposed method strictly follows the physics-driven scattering model for dehazing. Inspired by the dense network that can maximize the information flow along features from different levels, we propose a new edge-preserving densely connected encoder-decoder structure with multi-level pyramid pooling module for estimating the transmission map. This network is optimized using a newly introduced edge-preserving loss function. To further incorporate the mutual structural information between the estimated transmission map and the dehazed result, we propose a joint-discriminator based on generative adversarial network framework to decide whether the corresponding dehazed image and the estimated transmission map are real or fake. An ablation study is conducted to demonstrate the effectiveness of each module evaluated at both estimated transmission map and dehazed result. Extensive experiments demonstrate that the proposed method achieves significant improvements over the state-of-the-art methods. Code will be made available at: this https URL

##### Abstract (translated by Google)
我们提出了一种称为密集连接金字塔除雾网络（DCPDN）的新型端到端单一图像去雾方法，它可以共同学习透射图，大气光和去雾。端到端学习是通过将大气散射模型直接嵌入到网络中来实现的，从而确保所提出的方法严格遵循物理驱动的散射模型。受密集网络的启发，可以最大限度地利用不同层次特征的信息流，我们提出了一种新的边缘保持稠密连接的编码器 - 解码器结构，其具有用于估计传输映射的多级金字塔池模块。该网络使用新引入的边缘保留损失函数进行了优化。为了进一步在估计的传输图和去抖动结果之间结合相互结构信息，我们提出了一种基于生成对抗网络框架的联合鉴别器，以确定相应的去雾图像和估计的传输图是真实的还是假的。进行消融研究以证明在估计的传输图和去除颤动结果时评估的每个模块的有效性。大量的实验证明，所提出的方法比现有技术的方法有显着的改进。代码将在此https网址提供

##### URL
[https://arxiv.org/abs/1803.08396](https://arxiv.org/abs/1803.08396)

##### PDF
[https://arxiv.org/pdf/1803.08396](https://arxiv.org/pdf/1803.08396)

