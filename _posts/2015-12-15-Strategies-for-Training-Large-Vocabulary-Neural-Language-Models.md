---
layout: post
title: "Strategies for Training Large Vocabulary Neural Language Models"
date: 2015-12-15 19:29:01
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Language_Model Recognition
author: Welin Chen, David Grangier, Michael Auli
mathjax: true
---

* content
{:toc}

##### Abstract
Training neural network language models over large vocabularies is still computationally very costly compared to count-based models such as Kneser-Ney. At the same time, neural language models are gaining popularity for many applications such as speech recognition and machine translation whose success depends on scalability. We present a systematic comparison of strategies to represent and train large vocabularies, including softmax, hierarchical softmax, target sampling, noise contrastive estimation and self normalization. We further extend self normalization to be a proper estimator of likelihood and introduce an efficient variant of softmax. We evaluate each method on three popular benchmarks, examining performance on rare words, the speed/accuracy trade-off and complementarity to Kneser-Ney.

##### Abstract (translated by Google)
与基于计数的模型（如Kneser-Ney）相比，训练大型词汇表上的神经网络语言模型在计算上仍然非常昂贵。同时，神经语言模型越来越受到许多应用的欢迎，如语音识别和机器翻译，其成功取决于可伸缩性。我们提出了一个系统的比较策略来表示和训练大词汇表，包括softmax，层次softmax，目标抽样，噪声对比估计和自我规范化。我们进一步将自我归一化扩展为可能性的恰当估计，并引入softmax的高效变体。我们在三个流行的基准测试中评估每种方法，检查罕见词汇的表现，速度/准确性和Kneser-Ney的互补性。

##### URL
[https://arxiv.org/abs/1512.04906](https://arxiv.org/abs/1512.04906)

##### PDF
[https://arxiv.org/pdf/1512.04906](https://arxiv.org/pdf/1512.04906)

