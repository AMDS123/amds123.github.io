---
layout: post
title: "Yeah, Right, Uh-Huh: A Deep Learning Backchannel Predictor"
date: 2017-06-02 17:05:26
categories: arXiv_CL
tags: arXiv_CL RNN Deep_Learning Language_Model
author: Robin Ruede, Markus Müller, Sebastian Stüker, Alex Waibel
mathjax: true
---

* content
{:toc}

##### Abstract
Using supporting backchannel (BC) cues can make human-computer interaction more social. BCs provide a feedback from the listener to the speaker indicating to the speaker that he is still listened to. BCs can be expressed in different ways, depending on the modality of the interaction, for example as gestures or acoustic cues. In this work, we only considered acoustic cues. We are proposing an approach towards detecting BC opportunities based on acoustic input features like power and pitch. While other works in the field rely on the use of a hand-written rule set or specialized features, we made use of artificial neural networks. They are capable of deriving higher order features from input features themselves. In our setup, we first used a fully connected feed-forward network to establish an updated baseline in comparison to our previously proposed setup. We also extended this setup by the use of Long Short-Term Memory (LSTM) networks which have shown to outperform feed-forward based setups on various tasks. Our best system achieved an F1-Score of 0.37 using power and pitch features. Adding linguistic information using word2vec, the score increased to 0.39.

##### Abstract (translated by Google)
使用支持反向通道（BC）的线索可以使人机交互更加社交化。不列颠哥伦比亚省提供了从聆听者到发言者的反馈，向发言者指出他仍在聆听。 BC可以以不同的方式表达，取决于交互的形式，例如作为手势或声音提示。在这项工作中，我们只考虑声学提示。我们提出一种基于功率和音调等声学输入特征来检测BC机会的方法。虽然在这个领域的其他作品依赖于手写规则集或专业特征的使用，我们使用人工神经网络。他们能够从输入特征本身获得更高阶的特征。在我们的设置中，我们首先使用完全连接的前馈网络来建立与我们之前提出的设置相比更新的基线。我们还通过使用长期短期记忆（LSTM）网络扩展了这种设置，这些网络已经证明在各种任务上优于基于前馈的设置。我们最好的系统使用功率和音高功能获得了0.37的F1分数。使用word2vec添加语言信息，得分增加到0.39。

##### URL
[https://arxiv.org/abs/1706.01340](https://arxiv.org/abs/1706.01340)

##### PDF
[https://arxiv.org/pdf/1706.01340](https://arxiv.org/pdf/1706.01340)

