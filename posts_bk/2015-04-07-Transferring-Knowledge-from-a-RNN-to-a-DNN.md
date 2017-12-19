---
layout: post
title: "Transferring Knowledge from a RNN to a DNN"
date: 2015-04-07 06:15:44
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition RNN Recognition
author: William Chan, Nan Rosemary Ke, Ian Lane
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Network (DNN) acoustic models have yielded many state-of-the-art results in Automatic Speech Recognition (ASR) tasks. More recently, Recurrent Neural Network (RNN) models have been shown to outperform DNNs counterparts. However, state-of-the-art DNN and RNN models tend to be impractical to deploy on embedded systems with limited computational capacity. Traditionally, the approach for embedded platforms is to either train a small DNN directly, or to train a small DNN that learns the output distribution of a large DNN. In this paper, we utilize a state-of-the-art RNN to transfer knowledge to small DNN. We use the RNN model to generate soft alignments and minimize the Kullback-Leibler divergence against the small DNN. The small DNN trained on the soft RNN alignments achieved a 3.93 WER on the Wall Street Journal (WSJ) eval92 task compared to a baseline 4.54 WER or more than 13% relative improvement.

##### Abstract (translated by Google)
深度神经网络（DNN）声学模型在自动语音识别（ASR）任务中已经产生了许多最新的结果。最近，递归神经网络（RNN）模型已经被证明胜过DNNs的同行。然而，最先进的DNN和RNN模型在计算能力有限的嵌入式系统上往往是不切实际的。传统上，嵌入式平台的方法是直接训练小DNN，或者训练小DNN，学习大DNN的输出分布。在本文中，我们利用最先进的RNN将知识转移到小DNN。我们使用RNN模型来产生软比对，并将对小DNN的Kullback-Leibler背离最小化。训练有素RNN队列的小DNN在“华尔街日报”（WSJ）eval92任务上达到3.93 WER，而基线4.54 WER或相对改善13％以上。

##### URL
[https://arxiv.org/abs/1504.01483](https://arxiv.org/abs/1504.01483)

##### PDF
[https://arxiv.org/pdf/1504.01483](https://arxiv.org/pdf/1504.01483)

