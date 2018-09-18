---
layout: post
title: "Quantum Statistics-Inspired Neural Attention"
date: 2018-09-17 13:58:13
categories: arXiv_AI
tags: arXiv_AI Salient Attention Inference Deep_Learning
author: Aristotelis Charalampous, Sotirios Chatzis
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence (encoder-decoder) models with attention constitute a cornerstone of deep learning research, as they have enabled unprecedented sequential data modeling capabilities. This effectiveness largely stems from the capacity of these models to infer salient temporal dynamics over long horizons; these are encoded into the obtained neural attention (NA) distributions. However, existing NA formulations essentially constitute point-wise selection mechanisms over the observed source sequences; that is, attention weights computation relies on the assumption that each source sequence element is independent of the rest. Unfortunately, although convenient, this assumption fails to account for higher-order dependencies which might be prevalent in real-world data. This paper addresses these limitations by leveraging Quantum-Statistical modeling arguments. Specifically, our work broadens the notion of NA, by attempting to account for the case that the NA model becomes inherently incapable of discerning between individual source elements; this is assumed to be the case due to higher-order temporal dynamics. On the contrary, we postulate that in some cases selection may be feasible only at the level of pairs of source sequence elements. To this end, we cast NA into inference of an attention density matrix (ADM) approximation. We derive effective training and inference algorithms, and evaluate our approach in the context of a machine translation (MT) application. We perform experiments with challenging benchmark datasets. As we show, our approach yields favorable outcomes in terms of several evaluation metrics.

##### Abstract (translated by Google)
序列到序列（编码器 - 解码器）模型受到关注构成了深度学习研究的基石，因为它们实现了前所未有的顺序数据建模功能。这种有效性很大程度上源于这些模型在长期视野中推断显着的时间动态的能力;这些被编码到获得的神经注意（NA）分布中。然而，现有的NA制剂基本上构成了观察到的源序列的逐点选择机制;也就是说，注意力量计算依赖于每个源序列元素独立于其余元素的假设。不幸的是，虽然方便，但这种假设无法解释可能在现实世界数据中普遍存在的高阶依赖性。本文通过利用量子统计建模参数来解决这些局限性。具体而言，我们的工作拓宽了NA的概念，试图解释NA模型本身无法辨别各个源元素的情况;由于高阶时间动态，这被认为是这种情况。相反，我们假设在某些情况下，选择仅在源序列元素对的水平上是可行的。为此，我们将NA转换为注意密度矩阵（ADM）近似的推断。我们推导出有效的训练和推理算法，并在机器翻译（MT）应用程序的背景下评估我们的方法。我们用具有挑战性的基准数据集进行实验如我们所示，我们的方法在几个评估指标方面产生了有利的结果。

##### URL
[http://arxiv.org/abs/1809.06205](http://arxiv.org/abs/1809.06205)

##### PDF
[http://arxiv.org/pdf/1809.06205](http://arxiv.org/pdf/1809.06205)

