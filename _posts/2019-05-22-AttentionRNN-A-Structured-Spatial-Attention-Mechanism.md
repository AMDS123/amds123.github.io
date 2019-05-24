---
layout: post
title: "AttentionRNN: A Structured Spatial Attention Mechanism"
date: 2019-05-22 23:13:05
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN Quantitative Recognition
author: Siddhesh Khandelwal, Leonid Sigal
mathjax: true
---

* content
{:toc}

##### Abstract
Visual attention mechanisms have proven to be integrally important constituent components of many modern deep neural architectures. They provide an efficient and effective way to utilize visual information selectively, which has shown to be especially valuable in multi-modal learning tasks. However, all prior attention frameworks lack the ability to explicitly model structural dependencies among attention variables, making it difficult to predict consistent attention masks. In this paper we develop a novel structured spatial attention mechanism which is end-to-end trainable and can be integrated with any feed-forward convolutional neural network. This proposed AttentionRNN layer explicitly enforces structure over the spatial attention variables by sequentially predicting attention values in the spatial mask in a bi-directional raster-scan and inverse raster-scan order. As a result, each attention value depends not only on local image or contextual information, but also on the previously predicted attention values. Our experiments show consistent quantitative and qualitative improvements on a variety of recognition tasks and datasets; including image categorization, question answering and image generation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09400](http://arxiv.org/abs/1905.09400)

##### PDF
[http://arxiv.org/pdf/1905.09400](http://arxiv.org/pdf/1905.09400)

