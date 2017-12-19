---
layout: post
title: "A hypothesize-and-verify framework for Text Recognition using Deep Recurrent Neural Networks"
date: 2015-02-26 13:18:09
categories: arXiv_CV
tags: arXiv_CV Segmentation RNN Language_Model Recognition
author: Anupama Ray, Sai Rajeswar, Santanu Chaudhury
mathjax: true
---

* content
{:toc}

##### Abstract
Deep LSTM is an ideal candidate for text recognition. However text recognition involves some initial image processing steps like segmentation of lines and words which can induce error to the recognition system. Without segmentation, learning very long range context is difficult and becomes computationally intractable. Therefore, alternative soft decisions are needed at the pre-processing level. This paper proposes a hybrid text recognizer using a deep recurrent neural network with multiple layers of abstraction and long range context along with a language model to verify the performance of the deep neural network. In this paper we construct a multi-hypotheses tree architecture with candidate segments of line sequences from different segmentation algorithms at its different branches. The deep neural network is trained on perfectly segmented data and tests each of the candidate segments, generating unicode sequences. In the verification step, these unicode sequences are validated using a sub-string match with the language model and best first search is used to find the best possible combination of alternative hypothesis from the tree structure. Thus the verification framework using language models eliminates wrong segmentation outputs and filters recognition errors.

##### Abstract (translated by Google)
Deep LSTM是文本识别的理想选择。然而，文本识别涉及一些初始的图像处理步骤，如线条和词的分割，这可能会导致识别系统的错误。没有分割，学习非常远距离的上下文是困难的，变得计算上难以处理。因此，在预处理级别需要替代的软判决。本文提出了一种混合型文本识别器，使用具有多层抽象和长距离上下文的深度递归神经网络以及语言模型来验证深度神经网络的性能。在本文中，我们构造了一个多假设树结构，在不同分支的不同分割算法中，有不同分割算法的候选线段序列。对深度神经网络进行完美分段数据的训练，并对每个候选段进行测试，从而生成unicode序列。在验证步骤中，使用与语言模型的子字符串匹配对这些unicode序列进行验证，并且使用最佳首先搜索从树结构中找到替代假设的最佳可能组合。因此，使用语言模型的验证框架消除了错误的分割输出和过滤器识别错误。

##### URL
[https://arxiv.org/abs/1502.07540](https://arxiv.org/abs/1502.07540)

##### PDF
[https://arxiv.org/pdf/1502.07540](https://arxiv.org/pdf/1502.07540)

