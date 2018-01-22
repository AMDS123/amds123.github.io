---
layout: post
title: "Image Provenance Analysis at Scale"
date: 2018-01-19 17:54:22
categories: arXiv_CV
tags: arXiv_CV
author: Daniel Moreira, Aparna Bharati, Joel Brogan, Allan Pinto, Michael Parowski, Kevin W. Bowyer, Patrick J. Flynn, Anderson Rocha, Walter J. Scheirer
mathjax: true
---

* content
{:toc}

##### Abstract
Prior art has shown it is possible to estimate, through image processing and computer vision techniques, the types and parameters of transformations that have been applied to the content of individual images to obtain new images. Given a large corpus of images and a query image, an interesting further step is to retrieve the set of original images whose content is present in the query image, as well as the detailed sequences of transformations that yield the query image given the original images. This is a problem that recently has received the name of image provenance analysis. In these times of public media manipulation ( e.g., fake news and meme sharing), obtaining the history of image transformations is relevant for fact checking and authorship verification, among many other applications. This article presents an end-to-end processing pipeline for image provenance analysis, which works at real-world scale. It employs a cutting-edge image filtering solution that is custom-tailored for the problem at hand, as well as novel techniques for obtaining the provenance graph that expresses how the images, as nodes, are ancestrally connected. A comprehensive set of experiments for each stage of the pipeline is provided, comparing the proposed solution with state-of-the-art results, employing previously published datasets. In addition, this work introduces a new dataset of real-world provenance cases from the social media site Reddit, along with baseline results.

##### Abstract (translated by Google)
现有技术已经表明，可以通过图像处理和计算机视觉技术来估计已经应用于各个图像的内容的变换的类型和参数以获得新的图像。给定大量的图像和查询图像，有趣的是，检索查询图像中存在内容的原始图像集合，以及给出原始图像产生查询图像的转换的详细序列。这是最近已经收到图像起源分析名称的一个问题。在这些公共媒体操纵的时代（例如，假新闻和模因共享）中，获得图像转换的历史与许多其他应用程序中的事实检查和着作权验证是相关的。本文提供了一个图像来源分析的端到端处理流程，可以在现实世界中使用。它采用了针对手头问题量身定制的尖端图像过滤解决方案，以及获取源图像的​​新颖技术，该图像表达了图像作为节点如何连接在一起。提供了一个全面的实验流程的每个阶段，比较提出的解决方案与最先进的结果，采用以前发布的数据集。此外，这项工作还介绍了一个来自社交媒体网站Reddit的真实来源案例的新数据集以及基线结果。

##### URL
[http://arxiv.org/abs/1801.06510](http://arxiv.org/abs/1801.06510)

##### PDF
[http://arxiv.org/pdf/1801.06510](http://arxiv.org/pdf/1801.06510)

