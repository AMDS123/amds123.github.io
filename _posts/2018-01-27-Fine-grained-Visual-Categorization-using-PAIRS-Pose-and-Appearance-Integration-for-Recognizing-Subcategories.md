---
layout: post
title: "Fine-grained Visual Categorization using PAIRS: Pose and Appearance Integration for Recognizing Subcategories"
date: 2018-01-27 08:53:29
categories: arXiv_CV
tags: arXiv_CV Attention Classification Prediction
author: Pei Guo, Ryan Farrell
mathjax: true
---

* content
{:toc}

##### Abstract
In Fine-grained Visual Categorization (FGVC), the differences between similar categories are often highly localized to a small number of object parts, and significant pose variation therefore constitutes a great challenge for identification. To address this, we propose extracting image patches using pairs of predicted keypoint locations as anchor points. The benefits of this approach are two-fold: (1) it achieves explicit top-down visual attention on object parts, and (2) the extracted patches are pose-aligned and thus contain stable appearance features. We employ the popular Stacked Hourglass Network to predict keypoint locations, reporting state-of-the-art keypoint localization results on the challenging CUB-200-2011 dataset. Anchored by these predicted keypoints, an overcomplete basis of pose-aligned patches is extracted and a specialized appearance classification network is trained for each patch. An aggregating network is then applied to combine the patch networks' individual predictions, producing a final classification score. Our PAIRS algorithm attains an accuracy of 88.6%, an increase of 1.1% over the current state-of-the-art. Enhancing the base PAIRS model with single-keypoint patches produces a further improvement, yielding a new state-of-the-art accuracy of 89.2% on the CUB dataset and clearly demonstrating the power of integrating pose and appearance features.

##### Abstract (translated by Google)
在细粒度视觉分类（FGVC）中，相似类别之间的差异通常高度局限于少数目标部分，因此显着的姿态变化对识别构成巨大挑战。为了解决这个问题，我们提出使用预测的关键点位置对作为定位点来提取图像块。这种方法的好处是双重的：（1）它实现了明确的自上而下的视觉注意对象部分，（2）提取的补丁是姿势对齐，因此包含稳定的外观特征。我们采用流行的堆积沙漏网络来预测关键点的位置，报告具有挑战性的CUB-200-2011数据集上最先进的关键点定位结果。以这些预测的关键点为基础，提取姿态对齐补丁的过度完备基础，并针对每个补丁训练专门的外观分类网络。然后应用汇总网络来组合补丁网络的个人预测，产生最终的分类分数。我们的PAIRS算法达到了88.6％的精确度，比现有技术水平提高了1.1％。使用单关键点补丁增强基础对比模型会进一步改进，在CUB数据集上产生89.2％的新的最新准确度，并清楚地展示整合姿态和外观特征的能力。

##### URL
[http://arxiv.org/abs/1801.09057](http://arxiv.org/abs/1801.09057)

##### PDF
[http://arxiv.org/pdf/1801.09057](http://arxiv.org/pdf/1801.09057)

