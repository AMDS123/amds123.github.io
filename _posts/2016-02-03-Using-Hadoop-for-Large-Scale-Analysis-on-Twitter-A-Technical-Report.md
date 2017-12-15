---
layout: post
title: "Using Hadoop for Large Scale Analysis on Twitter: A Technical Report"
date: 2016-02-03 10:19:19
categories: arXiv_SD
tags: arXiv_SD Sentiment Attention Classification
author: Nikolaos Nodarakis, Spyros Sioutas, Athanasios Tsakalidis, Giannis Tzimas
mathjax: true
---

* content
{:toc}

##### Abstract
Sentiment analysis (or opinion mining) on Twitter data has attracted much attention recently. One of the system's key features, is the immediacy in communication with other users in an easy, user-friendly and fast way. Consequently, people tend to express their feelings freely, which makes Twitter an ideal source for accumulating a vast amount of opinions towards a wide diversity of topics. This amount of information offers huge potential and can be harnessed to receive the sentiment tendency towards these topics. However, since none can invest an infinite amount of time to read through these tweets, an automated decision making approach is necessary. Nevertheless, most existing solutions are limited in centralized environments only. Thus, they can only process at most a few thousand tweets. Such a sample, is not representative to define the sentiment polarity towards a topic due to the massive number of tweets published daily. In this paper, we go one step further and develop a novel method for sentiment learning in the MapReduce framework. Our algorithm exploits the hashtags and emoticons inside a tweet, as sentiment labels, and proceeds to a classification procedure of diverse sentiment types in a parallel and distributed manner. Moreover, we utilize Bloom filters to compact the storage size of intermediate data and boost the performance of our algorithm. Through an extensive experimental evaluation, we prove that our solution is efficient, robust and scalable and confirm the quality of our sentiment identification.

##### Abstract (translated by Google)
对Twitter数据的情感分析（或意见挖掘）近来备受关注。系统的关键特征之一就是以简单，用户友好和快速的方式与其他用户进行直接通信。因此，人们倾向于自由地表达自己的感受，这使得Twitter成为在广泛的话题上积累大量意见的理想来源。这种信息量提供了巨大的潜力，可以用来接受这些话题的情感倾向。但是，由于没有人可以投入无限的时间来阅读这些推文，所以自动决策方法是必要的。不过，大多数现有解决方案仅限于集中式环境。因此，他们最多只能处理几千条推文。这样一个样本，由于每天发布的大量推文，不能代表对主题的情感极性。在本文中，我们更进一步，在MapReduce框架中开发一种情感学习的新方法。我们的算法利用tweet中的hashtags和表情符号作为情感标签，并且以并行和分布的方式进行不同情感类型的分类过程。此外，我们利用Bloom过滤器来压缩中间数据的存储大小，并提高算法的性能。通过广泛的实验评估，我们证明我们的解决方案是高效，强大和可扩展的，并确认了我们的情感识别的质量。

##### URL
[https://arxiv.org/abs/1602.01248](https://arxiv.org/abs/1602.01248)

##### PDF
[https://arxiv.org/pdf/1602.01248](https://arxiv.org/pdf/1602.01248)

