---
layout: post
title: "Self-produced Guidance for Weakly-supervised Object Localization"
date: 2018-07-24 04:35:44
categories: arXiv_CV
tags: arXiv_CV Sparse Attention Weakly_Supervised Classification Relation
author: Xiaolin Zhang, Yunchao Wei, Guoliang Kang, Yi Yang, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised methods usually generate localization results based on attention maps produced by classification networks. However, the attention maps exhibit the most discriminative parts of the object which are small and sparse. We propose to generate Self-produced Guidance (SPG) masks which separate the foreground, the object of interest, from the background to provide the classification networks with spatial correlation information of pixels. A stagewise approach is proposed to incorporate high confident object regions to learn the SPG masks. The high confident regions within attention maps are utilized to progressively learn the SPG masks. The masks are then used as an auxiliary pixel-level supervision to facilitate the training of classification networks. Extensive experiments on ILSVRC demonstrate that SPG is effective in producing high-quality object localizations maps. Particularly, the proposed SPG achieves the Top-1 localization error rate of 43.83% on the ILSVRC validation set, which is a new state-of-the-art error rate.

##### Abstract (translated by Google)
弱监督方法通常基于分类网络产生的关注图生成定位结果。然而，注意力图表现出对象的最具辨别力的部分，这些部分是小的和稀疏的。我们建议生成自生导引（SPG）掩模，其将前景，感兴趣对象与背景分离，以向分类网络提供像素的空间相关信息。提出了一种分阶段方法，以结合高可靠对象区域来学习SPG掩模。注意力图中的高置信区域用于逐步学习SPG掩模。然后将掩模用作辅助像素级监督，以便于分类网络的训练。对ILSVRC的广泛实验表明，SPG可有效地生成高质量的对象定位图。特别是，提出的SPG在ILSVRC验证集上实现了43.83％的Top-1定位错误率，这是一种新的最新错误率。

##### URL
[https://arxiv.org/abs/1807.08902](https://arxiv.org/abs/1807.08902)

##### PDF
[https://arxiv.org/pdf/1807.08902](https://arxiv.org/pdf/1807.08902)

