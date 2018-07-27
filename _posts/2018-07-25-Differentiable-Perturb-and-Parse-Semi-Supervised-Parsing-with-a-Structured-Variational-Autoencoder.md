---
layout: post
title: "Differentiable Perturb-and-Parse: Semi-Supervised Parsing with a Structured Variational Autoencoder"
date: 2018-07-25 21:42:55
categories: arXiv_CL
tags: arXiv_CL Embedding Inference
author: Caio Corro, Ivan Titov
mathjax: true
---

* content
{:toc}

##### Abstract
Human annotation for syntactic parsing is expensive, and large resources are available only for a fraction of languages. A question we ask is whether one can leverage abundant unlabeled texts to improve syntactic parsers, beyond just using the texts to obtain more generalisable lexical features (i.e. beyond word embeddings). To this end, we propose a novel latent-variable generative model for semi-supervised syntactic dependency parsing. As exact inference is intractable, we introduce a differentiable relaxation to obtain approximate samples and compute gradients with respect to the parser parameters. Our method (Differentiable Perturb-and-Parse) relies on differentiable dynamic programming over stochastically perturbed edge scores. We demonstrate effectiveness of our approach with experiments on English, French and Swedish.

##### Abstract (translated by Google)
语法分析的人工注释是昂贵的，并且大量资源仅适用于一小部分语言。我们要问的一个问题是，是否可以利用丰富的未标记文本来改进语法分析器，而不仅仅是使用文本来获得更通用的词法特征（即除了嵌入词之外）。为此，我们提出了一种新的潜在变量生成模型，用于半监督句法依赖解析。由于精确推断是难以处理的，我们引入可微分松弛来获得近似样本并计算与解析器参数相关的梯度。我们的方法（Differentiable Perturb-and-Parse）依赖于随机扰动边缘分数的可微动态规划。我们通过英语，法语和瑞典语实验证明了我们的方法的有效性。

##### URL
[http://arxiv.org/abs/1807.09875](http://arxiv.org/abs/1807.09875)

##### PDF
[http://arxiv.org/pdf/1807.09875](http://arxiv.org/pdf/1807.09875)

