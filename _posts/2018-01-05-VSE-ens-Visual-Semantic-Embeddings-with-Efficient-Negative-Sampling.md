---
layout: post
title: "VSE-ens: Visual-Semantic Embeddings with Efficient Negative Sampling"
date: 2018-01-05 05:19:37
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Guibing Guo, Songlin Zhai, Fajie Yuan, Yuan Liu, Xingwei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Jointing visual-semantic embeddings (VSE) have become a research hotpot for the task of image annotation, which suffers from the issue of semantic gap, i.e., the gap between images' visual features (low-level) and labels' semantic features (high-level). This issue will be even more challenging if visual features cannot be retrieved from images, that is, when images are only denoted by numerical IDs as given in some real datasets. The typical way of existing VSE methods is to perform a uniform sampling method for negative examples that violate the ranking order against positive examples, which requires a time-consuming search in the whole label space. In this paper, we propose a fast adaptive negative sampler that can work well in the settings of no figure pixels available. Our sampling strategy is to choose the negative examples that are most likely to meet the requirements of violation according to the latent factors of images. In this way, our approach can linearly scale up to large datasets. The experiments demonstrate that our approach converges 5.02x faster than the state-of-the-art approaches on OpenImages, 2.5x on IAPR-TCI2 and 2.06x on NUS-WIDE datasets, as well as better ranking accuracy across datasets.

##### Abstract (translated by Google)
视觉语义嵌入（visual-semantic embeddings，VSE）已成为图像标注任务的研究热点，存在语义间隙问题，即图像视觉特征（低级）与标签语义特征-水平）。如果不能从图像中检索视觉特征，那么这个问题将更具挑战性，也就是说，当图像仅由一些真实数据集中给出的数字ID表示时。现有的VSE方法的典型方法是针对违反排名顺序的否定实例针对正例进行统一的抽样方法，这在整个标签空间中需要耗费时间的搜索。在本文中，我们提出了一个快速自适应负采样器，可以在没有图像像素可用的设置下工作。我们的抽样策略是根据图像的潜在因素选择最有可能符合违规要求的反例。这样，我们的方法可以线性扩展到大型数据集。实验表明，我们的方法比OpenImages上的最新方法快5.02倍，IAPR-TCI2上2.5x，NUS-WIDE数据集上2.06x，以及数据集上更好的排序准确性。

##### URL
[http://arxiv.org/abs/1801.01632](http://arxiv.org/abs/1801.01632)

##### PDF
[http://arxiv.org/pdf/1801.01632](http://arxiv.org/pdf/1801.01632)

