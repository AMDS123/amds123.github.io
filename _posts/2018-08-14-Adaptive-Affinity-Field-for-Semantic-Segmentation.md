---
layout: post
title: "Adaptive Affinity Field for Semantic Segmentation"
date: 2018-08-14 06:32:58
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Semantic_Segmentation Inference Relation
author: Tsung-Wei Ke, Jyh-Jing Hwang, Ziwei Liu, Stella X. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation has made much progress with increasingly powerful pixel-wise classifiers and incorporating structural priors via Conditional Random Fields (CRF) or Generative Adversarial Networks (GAN). We propose a simpler alternative that learns to verify the spatial structure of segmentation during training only. Unlike existing approaches that enforce semantic labels on individual pixels and match labels between neighbouring pixels, we propose the concept of Adaptive Affinity Fields (AAF) to capture and match the semantic relations between neighbouring pixels in the label space. We use adversarial learning to select the optimal affinity field size for each semantic category. It is formulated as a minimax problem, optimizing our segmentation neural network in a best worst-case learning scenario. AAF is versatile for representing structures as a collection of pixel-centric relations, easier to train than GAN and more efficient than CRF without run-time inference. Our extensive evaluations on PASCAL VOC 2012, Cityscapes, and GTA5 datasets demonstrate its above-par segmentation performance and robust generalization across domains.

##### Abstract (translated by Google)
语义分割已经通过越来越强大的像素分类器和通过条件随机场（CRF）或生成对抗网络（GAN）结合结构先验而取得了很大进展。我们提出了一种更简单的替代方案，可以在训练期间学习验证分割的空间结构。与在单个像素上强制语义标签并在相邻像素之间匹配标签的现有方法不同，我们提出自适应亲和场（AAF）的概念来捕获和匹配标签空间中的相邻像素之间的语义关系。我们使用对抗性学习为每个语义类别选择最佳亲和力字段大小。它被制定为一个极小极大问题，在最好的最坏情况学习场景中优化我们的分段神经网络。 AAF用于将结构表示为像素中心关系的集合，比GAN更容易训练，并且比没有运行时推断的CRF更有效。我们对PASCAL VOC 2012，Cityscapes和GTA5数据集的广泛评估证明了其高于分区的分段性能和跨域的强大泛化。

##### URL
[http://arxiv.org/abs/1803.10335](http://arxiv.org/abs/1803.10335)

##### PDF
[http://arxiv.org/pdf/1803.10335](http://arxiv.org/pdf/1803.10335)

