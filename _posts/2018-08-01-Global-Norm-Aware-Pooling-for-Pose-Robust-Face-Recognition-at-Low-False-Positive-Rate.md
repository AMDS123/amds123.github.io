---
layout: post
title: "Global Norm-Aware Pooling for Pose-Robust Face Recognition at Low False Positive Rate"
date: 2018-08-01 17:32:31
categories: arXiv_CV
tags: arXiv_CV Face Embedding CNN Recognition Face_Recognition
author: Sheng Chen, Jia Guo, Yang Liu, Xiang Gao, Zhen Han
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel Global Norm-Aware Pooling (GNAP) block, which reweights local features in a convolutional neural network (CNN) adaptively according to their L2 norms and outputs a global feature vector with a global average pooling layer. Our GNAP block is designed to give dynamic weights to local features in different spatial positions without losing spatial symmetry. We use a GNAP block in a face feature embedding CNN to produce discriminative face feature vectors for pose-robust face recognition. The GNAP block is of very cheap computational cost, but it is very powerful for frontal-profile face recognition. Under the CFP frontal-profile protocol, the GNAP block can not only reduce EER dramatically but also boost TPR@FPR=0.1% (TPR i.e. True Positive Rate, FPR i.e. False Positive Rate) substantially. Our experiments show that the GNAP block greatly promotes pose-robust face recognition over the base model especially at low false positive rate.

##### Abstract (translated by Google)
在本文中，我们提出了一种新颖的全局规范感知池（GNAP）块，它根据其L2规范自适应地重新计算卷积神经网络（CNN）中的局部特征，并输出具有全局平均池层的全局特征向量。我们的GNAP模块旨在为不同空间位置的局部特征提供动态权重，而不会失去空间对称性。我们在嵌入CNN的面部特征中使用GNAP块来产生用于姿势稳健的面部识别的辨别面部特征向量。 GNAP块具有非常便宜的计算成本，但它对于正面轮廓面部识别非常有用。在CFP正面轮廓协议下，GNAP块不仅可以显着降低EER，而且还可以大幅提升TPR@FPR=0.1%(TPR，即真正正率，FPR，即假阳性率）。我们的实验表明，GNAP块在基础模型上极大地促进了姿势稳健的人脸识别，特别是在低误报率时。

##### URL
[https://arxiv.org/abs/1808.00435](https://arxiv.org/abs/1808.00435)

##### PDF
[https://arxiv.org/pdf/1808.00435](https://arxiv.org/pdf/1808.00435)

