---
layout: post
title: "Streaming Word Embeddings with the Space-Saving Algorithm"
date: 2017-04-24 20:55:33
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model Prediction
author: Chandler May, Kevin Duh, Benjamin Van Durme, Ashwin Lall
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a streaming (one-pass, bounded-memory) word embedding algorithm based on the canonical skip-gram with negative sampling algorithm implemented in word2vec. We compare our streaming algorithm to word2vec empirically by measuring the cosine similarity between word pairs under each algorithm and by applying each algorithm in the downstream task of hashtag prediction on a two-month interval of the Twitter sample stream. We then discuss the results of these experiments, concluding they provide partial validation of our approach as a streaming replacement for word2vec. Finally, we discuss potential failure modes and suggest directions for future work.

##### Abstract (translated by Google)
我们在word2vec中开发了一种基于负样本算法的正则跳跃式字符流（one-pass，bounded-memory）字嵌入算法。我们通过测量每种算法下的字对之间的余弦相似度，并将每个算法应用于Twitter样本流的两个月间隔的下标标签预测任务中，将我们的数据流算法与word2vec进行比较。然后我们讨论这些实验的结果，总结他们提供了我们的方法的部分验证作为word2vec的流式替换。最后，我们讨论潜在的失效模式并为未来的工作提出方向。

##### URL
[https://arxiv.org/abs/1704.07463](https://arxiv.org/abs/1704.07463)

##### PDF
[https://arxiv.org/pdf/1704.07463](https://arxiv.org/pdf/1704.07463)

