---
layout: post
title: "Towards Practical Visual Search Engine within Elasticsearch"
date: 2018-06-23 02:47:51
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Cun Mu, Jun Zhao, Guang Yang, Jing Zhang, Zheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we describe our end-to-end content-based image retrieval system built upon Elasticsearch, a well-known and popular textual search engine. As far as we know, this is the first time such a system has been implemented in eCommerce, and our efforts have turned out to be highly worthwhile. We end up with a novel and exciting visual search solution that is extremely easy to be deployed, distributed, scaled and monitored in a cost-friendly manner. Moreover, our platform is intrinsically flexible in supporting multimodal searches, where visual and textual information can be jointly leveraged in retrieval. 
 The core idea is to encode image feature vectors into a collection of string tokens in a way such that closer vectors will share more string tokens in common. By doing that, we can utilize Elasticsearch to efficiently retrieve similar images based on similarities within encoded sting tokens. As part of the development, we propose a novel vector to string encoding method, which is shown to substantially outperform the previous ones in terms of both precision and latency. 
 First-hand experiences in implementing this Elasticsearch-based platform are extensively addressed, which should be valuable to practitioners also interested in building visual search engine on top of Elasticsearch.

##### Abstract (translated by Google)
在本文中，我们描述了基于Elasticsearch构建的端到端基于内容的图像检索系统，Elasticsearch是一个众所周知的流行文本搜索引擎。据我们所知，这是第一次在电子商务中实施这样一个系统，我们的努力结果非常有价值。我们最终获得了一种新颖且令人兴奋的视觉搜索解决方案，该解决方案非常易于以便宜的方式进行部署，分发，缩放和监控。此外，我们的平台在支持多模式搜索方面具有内在的灵活性，其中视觉和文本信息可以共同用于检索。
 其核心思想是将图像特征向量编码为一组字符串标记，以便更近的向量共享更多的字符串标记。通过这样做，我们可以利用Elasticsearch根据编码的令牌令牌中的相似性有效地检索相似的图像。作为开发的一部分，我们提出了一种新颖的矢量字符串编码方法，该方法在精度和延迟方面都显着优于以前的矢量。
 在实施基于Elasticsearch的平台方面的第一手经验得到了广泛的解决，这对于那些对在Elasticsearch之上构建可视化搜索引擎感兴趣的从业者也应该是有价值的。

##### URL
[http://arxiv.org/abs/1806.08896](http://arxiv.org/abs/1806.08896)

##### PDF
[http://arxiv.org/pdf/1806.08896](http://arxiv.org/pdf/1806.08896)

