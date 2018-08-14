---
layout: post
title: "VSE-ens: Visual-Semantic Embeddings with Efficient Negative Sampling"
date: 2018-08-11 08:58:05
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
连接视觉语义嵌入（VSE）已经成为图像标注任务的研究热点，它受到语义空白问题的困扰，即图像的视觉特征（低级）和标签的语义特征之间的差距（高） -水平）。如果无法从图像中检索视觉特征，即当图像仅由某些真实数据集中给出的数字ID表示时，此问题将更具挑战性。现有VSE方法的典型方式是对违反排名顺序的反例执行统一的采样方法，这需要在整个标签空间中进行耗时的搜索。在本文中，我们提出了一种快速自适应负采样器，它可以在没有图像像素的情况下很好地工作。我们的抽样策略是根据图像的潜在因素选择最有可能满足违规要求的反面例子。通过这种方式，我们的方法可以线性扩展到大型数据集。实验表明，我们的方法比OpenImages上的最先进方法快了5.02倍，IAPR-TCI2上的2.5倍和NUS-WIDE数据集上的2.06倍，以及更好的数据集排名准确性。

##### URL
[http://arxiv.org/abs/1801.01632](http://arxiv.org/abs/1801.01632)

##### PDF
[http://arxiv.org/pdf/1801.01632](http://arxiv.org/pdf/1801.01632)

