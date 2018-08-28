---
layout: post
title: "Why Self-Attention? A Targeted Evaluation of Neural Machine Translation Architectures"
date: 2018-08-27 17:51:27
categories: arXiv_CL
tags: arXiv_CL Attention CNN RNN
author: Gongbo Tang, Matthias Muller, Annette Rios, Rico Sennrich
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, non-recurrent architectures (convolutional, self-attentional) have outperformed RNNs in neural machine translation. CNNs and self-attentional networks can connect distant words via shorter network paths than RNNs, and it has been speculated that this improves their ability to model long-range dependencies. However, this theoretical argument has not been tested empirically, nor have alternative explanations for their strong performance been explored in-depth. We hypothesize that the strong performance of CNNs and self-attentional networks could also be due to their ability to extract semantic features from the source text, and we evaluate RNNs, CNNs and self-attention networks on two tasks: subject-verb agreement (where capturing long-range dependencies is required) and word sense disambiguation (where semantic feature extraction is required). Our experimental results show that: 1) self-attentional networks and CNNs do not outperform RNNs in modeling subject-verb agreement over long distances; 2) self-attentional networks perform distinctly better than RNNs and CNNs on word sense disambiguation.

##### Abstract (translated by Google)
最近，非经常性体系结构（卷积，自我注意）在神经机器翻译中的表现优于RNN。 CNN和自我关注网络可以通过比RNN更短的网络路径连接远端单词，并且据推测这可以提高他们对远程依赖性进行建模的能力。然而，这一理论论证尚未经过实证检验，也未对其强有力的表现进行深入探讨。我们假设CNN和自我关注网络的强大性能也可能是由于它们能够从源文本中提取语义特征，我们在两个任务上评估RNN，CNN和自我关注网络：主题 - 动词协议（其中）捕获远程依赖性是必需的）和词义消歧（需要语义特征提取）。我们的实验结果表明：1）自我注意网络和CNN在长距离建模主语 - 动词协议中的表现并不优于RNN; 2）自我关注网络在词义消歧方面表现明显优于RNN和CNN。

##### URL
[http://arxiv.org/abs/1808.08946](http://arxiv.org/abs/1808.08946)

##### PDF
[http://arxiv.org/pdf/1808.08946](http://arxiv.org/pdf/1808.08946)

