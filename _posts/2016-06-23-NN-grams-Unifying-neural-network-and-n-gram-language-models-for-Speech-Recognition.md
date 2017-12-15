---
layout: post
title: "NN-grams: Unifying neural network and n-gram language models for Speech Recognition"
date: 2016-06-23 20:37:06
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Classification Language_Model Recognition
author: Babak Damavandi, Shankar Kumar, Noam Shazeer, Antoine Bruguier
mathjax: true
---

* content
{:toc}

##### Abstract
We present NN-grams, a novel, hybrid language model integrating n-grams and neural networks (NN) for speech recognition. The model takes as input both word histories as well as n-gram counts. Thus, it combines the memorization capacity and scalability of an n-gram model with the generalization ability of neural networks. We report experiments where the model is trained on 26B words. NN-grams are efficient at run-time since they do not include an output soft-max layer. The model is trained using noise contrastive estimation (NCE), an approach that transforms the estimation problem of neural networks into one of binary classification between data samples and noise samples. We present results with noise samples derived from either an n-gram distribution or from speech recognition lattices. NN-grams outperforms an n-gram model on an Italian speech recognition dictation task.

##### Abstract (translated by Google)
我们提出NN-grams，一种新型的混合语言模型，将n-gram和神经网络（NN）结合起来用于语音识别。该模型将词历史和n-gram计数作为输入。因此，它将n-gram模型的记忆能力和可伸缩性与神经网络的泛化能力相结合。我们报告模型在26B字训练的实验。 NN-grams在运行时效率很高，因为它们不包含输出soft-max层。该模型使用噪声对比估计（NCE）进行训练，该方法将神经网络的估计问题转换为数据样本与噪声样本之间的二分类之一。我们用来自n-gram分布或者来自语音识别格的噪声样本给出结果。 NN-gram在意大利语言识别听写任务上胜过n-gram模型。

##### URL
[https://arxiv.org/abs/1606.07470](https://arxiv.org/abs/1606.07470)

##### PDF
[https://arxiv.org/pdf/1606.07470](https://arxiv.org/pdf/1606.07470)

