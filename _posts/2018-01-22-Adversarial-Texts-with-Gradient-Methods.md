---
layout: post
title: "Adversarial Texts with Gradient Methods"
date: 2018-01-22 16:19:52
categories: arXiv_CL
tags: arXiv_CL Review Adversarial Embedding
author: Zhitao Gong, Wenlu Wang, Bo Li, Dawn Song, Wei-Shinn Ku
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial samples for images have been extensively studied in the literature. Among many of the attacking methods, gradient-based methods are both effective and easy to compute. In this work, we propose a framework to adapt the gradient attacking methods on images to text domain. The main difficulties for generating adversarial texts with gradient methods are i) the input space is discrete, which makes it difficult to accumulate small noise directly in the inputs, and ii) the measurement of the quality of the adversarial texts is difficult. We tackle the first problem by searching for adversarials in the embedding space and then reconstruct the adversarial texts via nearest neighbor search. For the latter problem, we employ the Word Mover's Distance (WMD) to quantify the quality of adversarial texts. Through extensive experiments on three datasets, IMDB movie reviews, Reuters-2 and Reuters-5 newswires, we show that our framework can leverage gradient attacking methods to generate very high-quality adversarial texts that are only a few words different from the original texts. There are many cases where we can change one word to alter the label of the whole piece of text. We successfully incorporate FGM and DeepFool into our framework. In addition, we empirically show that WMD is closely related to the quality of adversarial texts.

##### Abstract (translated by Google)
文献中广泛研究了图像的敌对样本。在许多攻击方法中，基于梯度的方法既有效又容易计算。在这项工作中，我们提出了一个框架，适应梯度攻击方法的图像到文本域。使用梯度方法产生敌对文本的主要困难是：i）输入空间是离散的，这使得难以直接在输入中累积小噪声，以及ii）对抗文本的质量的测量是困难的。我们通过在嵌入空间中搜索敌手来解决第一个问题，然后通过最近的邻居搜索重构敌对文本。对于后一个问题，我们采用了漫游者距离（WMD）量化对抗性文本的质量。通过对三个数据集（IMDB电影评论，路透社2和路透社5）的广泛的实验，我们发现我们的框架可以利用梯度攻击方法来生成非常高质量的对抗文本，这些文本只是与原始文本不同的几个字。有很多情况下，我们可以改变一个单词来改变整个文本的标签。我们成功地将FGM和DeepFool整合到我们的框架中。另外，我们凭经验证明，大规模杀伤性武器与敌对文本的质量密切相关。

##### URL
[https://arxiv.org/abs/1801.07175](https://arxiv.org/abs/1801.07175)

##### PDF
[https://arxiv.org/pdf/1801.07175](https://arxiv.org/pdf/1801.07175)

