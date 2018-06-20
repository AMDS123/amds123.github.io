---
layout: post
title: "Cancer Metastasis Detection With Neural Conditional Random Field"
date: 2018-06-19 06:44:34
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Prediction Detection Relation
author: Yi Li, Wei Ping
mathjax: true
---

* content
{:toc}

##### Abstract
Breast cancer diagnosis often requires accurate detection of metastasis in lymph nodes through Whole-slide Images (WSIs). Recent advances in deep convolutional neural networks (CNNs) have shown significant successes in medical image analysis and particularly in computational histopathology. Because of the outrageous large size of WSIs, most of the methods divide one slide into lots of small image patches and perform classification on each patch independently. However, neighboring patches often share spatial correlations, and ignoring these spatial correlations may result in inconsistent predictions. In this paper, we propose a neural conditional random field (NCRF) deep learning framework to detect cancer metastasis in WSIs. NCRF considers the spatial correlations between neighboring patches through a fully connected CRF which is directly incorporated on top of a CNN feature extractor. The whole deep network can be trained end-to-end with standard back-propagation algorithm with minor computational overhead from the CRF component. The CNN feature extractor can also benefit from considering spatial correlations via the CRF component. Compared to the baseline method without considering spatial correlations, we show that the proposed NCRF framework obtains probability maps of patch predictions with better visual quality. We also demonstrate that our method outperforms the baseline in cancer metastasis detection on the Camelyon16 dataset and achieves an average FROC score of 0.8096 on the test set. NCRF is open sourced at https://github.com/baidu-research/NCRF.

##### Abstract (translated by Google)
乳腺癌的诊断往往需要通过整张幻灯片图像（WSIs）准确检测淋巴结转移。深度卷积神经网络（CNNs）的最新进展已经在医学图像分析，特别是计算组织病理学中显示出显着的成功。由于WSI的规模过大，大多数方法会将一张幻灯片分成许多小图像补丁，并独立对每个补丁执行分类。但是，相邻贴片通常会共享空间相关性，而忽略这些空间相关性可能会导致预测结果不一致。在本文中，我们提出了一种神经条件随机场（NCRF）深度学习框架来检测WSIs中的癌症转移。 NCRF通过完全连接的CRF考虑相邻贴片之间的空间相关性，该CRF直接并入CNN特征提取器的顶部。整个深度网络可以通过标准的反向传播算法进行端对端训练，CRF组件的计算开销很小。 CNN特征提取器也可以通过CRF组件考虑空间相关性。与没有考虑空间相关性的基线方法相比，我们表明，所提出的NCRF框架获得具有更好视觉质量的修补预测的概率图。我们还证明，我们的方法优于Camelyon16数据集中癌症转移检测的基线，并且在测试集上实现平均FROC评分0.8096。 NCRF开放源于https://github.com/baidu-research/NCRF。

##### URL
[http://arxiv.org/abs/1806.07064](http://arxiv.org/abs/1806.07064)

##### PDF
[http://arxiv.org/pdf/1806.07064](http://arxiv.org/pdf/1806.07064)

