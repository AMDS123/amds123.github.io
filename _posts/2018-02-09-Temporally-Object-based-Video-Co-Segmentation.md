---
layout: post
title: "Temporally Object-based Video Co-Segmentation"
date: 2018-02-09 14:32:12
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Michael Ying Yang, Matthias Reso, Jun Tang, Wentong Liao, Bodo Rosenhahn
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an unsupervised video object co-segmentation framework based on the primary object proposals to extract the common foreground object(s) from a given video set. In addition to the objectness attributes and motion coherence our framework exploits the temporal consistency of the object-like regions between adjacent frames to enrich the set of original object proposals. We call the enriched proposal sets temporal proposal streams, as they are composed of the most similar proposals from each frame augmented with predicted proposals using temporally consistent superpixel information. The temporal proposal streams represent all the possible region tubes of the objects. Therefore, we formulate a graphical model to select a proposal stream for each object in which the pairwise potentials consist of the appearance dissimilarity between different streams in the same video and also the similarity between the streams in different videos. This model is suitable for single (multiple) foreground objects in two (more) videos, which can be solved by any existing energy minimization method. We evaluate our proposed framework by comparing it to other video co-segmentation algorithms. Our method achieves improved performance on state-of-the-art benchmark datasets.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于主要对象提议的无监督视频对象协同分割框架，以从给定视频集中提取公共前景对象。除了对象属性和运动一致性之外，我们的框架还利用相邻帧之间的对象类区域的时间一致性来丰富原始对象提议集。我们称这个丰富的提案设置了时间提议流，因为它们由来自每个帧的最相似的提议组成，这些提议使用时间一致的超像素信息来增强预测提议。时间提议流代表对象的所有可能的区域管。因此，我们制定了一个图形模型来为每个对象选择提案流，其中成对电位由同一视频中不同流之间的外观差异以及不同视频中流之间的相似度组成。该模型适用于两个（更多）视频中的单个（多个）前景对象，这可以通过任何现有的能量最小化方法来解决。我们通过将其与其他视频共分割算法进行比较来评估我们提出的框架。我们的方法在最先进的基准数据集上实现了更高的性能。

##### URL
[http://arxiv.org/abs/1802.03279](http://arxiv.org/abs/1802.03279)

##### PDF
[http://arxiv.org/pdf/1802.03279](http://arxiv.org/pdf/1802.03279)

