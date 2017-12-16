---
layout: post
title: "Object Region Mining with Adversarial Erasing: A Simple Classification to Semantic Segmentation Approach"
date: 2017-03-27 07:23:05
categories: arXiv_CV
tags: arXiv_CV Adversarial Sparse Segmentation Semantic_Segmentation Inference Classification
author: Yunchao Wei, Jiashi Feng, Xiaodan Liang, Ming-Ming Cheng, Yao Zhao, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate a principle way to progressively mine discriminative object regions using classification networks to address the weakly-supervised semantic segmentation problems. Classification networks are only responsive to small and sparse discriminative regions from the object of interest, which deviates from the requirement of the segmentation task that needs to localize dense, interior and integral regions for pixel-wise inference. To mitigate this gap, we propose a new adversarial erasing approach for localizing and expanding object regions progressively. Starting with a single small object region, our proposed approach drives the classification network to sequentially discover new and complement object regions by erasing the current mined regions in an adversarial manner. These localized regions eventually constitute a dense and complete object region for learning semantic segmentation. To further enhance the quality of the discovered regions by adversarial erasing, an online prohibitive segmentation learning approach is developed to collaborate with adversarial erasing by providing auxiliary segmentation supervision modulated by the more reliable classification scores. Despite its apparent simplicity, the proposed approach achieves 55.0% and 55.7% mean Intersection-over-Union (mIoU) scores on PASCAL VOC 2012 val and test sets, which are the new state-of-the-arts.

##### Abstract (translated by Google)
我们调查一个原则的方法逐步挖掘区分对象区域使用分类网络来解决弱监督的语义分割问题。分类网络只对来自感兴趣对象的小和稀疏区域敏感，这偏离了需要为像素级推理定位稠密，内部和整体区域的分割任务的需求。为了缓解这种差距，我们提出了一种新的敌对擦除方法，用于逐步定位和扩展目标区域。从单个小物体区域开始，我们提出的方法驱动分类网络，通过以对抗方式擦除当前开采区域，顺序发现新的和补充的物体区域。这些局部区域最终构成了用于学习语义分割的密集且完整的对象区域。为了进一步提高对对象擦除发现区域的质量，开发了一种在线禁止性分割学习方法，通过提供由更可靠的分类评分调制的辅助分割监督来与敌对擦除进行协作。尽管其表面简单，但所提出的方法在PASCAL VOC 2012 val和测试集上的平均交叉点（mIoU）分数达到55.0％和55.7％，这是新的技术水平。

##### URL
[https://arxiv.org/abs/1703.08448](https://arxiv.org/abs/1703.08448)

##### PDF
[https://arxiv.org/pdf/1703.08448](https://arxiv.org/pdf/1703.08448)

