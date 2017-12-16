---
layout: post
title: "A Data Driven Approach for Compound Figure Separation Using Convolutional Neural Networks"
date: 2017-08-21 23:01:35
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning
author: Satoshi Tsutsui, David Crandall
mathjax: true
---

* content
{:toc}

##### Abstract
A key problem in automatic analysis and understanding of scientific papers is to extract semantic information from non-textual paper components like figures, diagrams, tables, etc. Much of this work requires a very first preprocessing step: decomposing compound multi-part figures into individual subfigures. Previous work in compound figure separation has been based on manually designed features and separation rules, which often fail for less common figure types and layouts. Moreover, few implementations for compound figure decomposition are publicly available. This paper proposes a data driven approach to separate compound figures using modern deep Convolutional Neural Networks (CNNs) to train the separator in an end-to-end manner. CNNs eliminate the need for manually designing features and separation rules, but require a large amount of annotated training data. We overcome this challenge using transfer learning as well as automatically synthesizing training exemplars. We evaluate our technique on the ImageCLEF Medical dataset, achieving 85.9% accuracy and outperforming previous techniques. We have released our implementation as an easy-to-use Python library, aiming to promote further research in scientific figure mining.

##### Abstract (translated by Google)
自动分析和理解科学论文的一个关键问题是从非文本的纸张组件（如图，图表，表格等）中提取语义信息。这些工作大部分需要一个第一预处理步骤：将复合多部分数字分解为单个子图。先前在复合图分离方面的工作是基于手动设计的特征和分离规则，对于较不常见的图形类型和布局常常失败。而且，复合图形分解的实现很少公开可用。本文提出了一种数据驱动的方法来分离使用现代深度卷积神经网络（CNN）的复合图形，以端到端的方式训练分离器。 CNN无需手动设计特征和分离规则，但需要大量的注释训练数据。我们通过转移学习克服了这个挑战，并自动综合了培训范例。我们在ImageCLEF医疗数据集上评估了我们的技术，达到了85.9％的准确度，并且胜过了先前的技术。我们已经发布了一个简单易用的Python库，旨在促进科学数字挖掘的进一步研究。

##### URL
[https://arxiv.org/abs/1703.05105](https://arxiv.org/abs/1703.05105)

##### PDF
[https://arxiv.org/pdf/1703.05105](https://arxiv.org/pdf/1703.05105)

