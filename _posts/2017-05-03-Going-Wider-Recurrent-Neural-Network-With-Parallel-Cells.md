---
layout: post
title: "Going Wider: Recurrent Neural Network With Parallel Cells"
date: 2017-05-03 10:22:22
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Danhao Zhu, Si Shen, Xin-Yu Dai, Jiajun Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Network (RNN) has been widely applied for sequence modeling. In RNN, the hidden states at current step are full connected to those at previous step, thus the influence from less related features at previous step may potentially decrease model's learning ability. We propose a simple technique called parallel cells (PCs) to enhance the learning ability of Recurrent Neural Network (RNN). In each layer, we run multiple small RNN cells rather than one single large cell. In this paper, we evaluate PCs on 2 tasks. On language modeling task on PTB (Penn Tree Bank), our model outperforms state of art models by decreasing perplexity from 78.6 to 75.3. On Chinese-English translation task, our model increases BLEU score for 0.39 points than baseline model.

##### Abstract (translated by Google)
递归神经网络（RNN）已被广泛应用于序列建模。在RNN中，当前步的隐藏状态与前一步的隐藏状态完全连接，因此上一步较少相关特征的影响可能会降低模型的学习能力。我们提出了一种简单的技术叫做并行单元（PC）来提高递归神经网络（RNN）的学习能力。在每一层中，我们运行多个小型RNN小区，而不是一个大型小区。在本文中，我们评估PC上的2个任务。在PTB（Penn Tree Bank）的语言建模任务上，我们的模型通过将困惑从78.6降低到75.3，超越了艺术模型的状态。在汉英翻译任务中，我们的模型比基线模型增加了0.39分的BLEU分数。

##### URL
[https://arxiv.org/abs/1705.01346](https://arxiv.org/abs/1705.01346)

##### PDF
[https://arxiv.org/pdf/1705.01346](https://arxiv.org/pdf/1705.01346)

