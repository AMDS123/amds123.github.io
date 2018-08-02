---
layout: post
title: "Bi-Real Net: Enhancing the Performance of 1-bit CNNs With Improved Representational Capability and Advanced Training Algorithm"
date: 2018-08-01 11:40:59
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Zechun Liu, Baoyuan Wu, Wenhan Luo, Xin Yang, Wei Liu, Kwang-Ting Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we study the 1-bit convolutional neural networks (CNNs), of which both the weights and activations are binary. While being efficient, the classification accuracy of the current 1-bit CNNs is much worse compared to their counterpart real-valued CNN models on the large-scale dataset, like ImageNet. To minimize the performance gap between the 1-bit and real-valued CNN models, we propose a novel model, dubbed Bi-Real net, which connects the real activations (after the 1-bit convolution and/or BatchNorm layer, before the sign function) to activations of the consecutive block, through an identity shortcut. Consequently, compared to the standard 1-bit CNN, the representational capability of the Bi-Real net is significantly enhanced and the additional cost on computation is negligible. Moreover, we develop a specific training algorithm including three technical novelties for 1- bit CNNs. Firstly, we derive a tight approximation to the derivative of the non-differentiable sign function with respect to activation. Secondly, we propose a magnitude-aware gradient with respect to the weight for updating the weight parameters. Thirdly, we pre-train the real-valued CNN model with a clip function, rather than the ReLU function, to better initialize the Bi-Real net. Experiments on ImageNet show that the Bi-Real net with the proposed training algorithm achieves 56.4% and 62.2% top-1 accuracy with 18 layers and 34 layers, respectively. Compared to the state-of-the-arts (e.g., XNOR Net), Bi-Real net achieves up to 10% higher top-1 accuracy with more memory saving and lower computational cost.

##### Abstract (translated by Google)
在这项工作中，我们研究了1位卷积神经网络（CNN），其中权重和激活都是二进制的。虽然效率很高，但与大型数据集（如ImageNet）上的对应实值CNN模型相比，当前1位CNN的分类准确性要差得多。为了最小化1位和实值CNN模型之间的性能差距，我们提出了一种新型模型，称为Bi-Real网络，它连接实际激活（在1位卷积和/或BatchNorm层之后，在符号之前） function）通过身份快捷方式激活连续块。因此，与标准的1比特CNN相比，Bi-Real网络的代表性能力显着增强，并且计算的额外成本可以忽略不计。此外，我们开发了一种特定的训练算法，包括针对1位CNN的三种技术新颖性。首先，我们推导出关于激活的非可微分号函数的导数的紧逼近似。其次，我们提出了关于更新权重参数的权重的幅度感知梯度。第三，我们使用剪辑函数（而不是ReLU函数）预先训练实值CNN模型，以更好地初始化Bi-Real网络。在ImageNet上的实验表明，所提出的训练算法的Bi-Real网络分别在18层和34层分别达到56.4％和62.2％的前1精度。与现有技术（例如，XNOR Net）相比，Bi-Real网络在前1精度方面实现高达10％的成本，同时节省更多内存并降低计算成本。

##### URL
[https://arxiv.org/abs/1808.00278](https://arxiv.org/abs/1808.00278)

##### PDF
[https://arxiv.org/pdf/1808.00278](https://arxiv.org/pdf/1808.00278)

