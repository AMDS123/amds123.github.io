---
layout: post
title: "Continuous Space Reordering Models for Phrase-based MT"
date: 2018-01-25 10:17:32
categories: arXiv_CL
tags: arXiv_CL Attention
author: Nadir Durrani, Fahim Dalvi
mathjax: true
---

* content
{:toc}

##### Abstract
Bilingual sequence models improve phrase-based translation and reordering by overcoming phrasal independence assumption and handling long range reordering. However, due to data sparsity, these models often fall back to very small context sizes. This problem has been previously addressed by learning sequences over generalized representations such as POS tags or word clusters. In this paper, we explore an alternative based on neural network models. More concretely we train neuralized versions of lexicalized reordering and the operation sequence models using feed-forward neural network. Our results show improvements of up to 0.6 and 0.5 BLEU points on top of the baseline German-&gt;English and English-&gt;German systems. We also observed improvements compared to the systems that used POS tags and word clusters to train these models. Because we modify the bilingual corpus to integrate reordering operations, this allows us to also train a sequence-to-sequence neural MT model having explicit reordering triggers. Our motivation was to directly enable reordering information in the encoder-decoder framework, which otherwise relies solely on the attention model to handle long range reordering. We tried both coarser and fine-grained reordering operations. However, these experiments did not yield any improvements over the baseline Neural MT systems.

##### Abstract (translated by Google)
双语序列模型通过克服短语独立性假设和处理长程重新排序来改进基于短语的翻译和重新排序。但是，由于数据稀疏，这些模型通常会回退到非常小的上下文大小。这个问题之前已经通过在广义表示（例如POS标签或单词群）上学习序列来解决。在本文中，我们探索一个基于神经网络模型的替代方案。更具体地说，我们使用前馈神经网络训练词汇化重排的神经化版本和操作序列模型。我们的结果显示，在基线德语 - >英语和英语 - >德语系统之上，可以提高多达0.6和0.5个BLEU点。与使用POS标签和词组来训练这些模型的系统相比，我们也观察到了改进。因为我们修改了双语语料库来整合重排序操作，所以我们也可以训练具有显式重排序触发器的序列 - 序列神经MT模型。我们的动机是直接在编码器 - 解码器框架中重新排序信息，否则单独依靠注意模型来处理长程重新排序。我们尝试了更粗更细的重排操作。然而，这些实验并没有比基线Neural MT系统有任何改进。

##### URL
[http://arxiv.org/abs/1801.08337](http://arxiv.org/abs/1801.08337)

##### PDF
[http://arxiv.org/pdf/1801.08337](http://arxiv.org/pdf/1801.08337)

