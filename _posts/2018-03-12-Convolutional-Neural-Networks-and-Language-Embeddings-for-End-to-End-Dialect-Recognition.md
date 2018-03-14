---
layout: post
title: "Convolutional Neural Networks and Language Embeddings for End-to-End Dialect Recognition"
date: 2018-03-12 23:04:11
categories: arXiv_SD
tags: arXiv_SD Embedding CNN Recognition
author: Suwon Shon, Ahmed Ali, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
Dialect identification (DID) is a special case of general language identification (LID), but a more challenging problem due to the linguistic similarity between dialects. In this paper, we propose an end-to-end DID system and a Siamese neural network to extract language embeddings. We use both acoustic and linguistic features for the DID task on the Arabic dialectal speech dataset: Multi-Genre Broadcast 3 (MGB-3). The end-to-end DID system was trained using three kinds of acoustic features: Mel-Frequency Cepstral Coefficients (MFCCs), log Mel-scale Filter Bank energies (FBANK) and spectrogram energies. We also investigated a dataset augmentation approach to achieve robust performance with limited data resources. Our linguistic feature research focused on learning similarities and dissimilarities between dialects using the Siamese network, so that we can reduce feature dimensionality as well as improve DID performance. The best system using a single feature set achieves 73% accuracy, while a fusion system using multiple features yields 78% on the MGB-3 dialect test set consisting of 5 dialects. The experimental results indicate that FBANK features achieve slightly better results than MFCCs. Dataset augmentation via speed perturbation appears to add significant robustness to the system. Although the Siamese network with language embeddings did not achieve as good a result as the end-to-end DID system, the two approaches had good synergy when combined together in a fused system.

##### Abstract (translated by Google)
方言识别（DID）是一般语言识别（LID）的特例，但由于方言在语言上的相似性而成为一个更具挑战性的问题。在本文中，我们提出了一个端到端的DID系统和一个Siamese神经网络来提取语言嵌入。我们在阿拉伯语方言语音数据集上使用DID任务的声学和语言特征：多流派广播3（MGB-3）。端对端DID系统使用三种声学特征进行训练：Mel频率倒谱系数（MFCC），对数梅尔尺度滤波器组能量（FBANK）和频谱图能量。我们还调查了数据集增强方法，以在有限的数据资源下实现强大的性能。我们的语言特征研究集中在使用Siamese网络学习方言之间的相似性和差异性，以便我们可以减少特征维度并提高DID性能。使用单一特征集的最佳系统达到了73％的准确性，而使用多种特征的融合系统在由5种方言组成的MGB-3方言测试集上获得78％的效果。实验结果表明FBANK特征比MFCC获得稍好的结果。通过速度扰动增加数据集似乎增加了系统的显着鲁棒性。虽然带语言嵌入的Siamese网络没有达到与端到端DID系统一样好的效果，但这两种方法在融合在一起的系统中具有良好的协同作用。

##### URL
[http://arxiv.org/abs/1803.04567](http://arxiv.org/abs/1803.04567)

##### PDF
[http://arxiv.org/pdf/1803.04567](http://arxiv.org/pdf/1803.04567)

