---
layout: post
title: "Conditional generation of multi-modal data using constrained embedding space mapping"
date: 2017-07-26 00:51:04
categories: arXiv_CV
tags: arXiv_CV Embedding Optimization Inference Relation
author: Subhajit Chaudhury, Sakyasingha Dasgupta, Asim Munawar, Md. A. Salam Khan, Ryuki Tachibana
mathjax: true
---

* content
{:toc}

##### Abstract
We present a conditional generative model that maps low-dimensional embeddings of multiple modalities of data to a common latent space hence extracting semantic relationships between them. The embedding specific to a modality is first extracted and subsequently a constrained optimization procedure is performed to project the two embedding spaces to a common manifold. The individual embeddings are generated back from this common latent space. However, in order to enable independent conditional inference for separately extracting the corresponding embeddings from the common latent space representation, we deploy a proxy variable trick - wherein, the single shared latent space is replaced by the respective separate latent spaces of each modality. We design an objective function, such that, during training we can force these separate spaces to lie close to each other, by minimizing the distance between their probability distribution functions. Experimental results demonstrate that the learned joint model can generalize to learning concepts of double MNIST digits with additional attributes of colors,from both textual and speech input.

##### Abstract (translated by Google)
我们提出了一个条件生成模型，将多维数据模式的低维嵌入映射到一个普通的潜在空间，从而提取它们之间的语义关系。首先提取特定于模态的嵌入，随后执行约束优化过程以将两个嵌入空间投影到公共流形。个别嵌入是从这个普通的潜在空间产生的。然而，为了能够独立的条件推理从共同的潜在空间表示中分别提取对应的嵌入，我们部署代理变量技巧 - 其中，单个共享的潜在空间被每个模态的相应单独的潜在空间替换。我们设计一个目标函数，使得在训练过程中，我们可以迫使这些独立的空间彼此靠近，通过最小化他们的概率分布函数之间的距离。实验结果表明，学习的联合模型可以推广到双重MNIST数字的学习概念，从文本和语音输入的颜色附加属性。

##### URL
[https://arxiv.org/abs/1707.00860](https://arxiv.org/abs/1707.00860)

##### PDF
[https://arxiv.org/pdf/1707.00860](https://arxiv.org/pdf/1707.00860)

