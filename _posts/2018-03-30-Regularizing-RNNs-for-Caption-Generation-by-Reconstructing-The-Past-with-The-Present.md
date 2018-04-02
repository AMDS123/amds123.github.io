---
layout: post
title: "Regularizing RNNs for Caption Generation by Reconstructing The Past with The Present"
date: 2018-03-30 13:15:56
categories: arXiv_AI
tags: arXiv_AI Image_Caption Caption Inference RNN
author: Xinpeng Chen, Lin Ma, Wenhao Jiang, Jian Yao, Wei Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, caption generation with an encoder-decoder framework has been extensively studied and applied in different domains, such as image captioning, code captioning, and so on. In this paper, we propose a novel architecture, namely Auto-Reconstructor Network (ARNet), which, coupling with the conventional encoder-decoder framework, works in an end-to-end fashion to generate captions. ARNet aims at reconstructing the previous hidden state with the present one, besides behaving as the input-dependent transition operator. Therefore, ARNet encourages the current hidden state to embed more information from the previous one, which can help regularize the transition dynamics of recurrent neural networks (RNNs). Extensive experimental results show that our proposed ARNet boosts the performance over the existing encoder-decoder models on both image captioning and source code captioning tasks. Additionally, ARNet remarkably reduces the discrepancy between training and inference processes for caption generation. Furthermore, the performance on permuted sequential MNIST demonstrates that ARNet can effectively regularize RNN, especially on modeling long-term dependencies. Our code is available at: this https URL

##### Abstract (translated by Google)
最近，带有编码器 - 解码器框架的字幕生成已被广泛研究并应用于不同的领域，例如图像字幕，代码字幕等。在本文中，我们提出了一种新颖的架构，即Auto-Reconstructor Network（ARNet），它与传统的编码器 - 解码器框架耦合，以端到端的方式工作来生成字幕。除了像输入相关的转换算子那样行之外，ARNet的目的是重建前一个隐藏状态。因此，ARNet鼓励当前的隐藏状态嵌入来自前一个隐藏状态的更多信息，这可以帮助规则化递归神经网络（RNN）的转换动态。大量的实验结果表明，我们提出的ARNet在图像字幕和源代码字幕任务上提高了现有编码器 - 解码器模型的性能。此外，ARNet显着减少了字幕生成的训练和推理过程之间的差异。此外，置换顺序MNIST上的性能表明，ARNet可以有效地规范RNN，尤其是建模长期依赖性。我们的代码位于：https网址

##### URL
[https://arxiv.org/abs/1803.11439](https://arxiv.org/abs/1803.11439)

##### PDF
[https://arxiv.org/pdf/1803.11439](https://arxiv.org/pdf/1803.11439)

