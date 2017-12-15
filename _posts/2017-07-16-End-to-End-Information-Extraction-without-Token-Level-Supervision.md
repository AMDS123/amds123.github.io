---
layout: post
title: "End-to-End Information Extraction without Token-Level Supervision"
date: 2017-07-16 16:57:36
categories: arXiv_CL
tags: arXiv_CL
author: Rasmus Berg Palm, Dirk Hovy, Florian Laws, Ole Winther
mathjax: true
---

* content
{:toc}

##### Abstract
Most state-of-the-art information extraction approaches rely on token-level labels to find the areas of interest in text. Unfortunately, these labels are time-consuming and costly to create, and consequently, not available for many real-life IE tasks. To make matters worse, token-level labels are usually not the desired output, but just an intermediary step. End-to-end (E2E) models, which take raw text as input and produce the desired output directly, need not depend on token-level labels. We propose an E2E model based on pointer networks, which can be trained directly on pairs of raw input and output text. We evaluate our model on the ATIS data set, MIT restaurant corpus and the MIT movie corpus and compare to neural baselines that do use token-level labels. We achieve competitive results, within a few percentage points of the baselines, showing the feasibility of E2E information extraction without the need for token-level labels. This opens up new possibilities, as for many tasks currently addressed by human extractors, raw input and output data are available, but not token-level labels.

##### Abstract (translated by Google)
大多数最先进的信息提取方法都依赖于令牌级标签来查找文本中的感兴趣区域。不幸的是，这些标签耗时且成本高昂，因此不适用于许多真实的IE任务。更糟的是，令牌级别的标签通常不是所需的输出，而只是一个中间步骤。采用原始文本作为输入并直接产生所需输出的端到端（E2E）模型不需要依赖于令牌级标签。我们提出了一种基于指针网络的E2E模型，可以直接在原始输入输出文本对上进行训练。我们在ATIS数据集，MIT餐馆语料库和MIT电影语料库上评估我们的模型，并与使用令牌级标签的神经基线进行比较。我们在基线的几个百分点范围内取得了有竞争力的结果，显示了E2E信息提取的可行性，而不需要令牌级别的标签。这就开辟了新的可能性，对于目前由人类提取器处理的许多任务，原始输入和输出数据是可用的，但不是令牌级标签。

##### URL
[https://arxiv.org/abs/1707.04913](https://arxiv.org/abs/1707.04913)

##### PDF
[https://arxiv.org/pdf/1707.04913](https://arxiv.org/pdf/1707.04913)

