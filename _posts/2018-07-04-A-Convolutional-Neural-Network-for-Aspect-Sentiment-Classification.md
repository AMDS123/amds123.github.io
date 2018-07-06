---
layout: post
title: "A Convolutional Neural Network for Aspect Sentiment Classification"
date: 2018-07-04 09:07:34
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention Sentiment_Classification CNN RNN Classification
author: Yongping Xing, Chuangbai Xiao, Yifei Wu, Ziming Ding
mathjax: true
---

* content
{:toc}

##### Abstract
With the development of the Internet, natural language processing (NLP), in which sentiment analysis is an important task, became vital in information processing.Sentiment analysis includes aspect sentiment classification. Aspect sentiment can provide complete and in-depth results with increased attention on aspect-level. Different context words in a sentence influence the sentiment polarity of a sentence variably, and polarity varies based on the different aspects in a sentence. Take the sentence, 'I bought a new camera. The picture quality is amazing but the battery life is too short.'as an example. If the aspect is picture quality, then the expected sentiment polarity is 'positive', if the battery life aspect is considered, then the sentiment polarity should be 'negative'; therefore, aspect is important to consider when we explore aspect sentiment in the sentence. Recurrent neural network (RNN) is regarded as a good model to deal with natural language processing, and RNNs has get good performance on aspect sentiment classification including Target-Dependent LSTM (TD-LSTM) ,Target-Connection LSTM (TC-LSTM) (Tang, 2015a, b), AE-LSTM, AT-LSTM, AEAT-LSTM (Wang et al., 2016).There are also extensive literatures on sentiment classification utilizing convolutional neural network, but there is little literature on aspect sentiment classification using convolutional neural network. In our paper, we develop attention-based input layers in which aspect information is considered by input layer. We then incorporate attention-based input layers into convolutional neural network (CNN) to introduce context words information. In our experiment, incorporating aspect information into CNN improves the latter's aspect sentiment classification performance without using syntactic parser or external sentiment lexicons in a benchmark dataset from Twitter but get better performance compared with other models.

##### Abstract (translated by Google)
随着互联网的发展，情感分析成为一项重要任务的自然语言处理（NLP）在信息处理中变得至关重要。情感分析包括方面情感分类。方面情绪可以提供完整和深入的结果，并在方面层面上得到更多的关注。句子中的不同上下文词可变地影响句子的情感极性，并且极性基于句子中的不同方面而变化。拿一句话，'我买了一台新相机。图像质量惊人，但电池寿命太短。“举个例子。如果方面是图像质量，那么预期的情绪极性是“正”，如果考虑电池寿命方面，那么情绪极性应该是“负”;因此，当我们探讨句子中的方面情绪时，方面是很重要的。递归神经网络（RNN）被认为是处理自然语言处理的良好模型，并且RNN在方面情感分类方面获得了良好的性能，包括目标相关LSTM（TD-LSTM），目标连接LSTM（TC-LSTM）（ Tang，2015a，b），AE-LSTM，AT-LSTM，AEAT-LSTM（Wang et al。，2016）。关于利用卷积神经网络进行情感分类的文献也很多，但关于使用方面情感分类的文献很少。卷积神经网络。在我们的论文中，我们开发了基于注意力的输入层，其中方面信息由输入层考虑。然后，我们将基于注意力的输入层结合到卷积神经网络（CNN）中以引入上下文单词信息。在我们的实验中，将方面信息纳入CNN可以改善后者的方面情感分类性能，而无需在Twitter的基准数据集中使用语法分析器或外部情感词典，但与其他模型相比可以获得更好的性能。

##### URL
[http://arxiv.org/abs/1807.01704](http://arxiv.org/abs/1807.01704)

##### PDF
[http://arxiv.org/pdf/1807.01704](http://arxiv.org/pdf/1807.01704)

