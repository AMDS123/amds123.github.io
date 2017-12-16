---
layout: post
title: "Deep Co-Space: Sample Mining Across Feature Transformation for Semi-Supervised Learning"
date: 2017-07-28 06:41:34
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Relation
author: Ziliang Chen, Keze Wang, Xiao Wang, Pai Peng, Ebroul Izquierdo, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Aiming at improving performance of visual classification in a cost-effective manner, this paper proposes an incremental semi-supervised learning paradigm called Deep Co-Space (DCS). Unlike many conventional semi-supervised learning methods usually performing within a fixed feature space, our DCS gradually propagates information from labeled samples to unlabeled ones along with deep feature learning. We regard deep feature learning as a series of steps pursuing feature transformation, i.e., projecting the samples from a previous space into a new one, which tends to select the reliable unlabeled samples with respect to this setting. Specifically, for each unlabeled image instance, we measure its reliability by calculating the category variations of feature transformation from two different neighborhood variation perspectives, and merged them into an unified sample mining criterion deriving from Hellinger distance. Then, those samples keeping stable correlation to their neighboring samples (i.e., having small category variation in distribution) across the successive feature space transformation, are automatically received labels and incorporated into the model for incrementally training in terms of classification. Our extensive experiments on standard image classification benchmarks (e.g., Caltech-256 and SUN-397) demonstrate that the proposed framework is capable of effectively mining from large-scale unlabeled images, which boosts image classification performance and achieves promising results compared to other semi-supervised learning methods.

##### Abstract (translated by Google)
为了提高视觉分类的性能，本文提出了一种称为Deep Co-Space（DCS）的增量式半监督学习范式。与许多传统的半监督学习方法（通常在一个固定的特征空间内执行）不同，我们的DCS将信息从标记的样本逐渐传播到未标记的样本，同时进行深度特征学习。我们把深度特征学习看作是一系列的特征变换步骤，即将样本从前一个空间投影到一个新的空间，这样就倾向于选择可靠的未标记样本。具体来说，对于每个未标记的图像实例，我们通过计算来自两个不同邻域变化视角的特征变换的类别变化来测量其可靠性，并将其合并成由海灵格距离导出的统一的采样标准。然后，在连续的特征空间变换中保持与其相邻样本稳定相关的那些样本（即，具有较小的分布变化类型）被自动接收到标签，并被结合到用于在分类方面递增训练的模型中。我们在标准图像分类基准（如Caltech-256和SUN-397）上的广泛实验表明，所提出的框架能够有效地从大规模未标记图像中挖掘出来，与其他半融合图像相比，提高了图像分类性能，监督学习方法。

##### URL
[https://arxiv.org/abs/1707.09119](https://arxiv.org/abs/1707.09119)

##### PDF
[https://arxiv.org/pdf/1707.09119](https://arxiv.org/pdf/1707.09119)

