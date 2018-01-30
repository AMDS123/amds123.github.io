---
layout: post
title: "Shift-Net: Image Inpainting via Deep Feature Rearrangement"
date: 2018-01-29 08:13:49
categories: arXiv_CV
tags: arXiv_CV CNN
author: Zhaoyi Yan, Xiaoming Li, Mu Li, Wangmeng Zuo, Shiguang Shan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional networks (CNNs) have exhibited their potential in image inpainting for producing plausible results.However, in most existing methods, e.g., context encoder, the missing parts are predicted by propagating the surrounding convolutional features through a fully connected layer, which intends to produce semantically plausible but blurry result. In this paper, we introduce a special shift-connection layer to the U-Net architecture, namely Shift-Net, for filling in missing regions of any shape with sharp structures and fine-detailed textures. To this end, the encoder feature of the known region is shifted to serve as an estimation of the missing parts. A guidance loss is introduced on decoder feature to minimize the distance between the decoder feature after fully connected layer and the ground truth encoder feature of the missing parts. With such constraint, the decoder feature in missing region can be used to guide the shift of encoder feature in known region. An end-to-end learning algorithm is further developed to train the Shift-Net. Experiments on the Paris StreetView and Places datasets demonstrate the efficiency and effectiveness of our Shift-Net in producing sharper, fine-detailed, and visually plausible results.

##### Abstract (translated by Google)
深卷积网络（CNNs）已经在图像修复方面展现出其可能结果的潜力。然而，在大多数现有的方法，例如上下文编码器中，通过将完整连接层传播周围卷积特征来预测缺失部分，产生语义上似是而非的模糊结果。在本文中，我们在U-Net架构中引入了一个特殊的移位连接层，即Shift-Net，用于填充具有尖锐结构和精细纹理的任何形状的缺失区域。为此，已知区域的编码器特征被移位以用作对缺失部分的估计。在解码器特征上引入了引导损失，以使完全连接层之后的解码器特征与缺失部分的地面实况编码器特征之间的距离最小化。在这样的约束条件下，可以使用缺失区域的解码器特征来引导已知区域中编码器特征的偏移。进一步发展端对端学习算法来训练Shift-Net。在巴黎StreetView和Places数据集上的实验证明了我们的Shift-Net在生成更清晰，细致和视觉上合理的结果方面的效率和有效性。

##### URL
[http://arxiv.org/abs/1801.09392](http://arxiv.org/abs/1801.09392)

##### PDF
[http://arxiv.org/pdf/1801.09392](http://arxiv.org/pdf/1801.09392)

