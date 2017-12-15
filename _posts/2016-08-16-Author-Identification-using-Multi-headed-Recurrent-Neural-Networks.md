---
layout: post
title: "Author Identification using Multi-headed Recurrent Neural Networks"
date: 2016-08-16 05:04:57
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Douglas Bagnall
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) are very good at modelling the flow of text, but typically need to be trained on a far larger corpus than is available for the PAN 2015 Author Identification task. This paper describes a novel approach where the output layer of a character-level RNN language model is split into several independent predictive sub-models, each representing an author, while the recurrent layer is shared by all. This allows the recurrent layer to model the language as a whole without over-fitting, while the outputs select aspects of the underlying model that reflect their author's style. The method proves competitive, ranking first in two of the four languages.

##### Abstract (translated by Google)
递归神经网络（RNN）非常适合对文本流进行建模，但通常需要在比PAN 2015 Author Identification任务更大的语料库上进行训练。本文描述了一种新颖的方法，其中字符级别的RNN语言模型的输出层被分割成几个独立的预测子模型，每个模型代表一个作者，而所有的共享层被共享。这允许递归层对整个语言进行建模而不会过度拟合，而输出则选择反映作者风格的底层模型的各个方面。该方法证明具有竞争力，在四种语言中的两种中排名第一。

##### URL
[https://arxiv.org/abs/1506.04891](https://arxiv.org/abs/1506.04891)

##### PDF
[https://arxiv.org/pdf/1506.04891](https://arxiv.org/pdf/1506.04891)

