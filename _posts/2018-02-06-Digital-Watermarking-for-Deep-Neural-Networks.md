---
layout: post
title: "Digital Watermarking for Deep Neural Networks"
date: 2018-02-06 05:32:36
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Yuki Nagai, Yusuke Uchida, Shigeyuki Sakazawa, Shin&#x27;ichi Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep neural networks have made tremendous progress in the area of multimedia representation, training neural models requires a large amount of data and time. It is well-known that utilizing trained models as initial weights often achieves lower training error than neural networks that are not pre-trained. A fine-tuning step helps to reduce both the computational cost and improve performance. Therefore, sharing trained models has been very important for the rapid progress of research and development. In addition, trained models could be important assets for the owner(s) who trained them, hence we regard trained models as intellectual property. In this paper, we propose a digital watermarking technology for ownership authorization of deep neural networks. First, we formulate a new problem: embedding watermarks into deep neural networks. We also define requirements, embedding situations, and attack types on watermarking in deep neural networks. Second, we propose a general framework for embedding a watermark in model parameters, using a parameter regularizer. Our approach does not impair the performance of networks into which a watermark is placed because the watermark is embedded while training the host network. Finally, we perform comprehensive experiments to reveal the potential of watermarking deep neural networks as the basis of this new research effort. We show that our framework can embed a watermark during the training of a deep neural network from scratch, and during fine-tuning and distilling, without impairing its performance. The embedded watermark does not disappear even after fine-tuning or parameter pruning; the watermark remains complete even after 65% of parameters are pruned.

##### Abstract (translated by Google)
尽管深度神经网络在多媒体表示领域已经取得了巨大的进步，但训练神经模型需要大量的数据和时间。众所周知，利用训练过的模型作为初始权重通常比没有预先训练的神经网络获得更低的训练误差。微调步骤有助于降低计算成本并提高性能。因此，共享训练模型对研发的快速发展至关重要。另外，训练好的模型对于训练它们的所有者来说可能是重要的资产，因此我们将训练好的模型视为知识产权。本文提出了一种深度神经网络所有权授权的数字水印技术。首先，我们制定一个新的问题：将水印嵌入深度神经网络。我们还定义了深度神经网络中的需求，嵌入情况和攻击类型。其次，我们提出了一个使用参数正则化器在模型参数中嵌入水印的通用框架。我们的方法不会损害放置水印的网络的性能，因为在训练主机网络的同时嵌入了水印。最后，我们进行了全面的实验，揭示了深度神经网络水印的潜力作为这个新的研究工作的基础。我们表明，我们的框架可以在从头开始的深度神经网络训练过程中嵌入水印，并且在微调和蒸馏过程中不会影响其性能。嵌入的水印即使经过微调或参数修剪也不会消失;即使修剪了65％的参数，水印仍然保持完整。

##### URL
[http://arxiv.org/abs/1802.02601](http://arxiv.org/abs/1802.02601)

##### PDF
[http://arxiv.org/pdf/1802.02601](http://arxiv.org/pdf/1802.02601)

