---
layout: post
title: "Evaluating Compositionality in Sentence Embeddings"
date: 2018-02-12 19:02:52
categories: arXiv_CL
tags: arXiv_CL Sentiment Knowledge Embedding Inference Detection
author: Ishita Dasgupta, Demi Guo, Andreas Stuhlm&#xfc;ller, Samuel J. Gershman, Noah D. Goodman
mathjax: true
---

* content
{:toc}

##### Abstract
An important frontier in the quest for human-like AI is compositional semantics: how do we design systems that understand an infinite number of expressions built from a finite vocabulary? Recent research has attempted to solve this problem by using deep neural networks to learn vector space embeddings of sentences, which then serve as input to supervised learning problems like paraphrase detection and sentiment analysis. Here we focus on 'natural language inference' (NLI) as a critical test of a system's capacity for semantic compositionality. In the NLI task, sentence pairs are assigned one of three categories: entailment, contradiction, or neutral. We present a new set of NLI sentence pairs that cannot be solved using only word-level knowledge and instead require some degree of compositionality. We use state of the art sentence embeddings trained on NLI (InferSent, Conneau et al. (2017)), and find that performance on our new dataset is poor, indicating that the representations learned by this model fail to capture the needed compositionality. We analyze some of the decision rules learned by InferSent and find that they are largely driven by simple heuristics at the word level that are ecologically valid in the SNLI dataset on which InferSent is trained. Further, we find that augmenting the training dataset with our new dataset improves performance on a held-out test set without loss of performance on the SNLI test set. This highlights the importance of structured datasets in better understanding, as well as improving the performance of, AI systems.

##### Abstract (translated by Google)
寻求人类人工智能的一个重要前沿是成分语义学：我们如何设计理解无限数量的表达式的系统，这些表达式是从有限的词汇表中构建的？最近的研究试图通过使用深度神经网络来学习句子的矢量空间嵌入来解决这个问题，然后将其用作监控学习问题的输入，如释义检测和情感分析。在这里，我们将重点放在“自然语言推理”（NLI）上，作为系统语义合成能力的关键测试。在NLI任务中，句对被分配到三类中的一类：包含，矛盾或中性。我们提出一套新的NLI句子对，它们不能仅使用单词级知识来解决，而是需要某种程度的组合性。我们使用最先进的NLI语言嵌入语言（InferSent，Conneau et al。（2017）），并发现我们的新数据集的表现很差，表明这种模型学到的表示未能捕捉到所需的组合性。我们分析了InferSent学到的一些决策规则，发现他们很大程度上受简单的启发式推动，在单词级别上，在InferSent训练的SNLI数据集中生态有效。此外，我们发现使用我们的新数据集增强训练数据集可以提高测试集的性能，而不会在SNLI测试集上损失性能。这突出显示了结构化数据集对于更好地理解AI系统的性能以及提高性能的重要性。

##### URL
[http://arxiv.org/abs/1802.04302](http://arxiv.org/abs/1802.04302)

##### PDF
[http://arxiv.org/pdf/1802.04302](http://arxiv.org/pdf/1802.04302)

