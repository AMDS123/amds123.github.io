---
layout: post
title: "An Efficient End-to-End Neural Model for Handwritten Text Recognition"
date: 2018-07-20 09:55:09
categories: arXiv_CV
tags: arXiv_CV CNN RNN Recognition
author: Arindam Chowdhury, Lovekesh Vig
mathjax: true
---

* content
{:toc}

##### Abstract
Offline handwritten text recognition from images is an important problem for enterprises attempting to digitize large volumes of handmarked scanned documents/reports. Deep recurrent models such as Multi-dimensional LSTMs have been shown to yield superior performance over traditional Hidden Markov Model based approaches that suffer from the Markov assumption and therefore lack the representational power of RNNs. In this paper we introduce a novel approach that combines a deep convolutional network with a recurrent Encoder-Decoder network to map an image to a sequence of characters corresponding to the text present in the image. The entire model is trained end-to-end using Focal Loss, an improvement over the standard Cross-Entropy loss that addresses the class imbalance problem, inherent to text recognition. To enhance the decoding capacity of the model, Beam Search algorithm is employed which searches for the best sequence out of a set of hypotheses based on a joint distribution of individual characters. Our model takes as input a downsampled version of the original image thereby making it both computationally and memory efficient. The experimental results were benchmarked against two publicly available datasets, IAM and RIMES. We surpass the state-of-the-art word level accuracy on the evaluation set of both datasets by 3.5% &amp; 1.1%, respectively.

##### Abstract (translated by Google)
对于试图数字化大量手写扫描文档/报告的企业来说，图像中的离线手写文本识别是一个重要问题。诸如多维LSTM之类的深度递归模型已经显示出优于传统的基于隐马尔可夫模型的方法的性能，该方法遭受马尔可夫假设，因此缺乏RNN的代表性能力。在本文中，我们介绍了一种新方法，它将深度卷积网络与循环编码器 - 解码器网络相结合，将图像映射到与图像中存在的文本相对应的字符序列。使用Focal Loss对整个模型进行端到端的训练，这是对标准交叉熵损失的改进，解决了文本识别所固有的类不平衡问题。为了增强模型的解码能力，采用波束搜索算法，该算法基于各个字符的联合分布从一组假设中搜索最佳序列。我们的模型将原始图像的下采样版本作为输入，从而使其在计算和存储器方面都有效。实验结果以两个公开可用的数据集IAM和RIMES为基准。我们在两个数据集的评估集上超过了最先进的字级精度3.5％＆amp;分别为1.1％。

##### URL
[http://arxiv.org/abs/1807.07965](http://arxiv.org/abs/1807.07965)

##### PDF
[http://arxiv.org/pdf/1807.07965](http://arxiv.org/pdf/1807.07965)

