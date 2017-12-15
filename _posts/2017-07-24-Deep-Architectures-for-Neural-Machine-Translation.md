---
layout: post
title: "Deep Architectures for Neural Machine Translation"
date: 2017-07-24 16:19:59
categories: arXiv_CL
tags: arXiv_CL Attention Inference RNN
author: Antonio Valerio Miceli Barone, Jindřich Helcl, Rico Sennrich, Barry Haddow, Alexandra Birch
mathjax: true
---

* content
{:toc}

##### Abstract
It has been shown that increasing model depth improves the quality of neural machine translation. However, different architectural variants to increase model depth have been proposed, and so far, there has been no thorough comparative study. In this work, we describe and evaluate several existing approaches to introduce depth in neural machine translation. Additionally, we explore novel architectural variants, including deep transition RNNs, and we vary how attention is used in the deep decoder. We introduce a novel "BiDeep" RNN architecture that combines deep transition RNNs and stacked RNNs. Our evaluation is carried out on the English to German WMT news translation dataset, using a single-GPU machine for both training and inference. We find that several of our proposed architectures improve upon existing approaches in terms of speed and translation quality. We obtain best improvements with a BiDeep RNN of combined depth 8, obtaining an average improvement of 1.5 BLEU over a strong shallow baseline. We release our code for ease of adoption.

##### Abstract (translated by Google)
已经表明，增加模型深度可以提高神经机器翻译的质量。然而，已经提出了不同的增加模型深度的架构变体，到目前为止还没有进行彻底的比较研究。在这项工作中，我们描述和评估几种现有的方法来引入神经机器翻译的深度。此外，我们探索新的架构变体，包括深度转换RNN，我们改变深度解码器的注意力。我们介绍一种结合了深度转换RNN和堆叠RNN的新颖的“BiDeep”RNN架构。我们的评估是在英语到德语的WMT新闻翻译数据集上进行的，使用单GPU机进行培训和推理。我们发现，我们提出的几个架构在速度和翻译质量方面都改进了现有的方法。我们使用深度为8的BiDeep RNN获得了最佳的改进，在较强的浅基线上获得了1.5 BLEU的平均改进。我们发布我们的代码以便于采用。

##### URL
[https://arxiv.org/abs/1707.07631](https://arxiv.org/abs/1707.07631)

##### PDF
[https://arxiv.org/pdf/1707.07631](https://arxiv.org/pdf/1707.07631)

