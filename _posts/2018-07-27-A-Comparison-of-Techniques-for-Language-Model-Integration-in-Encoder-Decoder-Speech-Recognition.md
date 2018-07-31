---
layout: post
title: "A Comparison of Techniques for Language Model Integration in Encoder-Decoder Speech Recognition"
date: 2018-07-27 23:33:33
categories: arXiv_AI
tags: arXiv_AI Attention GAN Speech_Recognition Language_Model Recognition
author: Shubham Toshniwal, Anjuli Kannan, Chung-Cheng Chiu, Yonghui Wu, Tara N Sainath, Karen Livescu
mathjax: true
---

* content
{:toc}

##### Abstract
Attention-based recurrent neural encoder-decoder models present an elegant solution to the automatic speech recognition problem. This approach folds the acoustic model, pronunciation model, and language model into a single network and requires only a parallel corpus of speech and text for training. However, unlike in conventional approaches that combine separate acoustic and language models, it is not clear how to use additional (unpaired) text. While there has been previous work on methods addressing this problem, a thorough comparison among methods is still lacking. In this paper, we compare a suite of past methods and some of our own proposed methods for using unpaired text data to improve encoder-decoder models. For evaluation, we use the medium-sized Switchboard data set and the large-scale Google voice search and dictation data sets. Our results confirm the benefits of using unpaired text across a range of methods and data sets. Surprisingly, for first-pass decoding, the rather simple approach of shallow fusion performs best across data sets. However, for Google data sets we find that cold fusion has a lower oracle error rate and outperforms other approaches after second-pass rescoring on the Google voice search data set.

##### Abstract (translated by Google)
基于注意的递归神经编码器 - 解码器模型为自动语音识别问题提供了一种优雅的解决方案。该方法将声学模型，发音模型和语言模型折叠成单个网络，并且仅需要用于训练的平行语音和文本语料库。然而，与结合单独的声学和语言模型的传统方法不同，不清楚如何使用附加（未配对）文本。虽然以前有关于解决这个问题的方法的工作，但仍然缺乏对方法之间的彻底比较。在本文中，我们比较了一套过去的方法和一些我们自己提出的使用不成对文本数据来改进编码器 - 解码器模型的方法。为了进行评估，我们使用中型交换机数据集和大规模Google语音搜索和听写数据集。我们的结果证实了在一系列方法和数据集中使用不成对文本的好处。令人惊讶的是，对于第一次通过解码，浅融合的相当简单的方法在数据集中表现最佳。然而，对于谷歌数据集，我们发现冷聚变具有较低的oracle错误率，并且在谷歌语音搜索数据集上第二次重新扫描后表现优于其他方法。

##### URL
[http://arxiv.org/abs/1807.10857](http://arxiv.org/abs/1807.10857)

##### PDF
[http://arxiv.org/pdf/1807.10857](http://arxiv.org/pdf/1807.10857)

