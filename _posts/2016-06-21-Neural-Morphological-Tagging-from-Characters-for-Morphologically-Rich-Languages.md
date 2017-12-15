---
layout: post
title: "Neural Morphological Tagging from Characters for Morphologically Rich Languages"
date: 2016-06-21 16:25:31
categories: arXiv_CL
tags: arXiv_CL Embedding RNN
author: Georg Heigold, Guenter Neumann, Josef van Genabith
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates neural character-based morphological tagging for languages with complex morphology and large tag sets. We systematically explore a variety of neural architectures (DNN, CNN, CNNHighway, LSTM, BLSTM) to obtain character-based word vectors combined with bidirectional LSTMs to model across-word context in an end-to-end setting. We explore supplementary use of word-based vectors trained on large amounts of unlabeled data. Our experiments for morphological tagging suggest that for "simple" model configurations, the choice of the network architecture (CNN vs. CNNHighway vs. LSTM vs. BLSTM) or the augmentation with pre-trained word embeddings can be important and clearly impact the accuracy. Increasing the model capacity by adding depth, for example, and carefully optimizing the neural networks can lead to substantial improvements, and the differences in accuracy (but not training time) become much smaller or even negligible. Overall, our best morphological taggers for German and Czech outperform the best results reported in the literature by a large margin.

##### Abstract (translated by Google)
本文研究了形态复杂，标签集合大的语言的基于神经元特征的形态标注。我们系统地探索了多种神经架构（DNN，CNN，CNN高速公路，LSTM，BLSTM），以获得与双向LSTM相结合的基于字符的单词向量，以在端到端设置中对跨词语境进行建模。我们探索了对大量未标记数据进行训练的基于词的矢量的补充使用。我们的形态标记实验表明，对于“简单”模型配置，网络结构（CNN与CNN公路相对于LSTM与BLSTM）的选择或者预先训练的词嵌入的增强可能是重要的，并且显然影响精度。例如，通过增加深度来增加模型容量，并且仔细优化神经网络可以导致实质性的改进，并且准确度（而不是训练时间）的差异变得更小甚至可以忽略不计。总体而言，德国和捷克的最佳形态标签器的性能优于文献报道的最好结果。

##### URL
[https://arxiv.org/abs/1606.06640](https://arxiv.org/abs/1606.06640)

##### PDF
[https://arxiv.org/pdf/1606.06640](https://arxiv.org/pdf/1606.06640)

