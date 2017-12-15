---
layout: post
title: "Local Translation Prediction with Global Sentence Representation"
date: 2015-02-27 14:55:15
categories: arXiv_CL
tags: arXiv_CL CNN Prediction
author: Jiajun Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Statistical machine translation models have made great progress in improving the translation quality. However, the existing models predict the target translation with only the source- and target-side local context information. In practice, distinguishing good translations from bad ones does not only depend on the local features, but also rely on the global sentence-level information. In this paper, we explore the source-side global sentence-level features for target-side local translation prediction. We propose a novel bilingually-constrained chunk-based convolutional neural network to learn sentence semantic representations. With the sentence-level feature representation, we further design a feed-forward neural network to better predict translations using both local and global information. The large-scale experiments show that our method can obtain substantial improvements in translation quality over the strong baseline: the hierarchical phrase-based translation model augmented with the neural network joint model.

##### Abstract (translated by Google)
统计机器翻译模型在提高翻译质量方面取得了很大的进展。然而，现有的模型仅用源和目标侧的本地情境信息来预测目标翻译。在实践中，把好的翻译与坏的翻译区分开来，不仅要依靠地方特色，还要依靠全球的句子层面的信息。在本文中，我们探讨了目标端局部翻译预测的源端全局句子层次特征。我们提出了一种新的双语约束的基于块的卷积神经网络来学习句子语义表征。通过句子级别的特征表示，我们进一步设计了一个前馈神经网络，以更好地预测使用本地和全局信息的翻译。大规模的实验表明，我们的方法可以在强基线上获得翻译质量的实质性提高：基于神经网络联合模型的分层短语翻译模型得到了增强。

##### URL
[https://arxiv.org/abs/1502.07920](https://arxiv.org/abs/1502.07920)

##### PDF
[https://arxiv.org/pdf/1502.07920](https://arxiv.org/pdf/1502.07920)

