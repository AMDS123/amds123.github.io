---
layout: post
title: "A Retrospective Analysis of the Fake News Challenge Stance Detection Task"
date: 2018-06-13 15:38:09
categories: arXiv_CL
tags: arXiv_CL RNN Classification Quantitative Detection
author: Andreas Hanselowski, Avinesh PVS, Benjamin Schiller, Felix Caspelherr, Debanjan Chaudhuri, Christian M. Meyer, Iryna Gurevych
mathjax: true
---

* content
{:toc}

##### Abstract
The 2017 Fake News Challenge Stage 1 (FNC-1) shared task addressed a stance classification task as a crucial first step towards detecting fake news. To date, there is no in-depth analysis paper to critically discuss FNC-1's experimental setup, reproduce the results, and draw conclusions for next-generation stance classification methods. In this paper, we provide such an in-depth analysis for the three top-performing systems. We first find that FNC-1's proposed evaluation metric favors the majority class, which can be easily classified, and thus overestimates the true discriminative power of the methods. Therefore, we propose a new F1-based metric yielding a changed system ranking. Next, we compare the features and architectures used, which leads to a novel feature-rich stacked LSTM model that performs on par with the best systems, but is superior in predicting minority classes. To understand the methods' ability to generalize, we derive a new dataset and perform both in-domain and cross-domain experiments. Our qualitative and quantitative study helps interpreting the original FNC-1 scores and understand which features help improving performance and why. Our new dataset and all source code used during the reproduction study are publicly available for future research.

##### Abstract (translated by Google)
2017年假新闻挑战赛第一阶段（FNC-1）共同任务处理了一个立场分类任务，作为检测假新闻的关键的第一步。迄今为止，还没有深入的分析论文来批判性地讨论FNC-1的实验装置，重现结果，并为下一代立场分类方法得出结论。在本文中，我们为三个顶级系统提供了如此深入的分析。我们首先发现FNC-1提出的评估指标倾向于大多数类别，它们可以很容易地进行分类，从而高估了方法的真正区分能力。因此，我们提出了一种新的基于F1的度量标准，可以产生变化的系统级别。接下来，我们比较所使用的功能和体系结构，这导致了一种新的功能丰富的堆叠LSTM模型，它可以与最好的系统相媲美，但在预测少数族群方面更胜一筹。为了理解方法的泛化能力，我们推导出一个新的数据集并执行域内和跨域实验。我们的定性和定量研究有助于解读原始FNC-1分数，并了解哪些功能有助于提高性能以及为什么。我们的新数据集以及在复制研究中使用的所有源代码都可以公开供未来研究。

##### URL
[http://arxiv.org/abs/1806.05180](http://arxiv.org/abs/1806.05180)

##### PDF
[http://arxiv.org/pdf/1806.05180](http://arxiv.org/pdf/1806.05180)

