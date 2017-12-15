---
layout: post
title: "Smoothing parameter estimation framework for IBM word alignment models"
date: 2016-04-27 04:01:48
categories: arXiv_SD
tags: arXiv_SD Sparse Language_Model
author: Vuong Van Bui, Cuong Anh Le
mathjax: true
---

* content
{:toc}

##### Abstract
IBM models are very important word alignment models in Machine Translation. Following the Maximum Likelihood Estimation principle to estimate their parameters, the models will easily overfit the training data when the data are sparse. While smoothing is a very popular solution in Language Model, there still lacks studies on smoothing for word alignment. In this paper, we propose a framework which generalizes the notable work Moore [2004] of applying additive smoothing to word alignment models. The framework allows developers to customize the smoothing amount for each pair of word. The added amount will be scaled appropriately by a common factor which reflects how much the framework trusts the adding strategy according to the performance on data. We also carefully examine various performance criteria and propose a smoothened version of the error count, which generally gives the best result.

##### Abstract (translated by Google)
IBM模型在机器翻译中是非常重要的词对齐模型。遵循最大似然估计原理来估计它们的参数，当数据稀疏时，模型将容易地过度训练数据。虽然平滑是语言模型中非常流行的解决方案，但仍然缺乏平滑字对齐的研究。在本文中，我们提出了一个框架，推广了在文字对齐模型中应用加法平滑的着名作品Moore [2004]。该框架允许开发人员自定义每对词的平滑量。增加的数量将根据一个共同的因素进行适当的缩放，该因子反映了框架根据数据性能信任增加策略的程度。我们还仔细检查了各种性能标准，并提出了错误计数的平滑版本，通常会给出最好的结果。

##### URL
[https://arxiv.org/abs/1601.03650](https://arxiv.org/abs/1601.03650)

##### PDF
[https://arxiv.org/pdf/1601.03650](https://arxiv.org/pdf/1601.03650)

