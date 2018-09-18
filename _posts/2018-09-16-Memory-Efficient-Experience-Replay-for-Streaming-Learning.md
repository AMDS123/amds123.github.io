---
layout: post
title: "Memory Efficient Experience Replay for Streaming Learning"
date: 2018-09-16 18:04:33
categories: arXiv_AI
tags: arXiv_AI
author: Tyler L. Hayes, Nathan D. Cahill, Christopher Kanan
mathjax: true
---

* content
{:toc}

##### Abstract
In supervised machine learning, an agent is typically trained once and then deployed. While this works well for static settings, robots often operate in changing environments and must quickly learn new things from data streams. In this paradigm, known as streaming learning, a learner is trained online, in a single pass, from a data stream that cannot be assumed to be independent and identically distributed (iid). Streaming learning will cause conventional deep neural networks (DNNs) to fail for two reasons: 1) they need multiple passes through the entire dataset; and 2) non-iid data will cause catastrophic forgetting. An old fix to both of these issues is rehearsal. To learn a new example, rehearsal mixes it with previous examples, and then this mixture is used to update the DNN. Full rehearsal is slow and memory intensive because it stores all previously observed examples, and its effectiveness for preventing catastrophic forgetting has not been studied in modern DNNs. Here, we describe the ExStream algorithm for memory efficient rehearsal and compare it to alternatives. We find that full rehearsal can eliminate catastrophic forgetting in a variety of streaming learning settings, with ExStream performing well using far less memory and computation.

##### Abstract (translated by Google)
在有监督的机器学习中，代理通常被训练一次然后被部署。虽然这适用于静态设置，但机器人通常在不断变化的环境中运行，并且必须从数据流中快速学习新事物。在这种称为流式学习的范例中，学习者在一次通过中从数据流在线训练，该数据流不能被假定为独立且相同地分布（iid）。流式学习将导致传统的深度神经网络（DNN）失败有两个原因：1）它们需要多次遍历整个数据集; 2）非iid数据将导致灾难性的遗忘。对这两个问题的一个旧解决方法是排练。为了学习一个新的例子，排练将它与之前的例子混合在一起，然后这个混合用于更新DNN。完整的排练是缓慢的和记忆密集型的，因为它存储了所有先前观察到的例子，并且它在现代DNN中尚未研究其防止灾难性遗忘的有效性。在这里，我们描述了用于内存有效排练的ExStream算法，并将其与替代方案进行比较。我们发现完整的排练可以消除各种流式学习设置中的灾难性遗忘，ExStream使用更少的内存和计算表现良好。

##### URL
[http://arxiv.org/abs/1809.05922](http://arxiv.org/abs/1809.05922)

##### PDF
[http://arxiv.org/pdf/1809.05922](http://arxiv.org/pdf/1809.05922)

