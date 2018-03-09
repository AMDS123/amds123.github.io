---
layout: post
title: "Instance Similarity Deep Hashing for Multi-Label Image Retrieval"
date: 2018-03-08 07:26:20
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Zheng Zhang, Qin Zou, Qian Wang, Yuewei Lin, Qingquan Li
mathjax: true
---

* content
{:toc}

##### Abstract
Hash coding has been widely used in the approximate nearest neighbor search for large-scale image retrieval. Recently, many deep hashing methods have been proposed and shown largely improved performance over traditional feature-learning-based methods. Most of these methods examine the pairwise similarity on the semantic-level labels, where the pairwise similarity is generally defined in a hard-assignment way. That is, the pairwise similarity is '1' if they share no less than one class label and '0' if they do not share any. However, such similarity definition cannot reflect the similarity ranking for pairwise images that hold multiple labels. In this paper, a new deep hashing method is proposed for multi-label image retrieval by re-defining the pairwise similarity into an instance similarity, where the instance similarity is quantified into a percentage based on the normalized semantic labels. Based on the instance similarity, a weighted cross-entropy loss and a minimum mean square error loss are tailored for loss-function construction, and are efficiently used for simultaneous feature learning and hash coding. Experiments on three popular datasets demonstrate that, the proposed method outperforms the competing methods and achieves the state-of-the-art performance in multi-label image retrieval.

##### Abstract (translated by Google)
散列编码已被广泛用于大规模图像检索的近似最近邻搜索。最近，已经提出了许多深度哈希方法，并且相比传统的基于特征学习的方法显示出大大改进的性能。这些方法中的大多数都检查语义级别标签上的成对相似性，其中成对相似性通常以难以分配的方式定义。也就是说，成对相似度如果共享不少于一个类别标签，则为'1'，如果它们不共享，则为0。然而，这种相似性定义不能反映出保存多个标签的成对图像的相似度排名。本文提出了一种新的深度哈希方法，通过将两两相似度重新定义为实例相似度，将实例相似度量化为基于规范化语义标签的百分比。基于实例相似度，针对损失函数构造量身定制加权交叉熵损失和最小均方误差损失，并有效地用于同时特征学习和哈希编码。在三个流行数据集上的实验表明，所提出的方法优于竞争方法，实现了多标签图像检索中的最新性能。

##### URL
[http://arxiv.org/abs/1803.02987](http://arxiv.org/abs/1803.02987)

##### PDF
[http://arxiv.org/pdf/1803.02987](http://arxiv.org/pdf/1803.02987)

