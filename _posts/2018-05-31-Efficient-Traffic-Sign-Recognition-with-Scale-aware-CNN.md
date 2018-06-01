---
layout: post
title: "Efficient Traffic-Sign Recognition with Scale-aware CNN"
date: 2018-05-31 02:09:20
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Detection Recognition
author: Yuchen Yang, Shuo Liu, Wei Ma, Qiuyuan Wang, Zheng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
The paper presents a Traffic Sign Recognition (TSR) system, which can fast and accurately recognize traffic signs of different sizes in images. The system consists of two well-designed Convolutional Neural Networks (CNNs), one for region proposals of traffic signs and one for classification of each region. In the proposal CNN, a Fully Convolutional Network (FCN) with a dual multi-scale architecture is proposed to achieve scale invariant detection. In training the proposal network, a modified "Online Hard Example Mining" (OHEM) scheme is adopted to suppress false positives. The classification network fuses multi-scale features as representation and adopts an "Inception" module for efficiency. We evaluate the proposed TSR system and its components with extensive experiments. Our method obtains $99.88\%$ precision and $96.61\%$ recall on the Swedish Traffic Signs Dataset (STSD), higher than state-of-the-art methods. Besides, our system is faster and more lightweight than state-of-the-art deep learning networks for traffic sign recognition.

##### Abstract (translated by Google)
本文提出了一种交通标志识别（TSR）系统，该系统可以快速准确地识别出图像中不同大小的交通标志。该系统由两个设计良好的卷积神经网络（CNN）组成，一个用于交通标志的地区建议，另一个用于每个地区的分类。在CNN的提案中，提出了一种具有双重多尺度结构的全卷积网络（FCN）来实现尺度不变检测。在培训提案网络时，采用修改的“在线硬件示例挖掘”（OHEM）方案来抑制误报。分类网络将多尺度特征融合为代表性，并采用“初始”模块以提高效率。我们通过广泛的实验来评估提议的TSR系统及其组件。我们的方法在瑞典交通标志数据集（STSD）上获得$ 99.88 \％$精度和$ 96.61 \％$回忆，高于最先进的方法。此外，我们的系统比用于交通标志识别的最先进的深度学习网络更快，更轻量。

##### URL
[http://arxiv.org/abs/1805.12289](http://arxiv.org/abs/1805.12289)

##### PDF
[http://arxiv.org/pdf/1805.12289](http://arxiv.org/pdf/1805.12289)

