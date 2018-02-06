---
layout: post
title: "Multimodal Sentiment Analysis with Word-Level Fusion and Reinforcement Learning"
date: 2018-02-03 06:30:09
categories: arXiv_AI
tags: arXiv_AI Sentiment Attention Face Sentiment_Classification Reinforcement_Learning Embedding RNN Classification Prediction
author: Minghai Chen, Sen Wang, Paul Pu Liang, Tadas Baltru&#x161;aitis, Amir Zadeh, Louis-Philippe Morency
mathjax: true
---

* content
{:toc}

##### Abstract
With the increasing popularity of video sharing websites such as YouTube and Facebook, multimodal sentiment analysis has received increasing attention from the scientific community. Contrary to previous works in multimodal sentiment analysis which focus on holistic information in speech segments such as bag of words representations and average facial expression intensity, we develop a novel deep architecture for multimodal sentiment analysis that performs modality fusion at the word level. In this paper, we propose the Gated Multimodal Embedding LSTM with Temporal Attention (GME-LSTM(A)) model that is composed of 2 modules. The Gated Multimodal Embedding alleviates the difficulties of fusion when there are noisy modalities. The LSTM with Temporal Attention performs word level fusion at a finer fusion resolution between input modalities and attends to the most important time steps. As a result, the GME-LSTM(A) is able to better model the multimodal structure of speech through time and perform better sentiment comprehension. We demonstrate the effectiveness of this approach on the publicly-available Multimodal Corpus of Sentiment Intensity and Subjectivity Analysis (CMU-MOSI) dataset by achieving state-of-the-art sentiment classification and regression results. Qualitative analysis on our model emphasizes the importance of the Temporal Attention Layer in sentiment prediction because the additional acoustic and visual modalities are noisy. We also demonstrate the effectiveness of the Gated Multimodal Embedding in selectively filtering these noisy modalities out. Our results and analysis open new areas in the study of sentiment analysis in human communication and provide new models for multimodal fusion.

##### Abstract (translated by Google)
随着YouTube，Facebook等视频共享网站的日益普及，多模态情感分析越来越受到科学界的关注。与之前在多语气情绪分析方面的研究相比，这些分析方法集中在语音片段中的整体信息，例如词汇表示和平均面部表情强度，我们开发了一种新型的多模态情感分析深层架构，在词层面进行模态融合。在本文中，我们提出了由2个模块组成的具有时间注意的门控多模式嵌入式LSTM（GME-LSTM（A））模型。门控多模式嵌入缓解了有噪声模式时融合的困难。具有时间注意力的LSTM在输入模式之间以更精细的融合分辨率执行字级融合，并参加最重要的时间步骤。因此，GME-LSTM（A）能够更好地模拟语音的多模态结构，并且能够更好地理解情感。我们通过实现最先进的情感分类和回归结果来证明这种方法在公众可用的情感强度和主观性分析（CMU-MOSI）数据集的多模态语料库上的有效性。对我们模型的定性分析强调时间关注层在情感预测中的重要性，因为额外的声学和视觉方式是嘈杂的。我们还演示了选通滤波这些噪声模式的门控多模式嵌入的有效性。我们的研究成果和分析开辟了人类交流情感分析研究的新领域，为多模态融合提供了新的模式。

##### URL
[http://arxiv.org/abs/1802.00924](http://arxiv.org/abs/1802.00924)

##### PDF
[http://arxiv.org/pdf/1802.00924](http://arxiv.org/pdf/1802.00924)

