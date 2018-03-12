---
layout: post
title: "Non-Autoregressive Neural Machine Translation"
date: 2018-03-09 03:37:52
categories: arXiv_CL
tags: arXiv_CL Knowledge Inference
author: Jiatao Gu, James Bradbury, Caiming Xiong, Victor O.K. Li, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Existing approaches to neural machine translation condition each output word on previously generated outputs. We introduce a model that avoids this autoregressive property and produces its outputs in parallel, allowing an order of magnitude lower latency during inference. Through knowledge distillation, the use of input token fertilities as a latent variable, and policy gradient fine-tuning, we achieve this at a cost of as little as 2.0 BLEU points relative to the autoregressive Transformer network used as a teacher. We demonstrate substantial cumulative improvements associated with each of the three aspects of our training strategy, and validate our approach on IWSLT 2016 English-German and two WMT language pairs. By sampling fertilities in parallel at inference time, our non-autoregressive model achieves near-state-of-the-art performance of 29.8 BLEU on WMT 2016 English-Romanian.

##### Abstract (translated by Google)
现有的神经机器翻译方法会对先前生成的输出中的每个输出字进行调整。我们引入了一个模型，避免了这种自回归属性并且产生并行输出，从而在推理过程中允许数量级较低的延迟。通过知识蒸馏，使用输入标记生育力作为潜在变量，以及政策梯度微调，我们以相对于用作教师的自动回归Transformer网络为代价，只需花费2.0 BLEU点即可实现此目标。我们展示了与我们培训战略三个方面相关的大量累积改进，并验证了我们在IWSLT 2016英语 - 德语和两个WMT语言对上的方法。通过在推断时间内并行采样肥料，我们的非自回归模型在WMT 2016英语 - 罗马尼亚语中达到了近29.8 BLEU的最新性能。

##### URL
[http://arxiv.org/abs/1711.02281](http://arxiv.org/abs/1711.02281)

##### PDF
[http://arxiv.org/pdf/1711.02281](http://arxiv.org/pdf/1711.02281)

