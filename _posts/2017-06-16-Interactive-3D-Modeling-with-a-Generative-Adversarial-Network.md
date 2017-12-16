---
layout: post
title: "Interactive 3D Modeling with a Generative Adversarial Network"
date: 2017-06-16 08:01:09
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Jerry Liu, Fisher Yu, Thomas Funkhouser
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes the idea of using a generative adversarial network (GAN) to assist a novice user in designing real-world shapes with a simple interface. The user edits a voxel grid with a painting interface (like Minecraft). Yet, at any time, he/she can execute a SNAP command, which projects the current voxel grid onto a latent shape manifold with a learned projection operator and then generates a similar, but more realistic, shape using a learned generator network. Then the user can edit the resulting shape and snap again until he/she is satisfied with the result. The main advantage of this approach is that the projection and generation operators assist novice users to create 3D models characteristic of a background distribution of object shapes, but without having to specify all the details. The core new research idea is to use a GAN to support this application. 3D GANs have previously been used for shape generation, interpolation, and completion, but never for interactive modeling. The new challenge for this application is to learn a projection operator that takes an arbitrary 3D voxel model and produces a latent vector on the shape manifold from which a similar and realistic shape can be generated. We develop algorithms for this and other steps of the SNAP processing pipeline and integrate them into a simple modeling tool. Experiments with these algorithms and tool suggest that GANs provide a promising approach to computer-assisted interactive modeling.

##### Abstract (translated by Google)
本文提出使用生成对抗网络（GAN）来帮助新手用户以简单的界面设计真实世界的形状。用户使用绘画界面（像Minecraft）编辑体素网格。然而，在任何时候，他/她都可以执行SNAP命令，将当前体素网格投影到具有学习投影算子的潜在形状流形上，然后使用学习生成器网络生成类似但更逼真的形状。然后用户可以编辑结果形状并再次捕捉，直到他/她对结果满意为止。这种方法的主要优点在于，投影和生成操作者可以帮助新手用户创建具有背景分布的三维模型特征，而不必指定所有的细节。核心的新研究思路是使用GAN来支持这个应用程序。以前，3D GAN用于形状生成，插值和完成，但从未用于交互式建模。这个应用程序的新挑战是学习一个投影算子，它采用任意三维体素模型，并在形状流形上产生一个潜在向量，从中可以生成一个类似的，逼真的形状。我们为SNAP处理流水线的这个步骤和其他步骤开发算法，并将它们集成到一个简单的建模工具中。这些算法和工具的实验表明，GAN为计算机辅助交互建模提供了一种有前途的方法。

##### URL
[https://arxiv.org/abs/1706.05170](https://arxiv.org/abs/1706.05170)

##### PDF
[https://arxiv.org/pdf/1706.05170](https://arxiv.org/pdf/1706.05170)

