---
layout: post
title: "Multinomial Loss on Held-out Data for the Sparse Non-negative Matrix Language Model"
date: 2016-02-22 19:15:19
categories: arXiv_CL
tags: arXiv_CL Sparse Language_Model
author: Ciprian Chelba, Fernando Pereira
mathjax: true
---

* content
{:toc}

##### Abstract
We describe Sparse Non-negative Matrix (SNM) language model estimation using multinomial loss on held-out data. Being able to train on held-out data is important in practical situations where the training data is usually mismatched from the held-out/test data. It is also less constrained than the previous training algorithm using leave-one-out on training data: it allows the use of richer meta-features in the adjustment model, e.g. the diversity counts used by Kneser-Ney smoothing which would be difficult to deal with correctly in leave-one-out training. In experiments on the one billion words language modeling benchmark, we are able to slightly improve on our previous results which use a different loss function, and employ leave-one-out training on a subset of the main training set. Surprisingly, an adjustment model with meta-features that discard all lexical information can perform as well as lexicalized meta-features. We find that fairly small amounts of held-out data (on the order of 30-70 thousand words) are sufficient for training the adjustment model. In a real-life scenario where the training data is a mix of data sources that are imbalanced in size, and of different degrees of relevance to the held-out and test data, taking into account the data source for a given skip-/n-gram feature and combining them for best performance on held-out/test data improves over skip-/n-gram SNM models trained on pooled data by about 8% in the SMT setup, or as much as 15% in the ASR/IME setup. The ability to mix various data sources based on how relevant they are to a mismatched held-out set is probably the most attractive feature of the new estimation method for SNM LM.

##### Abstract (translated by Google)
我们描述稀疏的非负矩阵（SNM）语言模型估计使用多项式亏损保持数据。训练数据通常与外出/测试数据不匹配的实际情况下，能够训练外挂数据非常重要。它比以前的训练算法在训练数据上使用leave-one-out的约束更少：它允许在调整模型中使用更丰富的元特征，例如， Kneser-Ney平滑使用的多样性计数，在一次性训练中难以正确处理。在10亿字语言建模基准的实验中，我们能够略微改进我们之前使用不同损失函数的结果，并且在主要训练集的一个子集上使用leave-one-out训练。令人惊讶的是，具有放弃所有词汇信息的元特征的调整模型可以执行以及词汇化的元特征。我们发现，相当少量的外部数据（大约30-70万字）足以训练调整模型。在现实生活中，训练数据是混合的数据源，这些数据源的大小不平衡，并且与保留和测试数据有不同程度的相关性，考虑给定跳过/ n的数据源-gram功能，并将它们组合起来以实现最佳的测试/保持数据性能，优于在SMT设置中对混合数据进行8％左右训练的skip-/ n-gram SNM模型，或在ASR / IME中高达15％建立。基于SNM LM的新估计方法的最有吸引力的特征，根据它们与不匹配的保持集的相关程度来混合各种数据源的能力可能是最有吸引力的特征。

##### URL
[https://arxiv.org/abs/1511.01574](https://arxiv.org/abs/1511.01574)

##### PDF
[https://arxiv.org/pdf/1511.01574](https://arxiv.org/pdf/1511.01574)

