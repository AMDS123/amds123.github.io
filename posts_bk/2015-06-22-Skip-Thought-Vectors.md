---
layout: post
title: "Skip-Thought Vectors"
date: 2015-06-22 19:33:40
categories: arXiv_CL
tags: arXiv_CL Sentiment Classification Detection
author: Ryan Kiros, Yukun Zhu, Ruslan Salakhutdinov, Richard S. Zemel, Antonio Torralba, Raquel Urtasun, Sanja Fidler
mathjax: true
---

* content
{:toc}

##### Abstract
We describe an approach for unsupervised learning of a generic, distributed sentence encoder. Using the continuity of text from books, we train an encoder-decoder model that tries to reconstruct the surrounding sentences of an encoded passage. Sentences that share semantic and syntactic properties are thus mapped to similar vector representations. We next introduce a simple vocabulary expansion method to encode words that were not seen as part of training, allowing us to expand our vocabulary to a million words. After training our model, we extract and evaluate our vectors with linear models on 8 tasks: semantic relatedness, paraphrase detection, image-sentence ranking, question-type classification and 4 benchmark sentiment and subjectivity datasets. The end result is an off-the-shelf encoder that can produce highly generic sentence representations that are robust and perform well in practice. We will make our encoder publicly available.

##### Abstract (translated by Google)
我们描述了一种通用的分布式句子编码器的无监督学习方法。使用书籍文本的连续性，我们训练编码器 - 解码器模型，试图重构编码段落的周围句子。共享语义和语法属性的句子因此映射到相似的向量表示。接下来我们介绍一种简单的词汇扩展方法来编码未被视为训练一部分的单词，使我们能够将词汇量扩展到一百万字。在训练模型之后，我们用8个任务的线性模型提取和评估我们的向量：语义相关性，释义检测，图像 - 句子排序，问题类型分类和4个基准情绪和主观数据集。最终的结果是一个现成的编码器，可以生成高度通用的句子表示，这些表示在实践中是健壮的并且表现良好。我们将公开我们的编码器。

##### URL
[https://arxiv.org/abs/1506.06726](https://arxiv.org/abs/1506.06726)

##### PDF
[https://arxiv.org/pdf/1506.06726](https://arxiv.org/pdf/1506.06726)

