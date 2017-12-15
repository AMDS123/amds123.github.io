---
layout: post
title: "Sample and Filter: Nonparametric Scene Parsing via Efficient Filtering"
date: 2016-03-15 01:29:03
categories: arXiv_CV
tags: arXiv_CV Attention
author: Mohammad Najafi, Sarah Taghavi Namin, Mathieu Salzmann, Lars Petersson
mathjax: true
---

* content
{:toc}

##### Abstract
Scene parsing has attracted a lot of attention in computer vision. While parametric models have proven effective for this task, they cannot easily incorporate new training data. By contrast, nonparametric approaches, which bypass any learning phase and directly transfer the labels from the training data to the query images, can readily exploit new labeled samples as they become available. Unfortunately, because of the computational cost of their label transfer procedures, state-of-the-art nonparametric methods typically filter out most training images to only keep a few relevant ones to label the query. As such, these methods throw away many images that still contain valuable information and generally obtain an unbalanced set of labeled samples. In this paper, we introduce a nonparametric approach to scene parsing that follows a sample-and-filter strategy. More specifically, we propose to sample labeled superpixels according to an image similarity score, which allows us to obtain a balanced set of samples. We then formulate label transfer as an efficient filtering procedure, which lets us exploit more labeled samples than existing techniques. Our experiments evidence the benefits of our approach over state-of-the-art nonparametric methods on two benchmark datasets.

##### Abstract (translated by Google)
场景解析在计算机视觉中引起了很多关注。虽然参数模型已经证明对这项任务有效，但他们不能轻易地整合新的训练数据。相比之下，绕过任何学习阶段并直接将标记从训练数据转移到查询图像的非参数方法可以容易地利用新标记的样本。不幸的是，由于其标签传输过程的计算成本，最先进的非参数方法通常会过滤出大多数训练图像，只保留一些相关的标签来查询。因此，这些方法丢弃了许多仍然包含有价值信息的图像，并且通常获得一组不平衡的标记样本。在本文中，我们介绍了一种采用抽样和过滤策略的非参数化场景解析方法。更具体地说，我们建议根据图像相似性分数来标记超级像素，这样我们就可以获得一组平衡的样本。然后，我们将标签转换制定为一个有效的过滤程序，使我们可以利用比现有技术更多的标签样本。我们的实验证明了我们的方法相对于两个基准数据集上的最先进的非参数方法的好处。

##### URL
[https://arxiv.org/abs/1511.04960](https://arxiv.org/abs/1511.04960)

##### PDF
[https://arxiv.org/pdf/1511.04960](https://arxiv.org/pdf/1511.04960)

