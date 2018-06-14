---
layout: post
title: "Unsupervised Adaptation with Interpretable Disentangled Representations for Distant Conversational Speech Recognition"
date: 2018-06-13 07:14:15
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Wei-Ning Hsu, Hao Tang, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
The current trend in automatic speech recognition is to leverage large amounts of labeled data to train supervised neural network models. Unfortunately, obtaining data for a wide range of domains to train robust models can be costly. However, it is relatively inexpensive to collect large amounts of unlabeled data from domains that we want the models to generalize to. In this paper, we propose a novel unsupervised adaptation method that learns to synthesize labeled data for the target domain from unlabeled in-domain data and labeled out-of-domain data. We first learn without supervision an interpretable latent representation of speech that encodes linguistic and nuisance factors (e.g., speaker and channel) using different latent variables. To transform a labeled out-of-domain utterance without altering its transcript, we transform the latent nuisance variables while maintaining the linguistic variables. To demonstrate our approach, we focus on a channel mismatch setting, where the domain of interest is distant conversational speech, and labels are only available for close-talking speech. Our proposed method is evaluated on the AMI dataset, outperforming all baselines and bridging the gap between unadapted and in-domain models by over 77% without using any parallel data.

##### Abstract (translated by Google)
目前自动语音识别的趋势是利用大量的标记数据来训练监督神经网络模型。不幸的是，获得广泛领域的数据来训练强大的模型可能代价高昂。但是，从我们希望模型推广到的域收集大量未标记的数据是相对便宜的。在本文中，我们提出了一种新的无监督自适应方法，该方法学习从未标记的域内数据合成目标域的标记数据并标记出域外数据。我们首先在没有监督的情况下学习使用不同的潜变量来编码语言和滋扰因素（例如说话者和频道）的可解释的言语潜在表示。为了在不改变其成绩单的情况下转换标记的域外话语，我们在保持语言变量的同时转化潜在的有害变量。为了演示我们的方法，我们专注于频道不匹配设置，其中感兴趣的领域是远距离对话式语音，并且标签仅可用于近距离通话语音。我们提出的方法在AMI数据集上进行评估，优于所有基线，并且在不使用任何并行数据的情况下弥合了不适应和适应性模型之间的差距超过77％。

##### URL
[https://arxiv.org/abs/1806.04872](https://arxiv.org/abs/1806.04872)

##### PDF
[https://arxiv.org/pdf/1806.04872](https://arxiv.org/pdf/1806.04872)

