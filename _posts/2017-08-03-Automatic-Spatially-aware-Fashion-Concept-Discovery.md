---
layout: post
title: "Automatic Spatially-aware Fashion Concept Discovery"
date: 2017-08-03 21:13:04
categories: arXiv_CV
tags: arXiv_CV Embedding CNN
author: Xintong Han, Zuxuan Wu, Phoenix X. Huang, Xiao Zhang, Menglong Zhu, Yuan Li, Yang Zhao, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an automatic spatially-aware concept discovery approach using weakly labeled image-text data from shopping websites. We first fine-tune GoogleNet by jointly modeling clothing images and their corresponding descriptions in a visual-semantic embedding space. Then, for each attribute (word), we generate its spatially-aware representation by combining its semantic word vector representation with its spatial representation derived from the convolutional maps of the fine-tuned network. The resulting spatially-aware representations are further used to cluster attributes into multiple groups to form spatially-aware concepts (e.g., the neckline concept might consist of attributes like v-neck, round-neck, etc). Finally, we decompose the visual-semantic embedding space into multiple concept-specific subspaces, which facilitates structured browsing and attribute-feedback product retrieval by exploiting multimodal linguistic regularities. We conducted extensive experiments on our newly collected Fashion200K dataset, and results on clustering quality evaluation and attribute-feedback product retrieval task demonstrate the effectiveness of our automatically discovered spatially-aware concepts.

##### Abstract (translated by Google)
本文提出了一种自动的空间感知概念发现方法，使用来自购物网站的弱标记图像文本数据。我们首先通过在视觉语义嵌入空间中联合建模服装图像及其对应的描述来微调GoogleNet。然后，对于每个属性（单词），我们通过将其语义词矢量表示与从微调网络的卷积映射导出的空间表示相组合，来生成其空间感知表示。得到的空间感知表示进一步用于将属性聚类为多个组以形成空间感知的概念（例如，领口概念可以由诸如V领，圆领等的属性组成）。最后，将视觉语义嵌入空间分解为多个概念特定的子空间，利用多模态语言规律，便于结构化浏览和属性反馈产品检索。我们对新收集的Fashion200K数据集进行了广泛的实验，聚类质量评估和属性反馈产品检索任务的结果证明了我们自动发现的空间意识概念的有效性。

##### URL
[https://arxiv.org/abs/1708.01311](https://arxiv.org/abs/1708.01311)

##### PDF
[https://arxiv.org/pdf/1708.01311](https://arxiv.org/pdf/1708.01311)

