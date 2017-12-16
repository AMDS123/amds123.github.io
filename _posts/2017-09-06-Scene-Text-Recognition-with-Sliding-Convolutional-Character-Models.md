---
layout: post
title: "Scene Text Recognition with Sliding Convolutional Character Models"
date: 2017-09-06 09:01:53
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN Classification Recognition
author: Fei Yin, Yi-Chao Wu, Xu-Yao Zhang, Cheng-Lin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Scene text recognition has attracted great interests from the computer vision and pattern recognition community in recent years. State-of-the-art methods use concolutional neural networks (CNNs), recurrent neural networks with long short-term memory (RNN-LSTM) or the combination of them. In this paper, we investigate the intrinsic characteristics of text recognition, and inspired by human cognition mechanisms in reading texts, we propose a scene text recognition method with character models on convolutional feature map. The method simultaneously detects and recognizes characters by sliding the text line image with character models, which are learned end-to-end on text line images labeled with text transcripts. The character classifier outputs on the sliding windows are normalized and decoded with Connectionist Temporal Classification (CTC) based algorithm. Compared to previous methods, our method has a number of appealing properties: (1) It avoids the difficulty of character segmentation which hinders the performance of segmentation-based recognition methods; (2) The model can be trained simply and efficiently because it avoids gradient vanishing/exploding in training RNN-LSTM based models; (3) It bases on character models trained free of lexicon, and can recognize unknown words. (4) The recognition process is highly parallel and enables fast recognition. Our experiments on several challenging English and Chinese benchmarks, including the IIIT-5K, SVT, ICDAR03/13 and TRW15 datasets, demonstrate that the proposed method yields superior or comparable performance to state-of-the-art methods while the model size is relatively small.

##### Abstract (translated by Google)
近年来，场景文本识别已经引起了计算机视觉和模式识别界的极大兴趣。最先进的方法使用精细神经网络（CNN），具有长期短期记忆（RNN-LSTM）的递归神经网络或它们的组合。本文研究了文本识别的内在特征，在阅读文本的过程中受到人类认知机制的启发，提出了一种在卷积特征图上具有特征模型的场景文本识别方法。该方法通过将字符模型滑动文本行图像来同时检测和识别字符，所述字符模型在由文本转录本标记的文本行图像上端对端学习。基于连接主义时间分类（CTC）的算法对滑动窗口上的字符分类器输出进行归一化和解码。与以前的方法相比，我们的方法具有很多吸引人的特点：（1）避免了字符分割的困难，阻碍了基于分词的识别方法的性能; （2）在训练RNN-LSTM模型的基础上避免了梯度消失/爆炸，可以简单有效地训练模型; （3）它基于没有词汇训练的人物模型，能够识别未知的单词。 （4）识别过程高度平行，能够快速识别。我们对包括IIIT-5K，SVT，ICDAR03 / 13和TRW15数据集在内的几个具有挑战性的英文和中文基准的实验表明，所提出的方法与现有技术的方法相比具有优越或可比的性能，而模型尺寸相对较小小。

##### URL
[https://arxiv.org/abs/1709.01727](https://arxiv.org/abs/1709.01727)

##### PDF
[https://arxiv.org/pdf/1709.01727](https://arxiv.org/pdf/1709.01727)

