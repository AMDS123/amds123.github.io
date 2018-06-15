---
layout: post
title: "View-volume Network for Semantic Scene Completion from a Single Depth Image"
date: 2018-06-14 04:42:05
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yu-Xiao Guo, Xin Tong
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a View-Volume convolutional neural network (VVNet) for inferring the occupancy and semantic labels of a volumetric 3D scene from a single depth image. The VVNet concatenates a 2D view CNN and a 3D volume CNN with a differentiable projection layer. Given a single RGBD image, our method extracts the detailed geometric features from the input depth image with a 2D view CNN and then projects the features into a 3D volume according to the input depth map via a projection layer. After that, we learn the 3D context information of the scene with a 3D volume CNN for computing the result volumetric occupancy and semantic labels. With combined 2D and 3D representations, the VVNet efficiently reduces the computational cost, enables feature extraction from multi-channel high resolution inputs, and thus significantly improves the result accuracy. We validate our method and demonstrate its efficiency and effectiveness on both synthetic SUNCG and real NYU dataset.

##### Abstract (translated by Google)
我们引入了一个View-Volume卷积神经网络（VVNet），用于根据单个深度图像来推断体积3D场景的占用率和语义标签。 VVNet将2D视图CNN和3D体积CNN与可微投影层连接起来。给定单个RGBD图像，我们的方法使用2D视图CNN从输入深度图像中提取详细的几何特征，然后根据输入深度图通过投影图层将特征投影到3D体积中。之后，我们利用3D体积CNN学习场景的3D上下文信息，以计算结果体积占用率和语义标签。借助2D和3D组合表示，VVNet可有效降低计算成本，支持从多通道高分辨率输入中提取特征，从而显着提高结果精度。我们验证了我们的方法并证明了它在合成SUNCG和真实NYU数据集上的效率和有效性。

##### URL
[http://arxiv.org/abs/1806.05361](http://arxiv.org/abs/1806.05361)

##### PDF
[http://arxiv.org/pdf/1806.05361](http://arxiv.org/pdf/1806.05361)

