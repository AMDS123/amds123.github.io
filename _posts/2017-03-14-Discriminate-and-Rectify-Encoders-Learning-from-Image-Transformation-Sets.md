---
layout: post
title: "Discriminate-and-Rectify Encoders: Learning from Image Transformation Sets"
date: 2017-03-14 22:21:48
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised Face Embedding Classification Recognition
author: Andrea Tacchetti, Stephen Voinea, Georgios Evangelopoulos
mathjax: true
---

* content
{:toc}

##### Abstract
The complexity of a learning task is increased by transformations in the input space that preserve class identity. Visual object recognition for example is affected by changes in viewpoint, scale, illumination or planar transformations. While drastically altering the visual appearance, these changes are orthogonal to recognition and should not be reflected in the representation or feature encoding used for learning. We introduce a framework for weakly supervised learning of image embeddings that are robust to transformations and selective to the class distribution, using sets of transforming examples (orbit sets), deep parametrizations and a novel orbit-based loss. The proposed loss combines a discriminative, contrastive part for orbits with a reconstruction error that learns to rectify orbit transformations. The learned embeddings are evaluated in distance metric-based tasks, such as one-shot classification under geometric transformations, as well as face verification and retrieval under more realistic visual variability. Our results suggest that orbit sets, suitably computed or observed, can be used for efficient, weakly-supervised learning of semantically relevant image embeddings.

##### Abstract (translated by Google)
学习任务的复杂性通过在保持阶级身份的输入空间中的转换而增加。视觉对象识别例如受到视点，比例，照明或平面变换的变化的影响。虽然剧烈地改变了视觉外观，但这些改变与识别正交，不应该反映在用于学习的表示或特征编码中。我们引入了一个弱监督学习的图像嵌入框架，该框架对于变换是鲁棒的，对类分布是有选择性的，使用一组变换示例（轨道集），深度参数化和新的基于轨道的丢失。所提出的损失将轨道上的一个有区别的对比部分与重建误差结合起来，学习纠正轨道变换。学习到的嵌入在基于距离度量的任务中被评估，例如在几何变换下的一次分类，以及在更真实的视觉变化下的面部验证和检索。我们的研究结果表明，适当计算或观察的轨道集可以用于语义相关图像嵌入的有效，弱监督学习。

##### URL
[https://arxiv.org/abs/1703.04775](https://arxiv.org/abs/1703.04775)

##### PDF
[https://arxiv.org/pdf/1703.04775](https://arxiv.org/pdf/1703.04775)

