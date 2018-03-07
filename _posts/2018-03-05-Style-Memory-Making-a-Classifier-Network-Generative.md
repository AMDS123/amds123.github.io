---
layout: post
title: "Style Memory: Making a Classifier Network Generative"
date: 2018-03-05 19:50:52
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Rey Wiyatno, Jeff Orchard
mathjax: true
---

* content
{:toc}

##### Abstract
Deep networks have shown great performance in classification tasks. However, the parameters learned by the classifier networks usually discard stylistic information of the input, in favour of information strictly relevant to classification. We introduce a network that has the capacity to do both classification and reconstruction by adding a "style memory" to the output layer of the network. We also show how to train such a neural network as a deep multi-layer autoencoder, jointly minimizing both classification and reconstruction losses. The generative capacity of our network demonstrates that the combination of style-memory neurons with the classifier neurons yield good reconstructions of the inputs when the classification is correct. We further investigate the nature of the style memory, and how it relates to composing digits and letters. Finally, we propose that this architecture enables the bidirectional flow of information used in predictive coding, and that such bidirectional networks can help mitigate against being fooled by ambiguous or adversarial input.

##### Abstract (translated by Google)
深度网络在分类任务中表现出卓越的性能。然而，分类器网络学习到的参数通常会丢弃输入的文体信息，而偏向与分类严格相关的信息。我们引入了一个网络，通过在网络的输出层增加一个“样式内存”，可以进行分类和重建。我们还展示了如何训练如深层多层自动编码器这样的神经网络，共同最小化分类和重建损失。我们的网络的生成能力表明，风格记忆神经元与分类器神经元的组合在分类正确时可以很好地重构输入。我们进一步调查风格记忆的本质，以及它如何与编写数字和字母相关。最后，我们建议这种架构能够实现预测编码中使用的双向信息流，并且这种双向网络可以帮助减少被模糊或敌对输入所愚弄。

##### URL
[https://arxiv.org/abs/1803.01900](https://arxiv.org/abs/1803.01900)

##### PDF
[https://arxiv.org/pdf/1803.01900](https://arxiv.org/pdf/1803.01900)

