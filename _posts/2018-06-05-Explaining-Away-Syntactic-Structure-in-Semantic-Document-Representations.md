---
layout: post
title: "Explaining Away Syntactic Structure in Semantic Document Representations"
date: 2018-06-05 12:02:11
categories: arXiv_CL
tags: arXiv_CL Prediction
author: Erik Holmer, Andreas Marfurt
mathjax: true
---

* content
{:toc}

##### Abstract
Most generative document models act on bag-of-words input in an attempt to focus on the semantic content and thereby partially forego syntactic information. We argue that it is preferable to keep the original word order intact and explicitly account for the syntactic structure instead. We propose an extension to the Neural Variational Document Model (Miao et al., 2016) that does exactly that to separate local (syntactic) context from the global (semantic) representation of the document. Our model builds on the variational autoencoder framework to define a generative document model based on next-word prediction. We name our approach Sequence-Aware Variational Autoencoder since in contrast to its predecessor, it operates on the true input sequence. In a series of experiments we observe stronger topicality of the learned representations as well as increased robustness to syntactic noise in our training data.

##### Abstract (translated by Google)
大多数生成文档模型都是基于词袋输入来尝试着重于语义内容，从而部分放弃语法信息。我们认为，最好保持原始单词顺序不变，并明确说明句法结构。我们提出了对神经变分文档模型的扩展（Miao et al。，2016），它确实将局部（句法）上下文与文档的全局（语义）表示分开。我们的模型建立在变化的自编码器框架上，以基于下一个词预测来定义生成文档模型。我们将我们的方法命名为Sequence-Aware Variational Autoencoder，因为与其前身相反，它使用真正的输入序列。在一系列实验中，我们观察到了学习表示的更强的话题性以及增强了训练数据中句法噪声的鲁棒性。

##### URL
[http://arxiv.org/abs/1806.01620](http://arxiv.org/abs/1806.01620)

##### PDF
[http://arxiv.org/pdf/1806.01620](http://arxiv.org/pdf/1806.01620)

