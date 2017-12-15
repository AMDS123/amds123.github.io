---
layout: post
title: "Reading Scene Text in Deep Convolutional Sequences"
date: 2015-12-20 21:06:23
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN Recognition
author: Pan He, Weilin Huang, Yu Qiao, Chen Change Loy, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a Deep-Text Recurrent Network (DTRN) that regards scene text reading as a sequence labelling problem. We leverage recent advances of deep convolutional neural networks to generate an ordered high-level sequence from a whole word image, avoiding the difficult character segmentation problem. Then a deep recurrent model, building on long short-term memory (LSTM), is developed to robustly recognize the generated CNN sequences, departing from most existing approaches recognising each character independently. Our model has a number of appealing properties in comparison to existing scene text recognition methods: (i) It can recognise highly ambiguous words by leveraging meaningful context information, allowing it to work reliably without either pre- or post-processing; (ii) the deep CNN feature is robust to various image distortions; (iii) it retains the explicit order information in word image, which is essential to discriminate word strings; (iv) the model does not depend on pre-defined dictionary, and it can process unknown words and arbitrary strings. Codes for the DTRN will be available.

##### Abstract (translated by Google)
我们开发了一个深度文本循环网络（DTRN），将场景文本阅读视为序列标签问题。我们利用深层卷积神经网络的最新进展从整个单词图像中生成一个有序的高层次序列，避免了难以处理的字符分割问题。然后，建立在长期短期记忆（LSTM）基础上的深层循环模型被开发来强健地识别​​所产生的CNN序列，这与大多数独立识别每个字符的现有方法不同。与现有的场景文本识别方法相比，我们的模型具有许多吸引人的特性：（i）通过利用有意义的上下文信息可以识别高度模糊的单词，使其在没有预处理或后处理的情况下可靠地工作; （ii）深CNN特征对于各种图像失真是强健的; （iii）它在字图像中保留明确的订单信息，这对于区分字符串是必不可少的; （4）模型不依赖于预定义的字典，它可以处理未知的单词和任意的字符串。 DTRN的代码将可用。

##### URL
[https://arxiv.org/abs/1506.04395](https://arxiv.org/abs/1506.04395)

##### PDF
[https://arxiv.org/pdf/1506.04395](https://arxiv.org/pdf/1506.04395)

