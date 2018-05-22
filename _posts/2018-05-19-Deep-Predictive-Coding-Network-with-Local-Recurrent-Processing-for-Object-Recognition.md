---
layout: post
title: "Deep Predictive Coding Network with Local Recurrent Processing for Object Recognition"
date: 2018-05-19 06:44:24
categories: arXiv_CV
tags: arXiv_CV Salient Attention CNN Image_Classification Classification Prediction Recognition
author: Kuan Han, Haiguang Wen, Yizhen Zhang, Di Fu, Eugenio Culurciello, Zhongming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by "predictive coding" - a theory in neuroscience, we develop a bi-directional and dynamical neural network with local recurrent processing, namely predictive coding network (PCN). Unlike any feedforward-only convolutional neural network, PCN includes both feedback connections, which carry top-down predictions, and feedforward connections, which carry bottom-up errors of prediction. Feedback and feedforward connections enable adjacent layers to interact locally and recurrently to refine representations towards minimization of layer-wise prediction errors. When unfolded over time, the recurrent processing gives rise to an increasingly deeper hierarchy of non-linear transformation, allowing a shallow network to dynamically extend itself into an arbitrarily deep network. We train and test PCN for image classification with SVHN, CIFAR and ImageNet datasets. Despite notably fewer layers and parameters, PCN achieves competitive performance compared to classical and state-of-the-art models. Further analysis shows that the internal representations in PCN converge over time and yield increasingly better accuracy in object recognition. Errors of top-down prediction also map visual saliency or bottom-up attention. This work takes us one step closer to bridging human and machine intelligence in vision.

##### Abstract (translated by Google)
受“预测编码”（一种神经科学理论）的启发，我们开发了一种具有局部循环处理的双向和动态神经网络，即预测编码网络（PCN）。与任何只有前馈的卷积神经网络不同，PCN包括进行自顶向下预测的反馈连接和包含自下而上的预测误差的前馈连接。反馈和前馈连接使相邻层能够在本地和循环中进行交互，以优化表示以最小化分层预测错误。随着时间的推移，随着时间的推移，经常性处理会导致非线性变换的层次越来越深，从而允许浅层网络将其自身扩展到任意深度的网络中。我们使用SVHN，CIFAR和ImageNet数据集训练和测试PCN进行图像分类。尽管层数和参数显着较少，但与经典和最先进的模型相比，PCN实现了具有竞争力的性能。进一步分析表明，PCN中的内部表示会随着时间的推移而收敛，并且在物体识别中产生越来越高的精度。自上而下预测的错误还会映射视觉显着性或自下而上的注意力。这项工作让我们更接近于在视觉上弥合人机智能。

##### URL
[https://arxiv.org/abs/1805.07526](https://arxiv.org/abs/1805.07526)

##### PDF
[https://arxiv.org/pdf/1805.07526](https://arxiv.org/pdf/1805.07526)

