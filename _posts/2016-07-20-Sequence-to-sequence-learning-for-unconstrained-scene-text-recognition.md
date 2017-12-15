---
layout: post
title: "Sequence to sequence learning for unconstrained scene text recognition"
date: 2016-07-20 21:02:16
categories: arXiv_CV
tags: arXiv_CV CNN RNN Relation Recognition
author: Ahmed Mamdouh A. Hassanien
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we present a state-of-the-art approach for unconstrained natural scene text recognition. We propose a cascade approach that incorporates a convolutional neural network (CNN) architecture followed by a long short term memory model (LSTM). The CNN learns visual features for the characters and uses them with a softmax layer to detect sequence of characters. While the CNN gives very good recognition results, it does not model relation between characters, hence gives rise to false positive and false negative cases (confusing characters due to visual similarities like "g" and "9", or confusing background patches with characters; either removing existing characters or adding non-existing ones) To alleviate these problems we leverage recent developments in LSTM architectures to encode contextual information. We show that the LSTM can dramatically reduce such errors and achieve state-of-the-art accuracy in the task of unconstrained natural scene text recognition. Moreover we manually remove all occurrences of the words that exist in the test set from our training set to test whether our approach will generalize to unseen data. We use the ICDAR 13 test set for evaluation and compare the results with the state of the art approaches [11, 18]. We finally present an application of the work in the domain of for traffic monitoring.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种无约束自然场景文本识别的最先进的方法。我们提出了一种级联方法，其结合了卷积神经网络（CNN）架构，随后是长期短期记忆模型（LSTM）。 CNN学习字符的视觉特征，并用softmax图层来检测字符序列。虽然CNN的识别效果非常好，但是它并没有模拟人物之间的关系，因此会产生假阳性和假阴性的情况（混淆了由于“g”和“9”等视觉相似性造成的字符混淆，要么删除现有的字符，要么添加不存在的字符）为了缓解这些问题，我们利用LSTM体系结构的最新发展来编码上下文信息。我们表明，LSTM可以显着减少这种错误，并在不受约束的自然场景文本识别任务中达到最新的精度。此外，我们手动删除在我们的训练集中测试集中存在的所有词语，以测试我们的方法是否会推广到看不见的数据。我们使用ICDAR 13测试集进行评估，并将结果与​​现有技术的方法进行比较[11,18]。我们最后介绍了在交通监控领域的应用。

##### URL
[https://arxiv.org/abs/1607.06125](https://arxiv.org/abs/1607.06125)

##### PDF
[https://arxiv.org/pdf/1607.06125](https://arxiv.org/pdf/1607.06125)

