---
layout: post
title: "Adversarial Networks for the Detection of Aggressive Prostate Cancer"
date: 2017-02-26 10:08:49
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN Semantic_Segmentation Deep_Learning Detection
author: Simon Kohl, David Bonekamp, Heinz-Peter Schlemmer, Kaneschka Yaqubi, Markus Hohenfellner, Boris Hadaschik, Jan-Philipp Radtke, Klaus Maier-Hein
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation constitutes an integral part of medical image analyses for which breakthroughs in the field of deep learning were of high relevance. The large number of trainable parameters of deep neural networks however renders them inherently data hungry, a characteristic that heavily challenges the medical imaging community. Though interestingly, with the de facto standard training of fully convolutional networks (FCNs) for semantic segmentation being agnostic towards the `structure' of the predicted label maps, valuable complementary information about the global quality of the segmentation lies idle. In order to tap into this potential, we propose utilizing an adversarial network which discriminates between expert and generated annotations in order to train FCNs for semantic segmentation. Because the adversary constitutes a learned parametrization of what makes a good segmentation at a global level, we hypothesize that the method holds particular advantages for segmentation tasks on complex structured, small datasets. This holds true in our experiments: We learn to segment aggressive prostate cancer utilizing MRI images of 152 patients and show that the proposed scheme is superior over the de facto standard in terms of the detection sensitivity and the dice-score for aggressive prostate cancer. The achieved relative gains are shown to be particularly pronounced in the small dataset limit.

##### Abstract (translated by Google)
语义分割是医学图像分析的一个组成部分，因此深度学习领域的突破是高度相关的。然而，深度神经网络的大量可训练参数使得它们本身具有数据饥饿性，这是对医学成像群体造成严重挑战的特征。虽然有意思的是，事实上对于语义分割的完全卷积网络（FCN）的标准训练对于预测标签图的“结构”是不可知的，关于分割的全局质量的有价值的补充信息处于闲置状态。为了挖掘这种潜力，我们提出利用对抗网络来区分专家和生成的注释，以便训练用于语义分割的FCN。由于对手构成了在全球范围内进行良好分割的学习参数化，我们推测该方法对于复杂结构化的小数据集上的分割任务具有特别的优势。这在我们的实验中也是如此：我们学习利用152名患者的MRI图像来分割侵袭性前列腺癌，并且表明所提出的方案在检测敏感性和侵袭性前列腺癌的骰子评分方面优于事实标准。所显示的相对收益在小数据集限制中显示得尤其明显。

##### URL
[https://arxiv.org/abs/1702.08014](https://arxiv.org/abs/1702.08014)

##### PDF
[https://arxiv.org/pdf/1702.08014](https://arxiv.org/pdf/1702.08014)

