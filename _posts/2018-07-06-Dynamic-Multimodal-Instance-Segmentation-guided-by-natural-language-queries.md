---
layout: post
title: "Dynamic Multimodal Instance Segmentation guided by natural language queries"
date: 2018-07-06 05:21:06
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Edgar A. Margffoy-Tuay, Juan C. P&#xe9;rez, Emilio Botero, Pablo Arbel&#xe1;ez
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the task of segmenting an object given a natural language expression that references it, \textit{i.e.} a referring expression. Current techniques tackle this task by either (\textit{i}) directly or recursively merging the linguistic and visual information in the channel dimension and then performing convolutions; or by (\textit{ii}) mapping the expression to a space in which it can be thought of as a filter, whose response is directly related to the presence of the object at a given spatial coordinate in the image, so that a convolution can be applied to look for the object. We propose a novel method that merges the best of both worlds to exploit the recursive nature of language, and that also, during the upsampling process, takes advantage of the intermediate information generated when downsampling the image, so that detailed segmentations can be obtained. Our method is compared with the state-of-the-art approaches in four standard datasets, in which it yields high performance and surpasses all previous methods in six of eight of the standard dataset splits for this task. Code will be made available in the final version of this paper. Full implementation of our method and training routines, written in PyTorch, can be found at \url{https://github.com/andfoy/query-objseg}

##### Abstract (translated by Google)
在本文中，我们解决了在给定引用它的自然语言表达式的对象的分割任务，\ textit {即。}一个引用表达式。当前技术通过（\ textit {i}）直接或递归地合并信道维度中的语言和视觉信息然后执行卷积来处理该任务;或者通过（\ textit {ii}）将表达式映射到一个空间，在该空间中它可以被认为是一个过滤器，其响应与图像中给定空间坐标处对象的存在直接相关，因此卷积可以应用于查找对象。我们提出了一种新方法，它融合了两个世界的优点，以利用语言的递归性质，并且在上采样过程中，还利用了在对图像进行下采样时生成的中间信息，从而可以获得详细的分割。我们的方法与四个标准数据集中的最新方法进行了比较，其中它产生了高性能，并且超过了此任务的八个标准数据集拆分中的六个中的所有先前方法。代码将在本文的最终版本中提供。用PyTorch编写的方法和训练程序的完整实现可以在\ url {https://github.com/andfoy/query-objseg}找到

##### URL
[http://arxiv.org/abs/1807.02257](http://arxiv.org/abs/1807.02257)

##### PDF
[http://arxiv.org/pdf/1807.02257](http://arxiv.org/pdf/1807.02257)

