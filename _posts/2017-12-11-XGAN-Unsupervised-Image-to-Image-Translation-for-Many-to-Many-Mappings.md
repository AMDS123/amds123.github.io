---
layout: post
title: "XGAN: Unsupervised Image-to-Image Translation for Many-to-Many Mappings"
date: 2017-12-11 00:09:05
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Style_Transfer Embedding
author: Am&#xe9;lie Royer, Konstantinos Bousmalis, Stephan Gouws, Fred Bertsch, Inbar Mosseri, Forrester Cole, Kevin Murphy
mathjax: true
---

* content
{:toc}

##### Abstract
Style transfer usually refers to the task of applying color and texture information from a specific style image to a given content image while preserving the structure of the latter. Here we tackle the more generic problem of semantic style transfer: given two unpaired collections of images, we aim to learn a mapping between the corpus-level style of each collection, while preserving semantic content shared across the two domains. We introduce XGAN ("Cross-GAN"), a dual adversarial autoencoder, which captures a shared representation of the common domain semantic content in an unsupervised way, while jointly learning the domain-to-domain image translations in both directions. We exploit ideas from the domain adaptation literature and define a semantic consistency loss which encourages the model to preserve semantics in the learned embedding space. We report promising qualitative results for the task of face-to-cartoon translation. The cartoon dataset we collected for this purpose is in the process of being released as a new benchmark for semantic style transfer.

##### Abstract (translated by Google)
样式转换通常指的是将颜色和纹理信息从特定样式图像应用到给定内容图像的任务，同时保留后者的结构。在这里，我们解决了语义风格转换的更一般的问题：给定两个不成对的图像集合，我们的目标是学习每个集合的语料库级风格之间的映射，同时保留两个域之间共享的语义内容。我们引入了XGAN（“Cross-GAN”），一种双向对抗自编码器，它以无监督的方式捕获共同领域语义内容的共享表示，同时在两个方向联合学习领域到图像的翻译。我们利用领域适应性文献中的想法，定义语义一致性损失，鼓励模型在学习的嵌入空间中保留语义。我们报告面向卡通翻译任务有希望的定性结果。我们为此收集的卡通数据集正在被发布，作为语义风格转换的新基准。

##### URL
[http://arxiv.org/abs/1711.05139](http://arxiv.org/abs/1711.05139)

##### PDF
[http://arxiv.org/pdf/1711.05139](http://arxiv.org/pdf/1711.05139)

