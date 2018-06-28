---
layout: post
title: "Attention to Head Locations for Crowd Counting"
date: 2018-06-27 03:52:19
categories: arXiv_CV
tags: arXiv_CV Sparse Attention CNN
author: Youmei Zhang, Chunluan Zhou, Faliang Chang, Alex C. Kot
mathjax: true
---

* content
{:toc}

##### Abstract
Occlusions, complex backgrounds, scale variations and non-uniform distributions present great challenges for crowd counting in practical applications. In this paper, we propose a novel method using an attention model to exploit head locations which are the most important cue for crowd counting. The attention model estimates a probability map in which high probabilities indicate locations where heads are likely to be present. The estimated probability map is used to suppress non-head regions in feature maps from several multi-scale feature extraction branches of a convolution neural network for crowd density estimation, which makes our method robust to complex backgrounds, scale variations and non-uniform distributions. In addition, we introduce a relative deviation loss to compensate a commonly used training loss, Euclidean distance, to improve the accuracy of sparse crowd density estimation. Experiments on Shanghai-Tech, UCF_CC_50 and World-Expo'10 data sets demonstrate the effectiveness of our method.

##### Abstract (translated by Google)
在实际应用中，遮挡，复杂背景，尺度变化和非均匀分布对人群计数提出了巨大挑战。在本文中，我们提出了一种使用注意模型来开发头部位置的新方法，这是人群计数最重要的线索。注意模型估计概率图，其中高概率指示头可能存在的位置。估计概率图用于抑制来自卷积神经网络的多个多尺度特征提取分支的特征映射中的非头部区域以用于人群密度估计，这使得我们的方法对于复杂背景，尺度变化和非均匀分布是鲁棒的。此外，我们引入相对偏差损失来补偿常用的训练损失欧几里德距离，以提高稀疏人群密度估计的准确性。上海科技，UCF_CC_50和World-Expo'10数据集的实验证明了我们方法的有效性。

##### URL
[http://arxiv.org/abs/1806.10287](http://arxiv.org/abs/1806.10287)

##### PDF
[http://arxiv.org/pdf/1806.10287](http://arxiv.org/pdf/1806.10287)

