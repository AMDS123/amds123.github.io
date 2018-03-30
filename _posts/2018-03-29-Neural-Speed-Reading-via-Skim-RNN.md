---
layout: post
title: "Neural Speed Reading via Skim-RNN"
date: 2018-03-29 03:25:36
categories: arXiv_CL
tags: arXiv_CL Face Inference RNN
author: Minjoon Seo, Sewon Min, Ali Farhadi, Hannaneh Hajishirzi
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by the principles of speed reading, we introduce Skim-RNN, a recurrent neural network (RNN) that dynamically decides to update only a small fraction of the hidden state for relatively unimportant input tokens. Skim-RNN gives computational advantage over an RNN that always updates the entire hidden state. Skim-RNN uses the same input and output interfaces as a standard RNN and can be easily used instead of RNNs in existing models. In our experiments, we show that Skim-RNN can achieve significantly reduced computational cost without losing accuracy compared to standard RNNs across five different natural language tasks. In addition, we demonstrate that the trade-off between accuracy and speed of Skim-RNN can be dynamically controlled during inference time in a stable manner. Our analysis also shows that Skim-RNN running on a single CPU offers lower latency compared to standard RNNs on GPUs.

##### Abstract (translated by Google)
受速度阅读原理的启发，我们引入了Skim-RNN，一种递归神经网络（RNN），它动态地决定只更新相对不重要输入令牌的一小部分隐藏状态。 Skim-RNN比RNN提供了计算优势，它总是更新整个隐藏状态。 Skim-RNN使用与标准RNN相同的输入和输出接口，可以在现有模型中轻松使用，而非RNN。在我们的实验中，我们展示Skim-RNN可以在不损失准确性的情况下，与五种不同的自然语言任务中的标准RNN相比，显着降低计算成本。另外，我们证明Skim-RNN的精度和速度之间的平衡可以在推理时间内以稳定的方式动态控制。我们的分析还表明，在单个CPU上运行的Skim-RNN与在GPU上的标准RNN相比提供了更低的延迟。

##### URL
[http://arxiv.org/abs/1711.02085](http://arxiv.org/abs/1711.02085)

##### PDF
[http://arxiv.org/pdf/1711.02085](http://arxiv.org/pdf/1711.02085)

