---
layout: post
title: "How to Generate a Good Word Embedding?"
date: 2015-07-20 15:07:53
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Siwei Lai, Kang Liu, Liheng Xu, Jun Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
We analyze three critical components of word embedding training: the model, the corpus, and the training parameters. We systematize existing neural-network-based word embedding algorithms and compare them using the same corpus. We evaluate each word embedding in three ways: analyzing its semantic properties, using it as a feature for supervised tasks and using it to initialize neural networks. We also provide several simple guidelines for training word embeddings. First, we discover that corpus domain is more important than corpus size. We recommend choosing a corpus in a suitable domain for the desired task, after that, using a larger corpus yields better results. Second, we find that faster models provide sufficient performance in most cases, and more complex models can be used if the training corpus is sufficiently large. Third, the early stopping metric for iterating should rely on the development set of the desired task rather than the validation loss of training embedding.

##### Abstract (translated by Google)
我们分析了词嵌入训练的三个关键组成部分：模型，语料库和训练参数。我们将现有的基于神经网络的词嵌入算法系统化，并使用相同的语料库进行比较。我们用三种方法评估每个词的嵌入：分析它的语义属性，用它作为监督任务的一个特征，并用它来初始化神经网络。我们还提供了几个简单的训练词嵌入的指导方针。首先，我们发现语料库领域比语料库规模更重要。我们建议在合适的领域选择一个语料库来完成所需的任务，然后使用更大的语料库可以得到更好的结果。其次，我们发现更快的模型在大多数情况下提供了足够的性能，如果训练语料库足够大，可以使用更复杂的模型。第三，迭代的早期停止度量应该依赖于期望任务的开发集而不是训练嵌入的验证丢失。

##### URL
[https://arxiv.org/abs/1507.05523](https://arxiv.org/abs/1507.05523)

##### PDF
[https://arxiv.org/pdf/1507.05523](https://arxiv.org/pdf/1507.05523)

