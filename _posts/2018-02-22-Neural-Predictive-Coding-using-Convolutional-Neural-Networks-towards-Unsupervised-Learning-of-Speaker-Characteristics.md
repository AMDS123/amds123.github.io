---
layout: post
title: "Neural Predictive Coding using Convolutional Neural Networks towards Unsupervised Learning of Speaker Characteristics"
date: 2018-02-22 00:37:49
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Embedding CNN Classification Recognition
author: Arindam Jati, Panayiotis Georgiou
mathjax: true
---

* content
{:toc}

##### Abstract
Learning speaker-specific features is vital in many applications like speaker recognition, diarization and speech recognition. This paper provides a novel approach, we term Neural Predictive Coding (NPC), to learn speaker-specific characteristics in a completely unsupervised manner from large amounts of unlabeled training data that even contain multi-speaker audio streams. The NPC framework exploits the proposed short-term active-speaker stationarity hypothesis which assumes two temporally-close short speech segments belong to the same speaker, and thus a common representation that can encode the commonalities of both the segments, should capture the vocal characteristics of that speaker. We train a convolutional deep siamese network to produce "speaker embeddings" by optimizing a loss function that increases between-speaker variability and decreases within-speaker variability. The trained NPC model can produce these embeddings by projecting any test audio stream into a high dimensional manifold where speech frames of the same speaker come closer than they do in the raw feature space. Results in the frame-level speaker classification experiment along with the visualization of the embeddings manifest the distinctive ability of the NPC model to learn short-term speaker-specific features as compared to raw MFCC features and i-vectors. The utterance-level speaker classification experiments show that concatenating simple statistics of the short-term NPC embeddings over the whole utterance with the utterance-level i-vectors can give useful complimentary information to the i-vectors and boost the classification accuracy. The results also show the efficacy of this technique to learn those characteristics from large amounts of unlabeled training set which has no prior information about the environment of the test set.

##### Abstract (translated by Google)
学习说话者特有的功能在许多应用中非常重要，如说话人识别，diarization和语音识别。本文提供了一种新颖的方法，我们称为神经预测编码（NPC），以完全无监督的方式从大量未标记的训练数据中学习说话者特有的特征，甚至包含多扬声器音频流。 NPC框架利用所提出的短期主动说话者平稳性假设，假设两个时间上接近的短语音段属于同一说话者，因此可以对两个段的共同性进行编码的共同表示应该捕捉语音特征那个发言者。我们通过优化损失函数来训练卷积深度暹罗网络，以产生“说话人嵌入”，从而增加说话人之间的差异性并减少说话者之间的差异性。训练好的NPC模型可以通过将任何测试音频流投影到高维流形中来产生这些嵌入，其中相同扬声器的语音帧比它们在原始特征空间中更接近。框架级别的说话人分类实验中的结果与嵌入的可视化一起显示了NPC模型与原始MFCC特征和i向量相比学习短期说话者特定特征的独特能力。话语级别的说话人分类实验表明，将整个话语中的短期NPC嵌入的简单统计与话语级别的i向量连接起来可以为i向量提供有用的互补信息并提高分类准确性。结果还显示了该技术从大量未标记的训练集中学习这些特征的功效，该训练集没有关于测试集的环境的先验信息。

##### URL
[http://arxiv.org/abs/1802.07860](http://arxiv.org/abs/1802.07860)

##### PDF
[http://arxiv.org/pdf/1802.07860](http://arxiv.org/pdf/1802.07860)

