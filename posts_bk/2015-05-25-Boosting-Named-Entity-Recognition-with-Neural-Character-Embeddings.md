---
layout: post
title: "Boosting Named Entity Recognition with Neural Character Embeddings"
date: 2015-05-25 11:35:32
categories: arXiv_CL
tags: arXiv_CL Embedding Classification Recognition
author: Cicero Nogueira dos Santos, Victor Guimarães
mathjax: true
---

* content
{:toc}

##### Abstract
Most state-of-the-art named entity recognition (NER) systems rely on handcrafted features and on the output of other NLP tasks such as part-of-speech (POS) tagging and text chunking. In this work we propose a language-independent NER system that uses automatically learned features only. Our approach is based on the CharWNN deep neural network, which uses word-level and character-level representations (embeddings) to perform sequential classification. We perform an extensive number of experiments using two annotated corpora in two different languages: HAREM I corpus, which contains texts in Portuguese; and the SPA CoNLL-2002 corpus, which contains texts in Spanish. Our experimental results shade light on the contribution of neural character embeddings for NER. Moreover, we demonstrate that the same neural network which has been successfully applied to POS tagging can also achieve state-of-the-art results for language-independet NER, using the same hyperparameters, and without any handcrafted features. For the HAREM I corpus, CharWNN outperforms the state-of-the-art system by 7.9 points in the F1-score for the total scenario (ten NE classes), and by 7.2 points in the F1 for the selective scenario (five NE classes).

##### Abstract (translated by Google)
大多数最先进的命名实体识别（NER）系统依赖于手工特征以及其他NLP任务的输出，例如词性（POS）标记和文本块（text chunking）。在这项工作中，我们提出了一个独立于语言的NER系统，它只使用自动学习功能。我们的方法是基于CharWNN深度神经网络，它使用字级和字符级表示（嵌入）来执行顺序分类。我们使用两种不同语言的两个带注释的语料库进行大量的实验：HAREM I语料库，其中包含葡萄牙文;以及包含西班牙文本的SPA CoNLL-2002语料库。我们的实验结果为神经元字符嵌入对NER的贡献提供了线索。此外，我们证明，已经成功应用于POS标记的相同的神经网络也可以使用相同的超参数并且没有任何手工特征来实现独立于语言的NER的最新结果。对于HAREM I语料库，CharWNN在总体情景（十个NE类别）的F1分数和选择性情景的F1分数（五个NE类别）。

##### URL
[https://arxiv.org/abs/1505.05008](https://arxiv.org/abs/1505.05008)

##### PDF
[https://arxiv.org/pdf/1505.05008](https://arxiv.org/pdf/1505.05008)

