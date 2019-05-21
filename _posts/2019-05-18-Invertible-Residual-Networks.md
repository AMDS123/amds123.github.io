---
layout: post
title: "Invertible Residual Networks"
date: 2019-05-18 18:19:33
categories: arXiv_AI
tags: arXiv_AI Classification
author: Jens Behrmann, Will Grathwohl, Ricky T. Q. Chen, David Duvenaud, J&#xf6;rn-Henrik Jacobsen
mathjax: true
---

* content
{:toc}

##### Abstract
We show that standard ResNet architectures can be made invertible, allowing the same model to be used for classification, density estimation, and generation. Typically, enforcing invertibility requires partitioning dimensions or restricting network architectures. In contrast, our approach only requires adding a simple normalization step during training, already available in standard frameworks. Invertible ResNets define a generative model which can be trained by maximum likelihood on unlabeled data. To compute likelihoods, we introduce a tractable approximation to the Jacobian log-determinant of a residual block. Our empirical evaluation shows that invertible ResNets perform competitively with both state-of-the-art image classifiers and flow-based generative models, something that has not been previously achieved with a single architecture.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00995](http://arxiv.org/abs/1811.00995)

##### PDF
[http://arxiv.org/pdf/1811.00995](http://arxiv.org/pdf/1811.00995)

