---
layout: post
title: "Adaptive Affinity Field for Semantic Segmentation"
date: 2018-03-27 21:21:57
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Semantic_Segmentation Inference Prediction Relation
author: Tsung-Wei Ke, Jyh-Jing Hwang, Ziwei Liu, Stella X. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Existing semantic segmentation methods mostly rely on per-pixel supervision, unable to capture structural regularity present in natural images. Instead of learning to enforce semantic labels on individual pixels, we propose to enforce affinity field patterns in individual pixel neighbourhoods, i.e., the semantic label patterns of whether neighbouring pixels are in the same segment should match between the prediction and the ground-truth. The affinity fields characterize geometric relationships within the image, such as "motorcycles have round wheels". We further develop a novel method for learning the optimal neighbourhood size for each semantic category, with an adversarial loss that optimizes over worst-case scenarios. Unlike the common Conditional Random Field (CRF) approaches, our adaptive affinity field (AAF) method has no extra parameters during inference, and is less sensitive to appearance changes in the image. Extensive evaluations on Cityscapes, PASCAL VOC 2012 and GTA5 datasets demonstrate the effectiveness and robustness of AAF in semantic segmentation.

##### Abstract (translated by Google)
现有的语义分割方法主要依赖于每像素监督，无法捕捉自然图像中存在的结构规则。我们建议在单个像素邻域中强制使用亲和性字段模式，即，相邻像素是否在同一个段中的语义标签模式应该与预测和基础事实相匹配，而不是学习在单个像素上强制执行语义标签。亲和性字段表征图像内的几何关系，例如“摩托车具有圆形轮子”。我们进一步开发了一种用于学习每个语义类别的最佳邻域大小的新方法，其中对抗性损失在最坏情况下优化。与常见的条件随机场（CRF）方法不同，我们的自适应亲和场（AAF）方法在推理期间没有额外的参数，并且对图像中的外观变化不太敏感。对Cityscapes，PASCAL VOC 2012和GTA5数据集的广泛评估证明了AAF在语义分割中的有效性和鲁棒性。

##### URL
[https://arxiv.org/abs/1803.10335](https://arxiv.org/abs/1803.10335)

##### PDF
[https://arxiv.org/pdf/1803.10335](https://arxiv.org/pdf/1803.10335)

