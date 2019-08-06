---
layout: post
title: "Image to Video Domain Adaptation Using Web Supervision"
date: 2019-08-05 02:50:59
categories: arXiv_CV
tags: arXiv_CV Attention Optimization
author: Andrew Kae, Yale Song
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep neural networks typically requires large amounts of labeled data which may be scarce or expensive to obtain for a particular target domain. As an alternative, we can leverage webly-supervised data (i.e. results from a public search engine) which are relatively plentiful but may contain noisy results. In this work, we propose a novel two-stage approach to learn a video classifier using webly-supervised data. We argue that learning appearance features and then temporal features sequentially, rather than simultaneously, is an easier optimization for this task. We show this by first learning an image model from web images, which is used to initialize and train a video model. Our model applies domain adaptation to account for potential domain shift present between the source domain (webly-supervised data) and target domain and also accounts for noise by adding a novel attention component. We report results competitive with state-of-the-art for webly-supervised approaches on UCF-101 (while simplifying the training process) and also evaluate on Kinetics for comparison.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01449](http://arxiv.org/abs/1908.01449)

##### PDF
[http://arxiv.org/pdf/1908.01449](http://arxiv.org/pdf/1908.01449)

