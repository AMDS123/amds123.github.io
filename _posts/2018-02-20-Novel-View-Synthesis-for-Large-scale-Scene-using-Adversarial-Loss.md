---
layout: post
title: "Novel View Synthesis for Large-scale Scene using Adversarial Loss"
date: 2018-02-20 11:21:11
categories: arXiv_CV
tags: arXiv_CV Adversarial Sparse CNN Quantitative
author: Xiaochuan Yin, Henglai Wei, Penghong lin, Xiangwei Wang, Qijun Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Novel view synthesis aims to synthesize new images from different viewpoints of given images. Most of previous works focus on generating novel views of certain objects with a fixed background. However, for some applications, such as virtual reality or robotic manipulations, large changes in background may occur due to the egomotion of the camera. Generated images of a large-scale environment from novel views may be distorted if the structure of the environment is not considered. In this work, we propose a novel fully convolutional network, that can take advantage of the structural information explicitly by incorporating the inverse depth features. The inverse depth features are obtained from CNNs trained with sparse labeled depth values. This framework can easily fuse multiple images from different viewpoints. To fill the missing textures in the generated image, adversarial loss is applied, which can also improve the overall image quality. Our method is evaluated on the KITTI dataset. The results show that our method can generate novel views of large-scale scene without distortion. The effectiveness of our approach is demonstrated through qualitative and quantitative evaluation.

##### Abstract (translated by Google)
新颖的视图合成旨在从给定图像的不同视角合成新图像。以前的大部分作品着重于生成具有固定背景的特定对象的新视图。但是，对于某些应用程序（如虚拟现实或机器人操作），由于摄像头的自我运动可能会发生背景变化较大。如果不考虑环境的结构，从新视角生成的大规模环境图像可能会被扭曲。在这项工作中，我们提出了一种新的完全卷积网络，它可以通过结合逆深度特征明确地利用结构信息。逆深度特征从用稀疏标记的深度值训练的CNN获得。该框架可以轻松融合来自不同视点的多个图像。为了在生成的图像中填充缺失的纹理，应用对抗性损失，这也可以改善整体图像质量。我们的方法在KITTI数据集上进行评估。结果表明，我们的方法可以产生新颖的大规模场景而不失真。通过定性和定量评估证明了我们方法的有效性。

##### URL
[http://arxiv.org/abs/1802.07064](http://arxiv.org/abs/1802.07064)

##### PDF
[http://arxiv.org/pdf/1802.07064](http://arxiv.org/pdf/1802.07064)

