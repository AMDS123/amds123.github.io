---
layout: post
title: "Finding the Topic of a Set of Images"
date: 2016-06-25 15:06:27
categories: arXiv_CV
tags: arXiv_CV
author: Gonzalo Vaca-Castano
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we introduce the problem of determining the topic that a set of images is describing, where every topic is represented as a set of words. Different from other problems like tag assignment or similar, a) we assume multiple images are used as input instead of single image, b) Input images are typically not visually related, c) Input images are not necessarily semantically close, and d) Output word space is unconstrained. In our proposed solution, visual information of each query image is used to retrieve similar images with text labels (tags) from an image database. We consider a scenario where the tags are very noisy and diverse, given that they were obtained by implicit crowd-sourcing in a database of 1 million images and over seventy seven thousand tags. The words or tags associated to each query are processed jointly in a word selection algorithm using random walks that allows to refine the search topic, rejecting words that are not part of the topic and produce a set of words that fairly describe the topic. Experiments on a dataset of 300 topics, with up to twenty images per topic, show that our algorithm performs better than the proposed baseline for any number of query images. We also present a new Conditional Random Field (CRF) word mapping algorithm that preserves the semantic similarity of the mapped words, increasing the performance of the results over the baseline.

##### Abstract (translated by Google)
在本文中，我们介绍确定一组图像正在描述的主题的问题，其中每个主题被表示为一组单词。不同于其他问题，如标签分配或类似，a）我们假设多个图像被用作输入，而不是单一的图像，b）输入图像通常不是视觉上相关的，c）输入图像不一定在语义上关闭，d）输出字空间不受限制。在我们提出的解决方案中，每个查询图像的视觉信息被用来从图像数据库中检索带有文本标签（标签）的相似图像。我们考虑一个场景，其中标签是非常嘈杂和多样化的，因为它们是通过在一百万张图像和超过七千七千个标签的数据库中隐含的众包来获得的。与每个查询相关联的单词或标签在使用随机游走的单词选择算法中被联合处理，所述随机游走允许优化搜索主题，拒绝不是主题的一部分的单词并且产生一组相当描述该主题的单词。对300个主题的数据集进行实验，每个主题最多20个图像，表明我们的算法比任何数量的查询图像提出的基线都要好。我们还提出了一种新的条件随机场（CRF）字映射算法，它保留了映射字的语义相似性，提高了基线结果的性能。

##### URL
[https://arxiv.org/abs/1606.07921](https://arxiv.org/abs/1606.07921)

##### PDF
[https://arxiv.org/pdf/1606.07921](https://arxiv.org/pdf/1606.07921)

