---
layout: post
title: "Extracting Scientific Figures with Distantly Supervised Neural Networks"
date: 2018-04-06 20:22:47
categories: arXiv_CV
tags: arXiv_CV Caption Detection
author: Noah Siegel, Nicholas Lourie, Russell Power, Waleed Ammar
mathjax: true
---

* content
{:toc}

##### Abstract
Non-textual components such as charts, diagrams and tables provide key information in many scientific documents, but the lack of large labeled datasets has impeded the development of data-driven methods for scientific figure extraction. In this paper, we induce high-quality training labels for the task of figure extraction in a large number of scientific documents, with no human intervention. To accomplish this we leverage the auxiliary data provided in two large web collections of scientific documents (arXiv and PubMed) to locate figures and their associated captions in the rasterized PDF. We share the resulting dataset of over 5.5 million induced labels---4,000 times larger than the previous largest figure extraction dataset---with an average precision of 96.8%, to enable the development of modern data-driven methods for this task. We use this dataset to train a deep neural network for end-to-end figure detection, yielding a model that can be more easily extended to new domains compared to previous work. The model was successfully deployed in Semantic Scholar, a large-scale academic search engine, and used to extract figures in 13 million scientific documents.

##### Abstract (translated by Google)
诸如图表，图表和表格等非文本组成部分提供了许多科学文献中的关键信息，但缺乏大量标记的数据集阻碍了数据驱动的科学数据提取方法的发展。在本文中，我们为大量科学文献中的图形提取任务引入高质量的训练标签，而不需要人为干预。为了实现这一目标，我们利用科学文档（arXiv和PubMed）的两个大型Web集合中提供的辅助数据来定位栅格化PDF中的图形及其相关标题。我们共享超过550万个诱导标签的结果数据集 - 比以前最大的图形提取数据集大4000倍 - 平均精度为96.8％，以便为此任务开发现代数据驱动的方法。我们使用这个数据集来训练一个深度神经网络来进行端到端数字检测，与以前的工作相比，这个模型可以更容易地扩展到新的领域。该模型已成功部署在Semantic Sc​​holar（一个大型的学术搜索引擎）中，并用于提取1300万份科学文档中的数字。

##### URL
[https://arxiv.org/abs/1804.02445](https://arxiv.org/abs/1804.02445)

##### PDF
[https://arxiv.org/pdf/1804.02445](https://arxiv.org/pdf/1804.02445)

