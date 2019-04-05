---
layout: post
title: "DeCaFA: Deep Convolutional Cascade for Face Alignment In The Wild"
date: 2019-04-04 13:36:11
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN
author: Arnaud Dapogny, K&#xe9;vin Bailly, Matthieu Cord
mathjax: true
---

* content
{:toc}

##### Abstract
Face Alignment is an active computer vision domain, that consists in localizing a number of facial landmarks that vary across datasets. State-of-the-art face alignment methods either consist in end-to-end regression, or in refining the shape in a cascaded manner, starting from an initial guess. In this paper, we introduce DeCaFA, an end-to-end deep convolutional cascade architecture for face alignment. DeCaFA uses fully-convolutional stages to keep full spatial resolution throughout the cascade. Between each cascade stage, DeCaFA uses multiple chained transfer layers with spatial softmax to produce landmark-wise attention maps for each of several landmark alignment tasks. Weighted intermediate supervision, as well as efficient feature fusion between the stages allow to learn to progressively refine the attention maps in an end-to-end manner. We show experimentally that DeCaFA significantly outperforms existing approaches on 300W, CelebA and WFLW databases. In addition, we show that DeCaFA can learn fine alignment with reasonable accuracy from very few images using coarsely annotated data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02549](http://arxiv.org/abs/1904.02549)

##### PDF
[http://arxiv.org/pdf/1904.02549](http://arxiv.org/pdf/1904.02549)

