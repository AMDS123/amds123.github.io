---
layout: post
title: "Toward domain-invariant speech recognition via large scale training"
date: 2018-08-16 00:24:49
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Arun Narayanan, Ananya Misra, Khe Chai Sim, Golan Pundak, Anshuman Tripathi, Mohamed Elfeky, Parisa Haghani, Trevor Strohman, Michiel Bacchiani
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art automatic speech recognition systems are trained to work in specific `domains', defined based on factors like application, sampling rate and codec. When such recognizers are used in conditions that do not match the training domain, performance significantly drops. This work explores the idea of building a single domain-invariant model for varied use-cases by combining large scale training data from multiple application domains. Our final system is trained using 162,000 hours of speech. Additionally, each utterance is artificially distorted during training to simulate effects like background noise, codec distortion, and sampling rates. Our results show that, even at such a scale, a model thus trained works almost as well as those fine-tuned to specific subsets: A single model can be robust to multiple application domains, and variations like codecs and noise. More importantly, such models generalize better to unseen conditions and allow for rapid adaptation -- we show that by using as little as 10 hours of data from a new domain, an adapted domain-invariant model can match performance of a domain-specific model trained from scratch using 70 times as much data. We also highlight some of the limitations of such models and areas that need addressing in future work.

##### Abstract (translated by Google)
当前最先进的自动语音识别系统经过训练，可以在特定的“域”中工作，这些域根据应用，采样率和编解码器等因素进行定义。当此类识别器用于与训练域不匹配的条件时，性能会显着下降。这项工作探讨了通过组合来自多个应用程序域的大规模训练数据，为各种用例构建单个域不变模型的想法。我们的最终系统使用162,000小时的演讲进行训练。另外，在训练期间，每个话语都被人为地扭曲，以模拟诸如背景噪声，编解码器失真和采样率之类的效果。我们的结果表明，即使在这样的规模下，这样训练的模型几乎与那些针对特定子集进行微调的模型一样好：单个模型可以对多个应用领域以及编解码器和噪声等变体具有鲁棒性。更重要的是，这些模型更好地概括为看不见的条件并允许快速适应 - 我们通过使用来自新域的少至10小时的数据表明，经过调整的域不变模型可以匹配特定于域的模型的性能从头开始使用70倍的数据。我们还强调了此类模型的一些局限性以及需要在未来工作中解决的领域。

##### URL
[http://arxiv.org/abs/1808.05312](http://arxiv.org/abs/1808.05312)

##### PDF
[http://arxiv.org/pdf/1808.05312](http://arxiv.org/pdf/1808.05312)

