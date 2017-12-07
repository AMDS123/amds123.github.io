---
layout: post
title: "EmTaggeR: A Word Embedding Based Novel Method for Hashtag Recommendation on Twitter"
date: 2017-12-05 10:29:14
categories: arXiv_CL
tags: arXiv_CL Embedding Recommendation
author: Kuntal Dey, Ritvik Shrivastava, Saroj Kaushik, L. Venkata Subramaniam
mathjax: true
---

* content
{:toc}

##### Abstract
The hashtag recommendation problem addresses recommending (suggesting) one or more hashtags to explicitly tag a post made on a given social network platform, based upon the content and context of the post. In this work, we propose a novel methodology for hashtag recommendation for microblog posts, specifically Twitter. The methodology, EmTaggeR, is built upon a training-testing framework that builds on the top of the concept of word embedding. The training phase comprises of learning word vectors associated with each hashtag, and deriving a word embedding for each hashtag. We provide two training procedures, one in which each hashtag is trained with a separate word embedding model applicable in the context of that hashtag, and another in which each hashtag obtains its embedding from a global context. The testing phase constitutes computing the average word embedding of the test post, and finding the similarity of this embedding with the known embeddings of the hashtags. The tweets that contain the most-similar hashtag are extracted, and all the hashtags that appear in these tweets are ranked in terms of embedding similarity scores. The top-K hashtags that appear in this ranked list, are recommended for the given test post. Our system produces F1 score of 50.83%, improving over the LDA baseline by around 6.53 times, outperforming the best-performing system known in the literature that provides a lift of 6.42 times. EmTaggeR is a fast, scalable and lightweight system, which makes it practical to deploy in real-life applications.

##### Abstract (translated by Google)
主题标签推荐问题解决了基于帖子的内容和上下文推荐（建议）一个或多个主题标签以明确地标记在给定社交网络平台上进行的帖子。在这项工作中，我们提出了一个新颖的微博帖子标签推荐方法，特别是Twitter。 EmTaggeR的方法建立在一个训练测试框架的基础上，这个框架建立在词嵌入的概念之上。训练阶段包括学习与每个井号标签相关联的字向量，并且为每个井号标签导出字嵌入。我们提供了两个训练程序，其中每个标签被用在该标签的上下文中适用的单独的单词嵌入模型进行训练，另一个是每个标签从全局上下文中获得其嵌入。测试阶段包括计算测试帖子的平均词嵌入，并找出这个嵌入与已知的主题标签嵌入的相似度。包含最相似哈希标签的推文被提取，并且在这些推文中出现的所有哈希标签按照嵌入相似性分数排序。出现在这个排名列表中的top-K hashtags被推荐用于给定的测试帖子。我们的系统产生了50.83％的F1得分，比LDA基线提高了6.53倍左右，超过了文献中提供的6.42倍的最佳表现系统。 EmTaggeR是一个快速，可扩展和轻量级的系统，可以在实际应用中部署。

##### URL
[http://arxiv.org/abs/1712.01562](http://arxiv.org/abs/1712.01562)

##### PDF
[http://arxiv.org/pdf/1712.01562](http://arxiv.org/pdf/1712.01562)

