---
layout: post
title: "End-To-End Visual Speech Recognition With LSTMs"
date: 2017-01-20 16:36:09
categories: arXiv_SD
tags: arXiv_SD Knowledge Speech_Recognition RNN Classification Deep_Learning Recognition
author: Stavros Petridis, Zuwei Li, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional visual speech recognition systems consist of two stages, feature extraction and classification. Recently, several deep learning approaches have been presented which automatically extract features from the mouth images and aim to replace the feature extraction stage. However, research on joint learning of features and classification is very limited. In this work, we present an end-to-end visual speech recognition system based on Long-Short Memory (LSTM) networks. To the best of our knowledge, this is the first model which simultaneously learns to extract features directly from the pixels and perform classification and also achieves state-of-the-art performance in visual speech classification. The model consists of two streams which extract features directly from the mouth and difference images, respectively. The temporal dynamics in each stream are modelled by an LSTM and the fusion of the two streams takes place via a Bidirectional LSTM (BLSTM). An absolute improvement of 9.7% over the base line is reported on the OuluVS2 database, and 1.5% on the CUAVE database when compared with other methods which use a similar visual front-end.

##### Abstract (translated by Google)
传统的视觉语音识别系统由两个阶段组成，即特征提取和分类。最近，已经提出了几种自动从嘴图像中提取特征的深度学习方法，并且旨在替换特征提取阶段。然而，关于特征和分类的联合学习的研究是非常有限的。在这项工作中，我们提出了一个基于长短内存（LSTM）网络的端到端视觉语音识别系统。据我们所知，这是第一个同时学习从像素中直接提取特征并进行分类并在视觉语音分类中实现最新性能的模型。该模型由两个流分别直接从嘴和差异图像提取特征。每个流中的时间动态模型由LSTM建模，两个流的融合通过双向LSTM（BLSTM）进行。 OuluVS2数据库报告的基线绝对值比基准线高出9.7％，CUAVE数据库高达1.5％，与其他使用类似视觉前端的方法相比。

##### URL
[https://arxiv.org/abs/1701.05847](https://arxiv.org/abs/1701.05847)

##### PDF
[https://arxiv.org/pdf/1701.05847](https://arxiv.org/pdf/1701.05847)

