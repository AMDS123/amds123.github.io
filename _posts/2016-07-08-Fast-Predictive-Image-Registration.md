---
layout: post
title: "Fast Predictive Image Registration"
date: 2016-07-08 19:58:56
categories: arXiv_CV
tags: arXiv_CV Optimization Prediction
author: Xiao Yang, Roland Kwitt, Marc Niethammer
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to predict image deformations based on patch-wise image appearance. Specifically, we design a patch-based deep encoder-decoder network which learns the pixel/voxel-wise mapping between image appearance and registration parameters. Our approach can predict general deformation parameterizations, however, we focus on the large deformation diffeomorphic metric mapping (LDDMM) registration model. By predicting the LDDMM momentum-parameterization we retain the desirable theoretical properties of LDDMM, while reducing computation time by orders of magnitude: combined with patch pruning, we achieve a 1500x/66x speed up compared to GPU-based optimization for 2D/3D image registration. Our approach has better prediction accuracy than predicting deformation or velocity fields and results in diffeomorphic transformations. Additionally, we create a Bayesian probabilistic version of our network, which allows evaluation of deformation field uncertainty through Monte Carlo sampling using dropout at test time. We show that deformation uncertainty highlights areas of ambiguous deformations. We test our method on the OASIS brain image dataset in 2D and 3D.

##### Abstract (translated by Google)
我们提出了一种方法来预测图像变形基于拼图明智的图像外观。具体来说，我们设计了一个基于补丁的深度编码器 - 解码器网络，它学习了图像外观和注册参数之间的像素/体素方面的映射。我们的方法可以预测一般变形参数化，但是我们关注大变形微分同胚映射（LDDMM）配准模型。通过预测LDDMM动量参数化，我们保留了理想的LDDMM理论特性，同时将计算时间减少了数量级：结合修补程序修剪，与2D / 3D图像配准的基于GPU的优化相比，我们实现了1500x / 66x的加速。我们的方法具有比预测变形或速度场更好的预测精度，并且导致微分变换。此外，我们创建了我们网络的贝叶斯概率版本，该版本允许在测试时间通过使用丢弃的蒙特卡罗采样来评估变形场的不确定性。我们显示变形的不确定性突出了模糊变形的区域。我们在2D和3D的OASIS大脑图像数据集上测试我们的方法。

##### URL
[https://arxiv.org/abs/1607.02504](https://arxiv.org/abs/1607.02504)

##### PDF
[https://arxiv.org/pdf/1607.02504](https://arxiv.org/pdf/1607.02504)

