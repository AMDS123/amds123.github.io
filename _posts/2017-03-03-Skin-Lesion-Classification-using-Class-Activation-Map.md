---
layout: post
title: "Skin Lesion Classification using Class Activation Map"
date: 2017-03-03 06:38:30
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Xi Jia, Linlin Shen
mathjax: true
---

* content
{:toc}

##### Abstract
We proposed a two stage framework with only one network to analyze skin lesion images, we firstly trained a convolutional network to classify these images, and cropped the import regions which the network has the maximum activation value. In the second stage, we retrained this CNN with the image regions extracted from stage one and output the final probabilities. The two stage framework achieved a mean AUC of 0.857 in ISIC-2017 skin lesion validation set and is 0.04 higher than that of the original inputs, 0.821.

##### Abstract (translated by Google)
我们提出了一个只有一个网络的两阶段框架来分析皮肤病变图像，我们首先训练卷积网络对这些图像进行分类，并裁剪网络具有最大激活值的输入区域。在第二阶段，我们重新训练这个CNN与从第一阶段提取的图像区域，并输出最终的概率。两阶段框架在ISIC-2017皮肤损伤验证组中达到了0.857的平均AUC，比原始投入0.821高出0.04。

##### URL
[https://arxiv.org/abs/1703.01053](https://arxiv.org/abs/1703.01053)

##### PDF
[https://arxiv.org/pdf/1703.01053](https://arxiv.org/pdf/1703.01053)

