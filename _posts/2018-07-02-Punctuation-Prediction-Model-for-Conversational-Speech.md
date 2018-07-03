---
layout: post
title: "Punctuation Prediction Model for Conversational Speech"
date: 2018-07-02 09:06:27
categories: arXiv_CL
tags: arXiv_CL Embedding CNN RNN Prediction
author: Piotr &#x17b;elasko, Piotr Szyma&#x144;ski, Jan Mizgajski, Adrian Szymczak, Yishay Carmiel, Najim Dehak
mathjax: true
---

* content
{:toc}

##### Abstract
An ASR system usually does not predict any punctuation or capitalization. Lack of punctuation causes problems in result presentation and confuses both the human reader andoff-the-shelf natural language processing algorithms. To overcome these limitations, we train two variants of Deep Neural Network (DNN) sequence labelling models - a Bidirectional Long Short-Term Memory (BLSTM) and a Convolutional Neural Network (CNN), to predict the punctuation. The models are trained on the Fisher corpus which includes punctuation annotation. In our experiments, we combine time-aligned and punctuated Fisher corpus transcripts using a sequence alignment algorithm. The neural networks are trained on Common Web Crawl GloVe embedding of the words in Fisher transcripts aligned with conversation side indicators and word time infomation. The CNNs yield a better precision and BLSTMs tend to have better recall. While BLSTMs make fewer mistakes overall, the punctuation predicted by the CNN is more accurate - especially in the case of question marks. Our results constitute significant evidence that the distribution of words in time, as well as pre-trained embeddings, can be useful in the punctuation prediction task.

##### Abstract (translated by Google)
ASR系统通常不会预测任何标点符号或大小写。缺少标点符号会导致结果呈现出现问题，并且会混淆人类读者和现成的自然语言处理算法。为了克服这些限制，我们训练两种变体的深度神经网络（DNN）序列标记模型 - 双向长短期记忆（BLSTM）和卷积神经网络（CNN），以预测标点符号。模型在Fisher语料库上进行训练，其中包括标点符号注释。在我们的实验中，我们使用序列比对算法组合时间对齐和间断的Fisher语料库转录本。神经网络在Common Web Crawl GloVe上进行训练，在Fisher转录本中嵌入单词，与会话侧指示符和单词时间信息一致。 CNN产生更好的精度，而BLSTM往往具有更好的回忆性。虽然BLSTM整体上犯的错误较少，但CNN预测的标点符号更准确 - 尤其是在问号的情况下。我们的结果构成了重要的证据，即时间词的分布以及预训练的嵌入在标点预测任务中可能是有用的。

##### URL
[http://arxiv.org/abs/1807.00543](http://arxiv.org/abs/1807.00543)

##### PDF
[http://arxiv.org/pdf/1807.00543](http://arxiv.org/pdf/1807.00543)

