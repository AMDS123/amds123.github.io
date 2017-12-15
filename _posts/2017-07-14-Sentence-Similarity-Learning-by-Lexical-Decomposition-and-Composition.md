---
layout: post
title: "Sentence Similarity Learning by Lexical Decomposition and Composition"
date: 2017-07-14 19:51:10
categories: arXiv_SD
tags: arXiv_SD
author: Zhiguo Wang, Haitao Mi, Abraham Ittycheriah
mathjax: true
---

* content
{:toc}

##### Abstract
Most conventional sentence similarity methods only focus on similar parts of two input sentences, and simply ignore the dissimilar parts, which usually give us some clues and semantic meanings about the sentences. In this work, we propose a model to take into account both the similarities and dissimilarities by decomposing and composing lexical semantics over sentences. The model represents each word as a vector, and calculates a semantic matching vector for each word based on all words in the other sentence. Then, each word vector is decomposed into a similar component and a dissimilar component based on the semantic matching vector. After this, a two-channel CNN model is employed to capture features by composing the similar and dissimilar components. Finally, a similarity score is estimated over the composed feature vectors. Experimental results show that our model gets the state-of-the-art performance on the answer sentence selection task, and achieves a comparable result on the paraphrase identification task.

##### Abstract (translated by Google)
大多数传统的句子相似性方法只关注两个输入句子的相似部分，而忽略不相似的部分，这些部分通常会给我们提供一些句子的线索和语义意义。在这项工作中，我们提出了一个模型，通过分解和合成句子中的词汇语义来考虑相似性和不相似性。该模型将每个单词表示为一个矢量，并基于另一个句子中的所有单词计算每个单词的语义匹配矢量。然后，基于语义匹配矢量将每个单词向量分解成相似的成分和不相似的成分。之后，采用双信道CNN模型通过组合相似和不相似的组件来捕获特征。最后，在组合的特征向量上估计相似度分数。实验结果表明，我们的模型在回答句子选择任务上得到了最新的表现，并且在复述识别任务上取得了可比的结果。

##### URL
[https://arxiv.org/abs/1602.07019](https://arxiv.org/abs/1602.07019)

##### PDF
[https://arxiv.org/pdf/1602.07019](https://arxiv.org/pdf/1602.07019)

