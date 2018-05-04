---
layout: post
title: "Ladder Networks for Emotion Recognition: Using Unsupervised Auxiliary Tasks to Improve Predictions of Emotional Attributes"
date: 2018-04-28 15:08:41
categories: arXiv_SD
tags: arXiv_SD Regularization Prediction Recognition
author: Srinivas Parthasarathy, Carlos Busso
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing emotions using few attribute dimensions such as arousal, valence and dominance provides the flexibility to effectively represent complex range of emotional behaviors. Conventional methods to learn these emotional descriptors primarily focus on separate models to recognize each of these attributes. Recent work has shown that learning these attributes together regularizes the models, leading to better feature representations. This study explores new forms of regularization by adding unsupervised auxiliary tasks to reconstruct hidden layer representations. This auxiliary task requires the denoising of hidden representations at every layer of an auto-encoder. The framework relies on ladder networks that utilize skip connections between encoder and decoder layers to learn powerful representations of emotional dimensions. The results show that ladder networks improve the performance of the system compared to baselines that individually learn each attribute, and conventional denoising autoencoders. Furthermore, the unsupervised auxiliary tasks have promising potential to be used in a semi-supervised setting, where few labeled sentences are available.

##### Abstract (translated by Google)
使用少量属性维度（如觉醒，效价和主导）来识别情绪提供了灵活性来有效地表示复杂的情绪行为范围。学习这些情绪描述符的传统方法主要集中在单独的模型上以识别每个属性。最近的研究表明，一起学习这些属性可以使模型正常化，从而导致更好的特征表示。本研究通过添加无监督的辅助任务来重构隐藏层表示来探索新的正则化形式。这个辅助任务需要在自动编码器的每一层上对隐藏表示进行去噪。该框架依赖于梯形网络，利用编码器和解码器层之间的跳过连接来学习情感维度的强大表示。结果表明，与单独学习每个属性的基线和传统的去噪自动编码器相比，梯形网络改善了系统的性能。此外，无监督辅助任务有希望用于半监督环境，这里只有很少的标记句子可用。

##### URL
[https://arxiv.org/abs/1804.10816](https://arxiv.org/abs/1804.10816)

##### PDF
[https://arxiv.org/pdf/1804.10816](https://arxiv.org/pdf/1804.10816)

