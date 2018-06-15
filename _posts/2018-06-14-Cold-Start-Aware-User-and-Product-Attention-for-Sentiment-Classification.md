---
layout: post
title: "Cold-Start Aware User and Product Attention for Sentiment Classification"
date: 2018-06-14 12:48:31
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Sparse Attention Sentiment_Classification Classification
author: Reinald Kim Amplayo, Jihyeok Kim, Sua Sung, Seung-won Hwang
mathjax: true
---

* content
{:toc}

##### Abstract
The use of user/product information in sentiment analysis is important, especially for cold-start users/products, whose number of reviews are very limited. However, current models do not deal with the cold-start problem which is typical in review websites. In this paper, we present Hybrid Contextualized Sentiment Classifier (HCSC), which contains two modules: (1) a fast word encoder that returns word vectors embedded with short and long range dependency features; and (2) Cold-Start Aware Attention (CSAA), an attention mechanism that considers the existence of cold-start problem when attentively pooling the encoded word vectors. HCSC introduces shared vectors that are constructed from similar users/products, and are used when the original distinct vectors do not have sufficient information (i.e. cold-start). This is decided by a frequency-guided selective gate vector. Our experiments show that in terms of RMSE, HCSC performs significantly better when compared with on famous datasets, despite having less complexity, and thus can be trained much faster. More importantly, our model performs significantly better than previous models when the training data is sparse and has cold-start problems.

##### Abstract (translated by Google)
在情感分析中使用用户/产品信息很重要，特别是对于冷启动用户/产品，其评论数量非常有限。但是，目前的模型并不涉及评论网站中典型的冷启动问题。在本文中，我们提出了混合情境化情感分类器（HCSC），其包含两个模块：（1）快速字编码器，其返回嵌入有短程和长程依赖性特征的字向量;和（2）冷启动感知注意（Cold-Start Aware Attention，CSAA），一种注意机制，当专注汇集编码的单词向量时考虑冷启动问题的存在。 HCSC引入了由相似用户/产品构建的共享向量，并且在原始不同向量没有足够信息（即冷启动）时使用。这由频率引导选择性门矢量决定。我们的实验表明，就RMSE而言，与着名数据集相比，HCSC的性能明显更好，尽管其复杂性较低，因此训练速度更快。更重要的是，当训练数据稀少且具有冷启动问题时，我们的模型比以前的模型执行得更好。

##### URL
[http://arxiv.org/abs/1806.05507](http://arxiv.org/abs/1806.05507)

##### PDF
[http://arxiv.org/pdf/1806.05507](http://arxiv.org/pdf/1806.05507)

