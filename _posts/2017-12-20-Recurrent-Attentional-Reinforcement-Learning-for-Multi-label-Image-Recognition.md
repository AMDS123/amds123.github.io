---
layout: post
title: "Recurrent Attentional Reinforcement Learning for Multi-label Image Recognition"
date: 2017-12-20 13:14:46
categories: arXiv_CV
tags: arXiv_CV Attention Reinforcement_Learning CNN Recognition
author: Tianshui Chen, Zhouxia Wang, Guanbin Li, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing multiple labels of images is a fundamental but challenging task in computer vision, and remarkable progress has been attained by localizing semantic-aware image regions and predicting their labels with deep convolutional neural networks. The step of hypothesis regions (region proposals) localization in these existing multi-label image recognition pipelines, however, usually takes redundant computation cost, e.g., generating hundreds of meaningless proposals with non-discriminative information and extracting their features, and the spatial contextual dependency modeling among the localized regions are often ignored or over-simplified. To resolve these issues, this paper proposes a recurrent attention reinforcement learning framework to iteratively discover a sequence of attentional and informative regions that are related to different semantic objects and further predict label scores conditioned on these regions. Besides, our method explicitly models long-term dependencies among these attentional regions that help to capture semantic label co-occurrence and thus facilitate multi-label recognition. Extensive experiments and comparisons on two large-scale benchmarks (i.e., PASCAL VOC and MS-COCO) show that our model achieves superior performance over existing state-of-the-art methods in both performance and efficiency as well as explicitly identifying image-level semantic labels to specific object regions.

##### Abstract (translated by Google)
识别图像的多个标签是计算机视觉中的基本但是具有挑战性的任务，并且通过使用深度卷积神经网络来定位语义感知的图像区域并且预测它们的标签已经获得了显着的进步。然而，在这些现有的多标签图像识别流水线中，假设区域（区域提议）定位的步骤通常需要冗余计算成本，例如，生成数百个无歧视信息并提取其特征的无意义提议，以及空间上下文相关性在局部地区之间的建模往往被忽略或过度简化。为了解决这些问题，本文提出了一种反复注意力强化学习框架，用于迭代地发现与不同语义对象相关的一系列注意和信息区域，并进一步预测这些区域的标签分数。此外，我们的方法明确地建模这些注意区域之间的长期依赖关系，有助于捕获语义标签共现，从而促进多标签识别。对两个大型基准（即PASCAL VOC和MS-COCO）的大量实验和比较表明，我们的模型在性能和效率方面都比现有的最先进的方法实现了卓越的性能，并且明确地确定了图像水平语义标签到特定的对象区域。

##### URL
[https://arxiv.org/abs/1712.07465](https://arxiv.org/abs/1712.07465)

##### PDF
[https://arxiv.org/pdf/1712.07465](https://arxiv.org/pdf/1712.07465)

