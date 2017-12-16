---
layout: post
title: "Deep Learning for Target Classification from SAR Imagery: Data Augmentation and Translation Invariance"
date: 2017-08-26 02:44:09
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Recognition
author: Hidetoshi Furukawa
mathjax: true
---

* content
{:toc}

##### Abstract
This report deals with translation invariance of convolutional neural networks (CNNs) for automatic target recognition (ATR) from synthetic aperture radar (SAR) imagery. In particular, the translation invariance of CNNs for SAR ATR represents the robustness against misalignment of target chips extracted from SAR images. To understand the translation invariance of the CNNs, we trained CNNs which classify the target chips from the MSTAR into the ten classes under the condition of with and without data augmentation, and then visualized the translation invariance of the CNNs. According to our results, even if we use a deep residual network, the translation invariance of the CNN without data augmentation using the aligned images such as the MSTAR target chips is not so large. A more important factor of translation invariance is the use of augmented training data. Furthermore, our CNN using augmented training data achieved a state-of-the-art classification accuracy of 99.6%. These results show an importance of domain-specific data augmentation.

##### Abstract (translated by Google)
本报告涉及从合成孔径雷达（SAR）图像中自动目标识别（ATR）的卷积神经网络（CNN）的平移不变性。特别是SAR ATR的CNN的平移不变性代表了从SAR图像中提取的目标码片未对准的鲁棒性。为了理解CNN的平移不变性，在有和没有数据增加的情况下，对MSTAR中的目标码片进行了10类分类训练，然后对CNN的平移不变性进行可视化。根据我们的结果，即使我们使用深度残差网络，使用诸如MSTAR目标芯片的对准图像的没有数据增强的CNN的平移不变性也不是那么大。翻译不变性的一个更重要的因素是使用增强的训练数据。此外，使用增强训练数据的CNN达到了99.6％的最新分类精度。这些结果显示了特定领域的数据增强的重要性。

##### URL
[https://arxiv.org/abs/1708.07920](https://arxiv.org/abs/1708.07920)

##### PDF
[https://arxiv.org/pdf/1708.07920](https://arxiv.org/pdf/1708.07920)

