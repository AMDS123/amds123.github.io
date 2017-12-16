---
layout: post
title: "Recurrent neural networks based Indic word-wise script identification using character-wise training"
date: 2017-09-11 01:35:22
categories: arXiv_CV
tags: arXiv_CV RNN Prediction Recognition
author: Rohun Tripathi, Riccha Tripati
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel methodology of Indic handwritten script recognition using Recurrent Neural Networks and addresses the problem of script recognition in poor data scenarios, such as when only character level online data is available. It is based on the hypothesis that curves of online character data comprise sufficient information for prediction at the word level. Online character data is used to train RNNs using BLSTM architecture which are then used to make predictions of online word level data. These prediction results on the test set are at par with prediction results of models trained with online word data, while the training of the character level model is much less data intensive and takes much less time. Performance for binary-script models and then 5 Indic script models are reported, along with comparison with HMM models.The system is extended for offline data prediction. Raw offline data lacks the temporal information available in online data and required for prediction using models trained with online data. To overcome this, stroke recovery is implemented and the strokes are utilized for predicting using the online character level models. The performance on character and word level offline data is reported.

##### Abstract (translated by Google)
本文提出了一种使用递归神经网络的手写脚本识别的新方法，并解决了在数据情况较差的情况下（例如只有字符级在线数据可用时）的脚本识别问题。它是基于在线字符数据的曲线包括足够的信息在字级预测的假设。在线字符数据用于训练使用BLSTM架构的RNN，然后用于预测在线字级数据。这些测试集的预测结果与使用在线单词数据训练的模型的预测结果是一致的，而字符级模型的训练数据密集程度要低得多，而且花费的时间也少得多。报告二进制脚本模型的性能，然后报告5个印度语脚本模型，并与HMM模型进行比较。该系统被扩展用于离线数据预测。原始离线数据缺乏在线数据中可用的时间信息，并且需要使用在线数据训练的模型进行预测。为了克服这个问题，笔画恢复被执行，笔画被用来预测使用在线角色等级模型。报告字符和词级脱机数据的性能。

##### URL
[https://arxiv.org/abs/1709.03209](https://arxiv.org/abs/1709.03209)

##### PDF
[https://arxiv.org/pdf/1709.03209](https://arxiv.org/pdf/1709.03209)

