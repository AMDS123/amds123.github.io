---
layout: post
title: "DropConnect Is Effective in Modeling Uncertainty of Bayesian Deep Networks"
date: 2019-06-07 20:51:52
categories: arXiv_AI
tags: arXiv_AI Segmentation Semantic_Segmentation Inference Classification Deep_Learning Prediction
author: Aryan Mobiny, Hien V. Nguyen, Supratik Moulik, Naveen Garg, Carol C. Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have achieved state-of-the-art performances in many important domains, including medical diagnosis, security, and autonomous driving. In these domains where safety is highly critical, an erroneous decision can result in serious consequences. While a perfect prediction accuracy is not always achievable, recent work on Bayesian deep networks shows that it is possible to know when DNNs are more likely to make mistakes. Knowing what DNNs do not know is desirable to increase the safety of deep learning technology in sensitive applications. Bayesian neural networks attempt to address this challenge. However, traditional approaches are computationally intractable and do not scale well to large, complex neural network architectures. In this paper, we develop a theoretical framework to approximate Bayesian inference for DNNs by imposing a Bernoulli distribution on the model weights. This method, called MC-DropConnect, gives us a tool to represent the model uncertainty with little change in the overall model structure or computational cost. We extensively validate the proposed algorithm on multiple network architectures and datasets for classification and semantic segmentation tasks. We also propose new metrics to quantify the uncertainty estimates. This enables an objective comparison between MC-DropConnect and prior approaches. Our empirical results demonstrate that the proposed framework yields significant improvement in both prediction accuracy and uncertainty estimation quality compared to the state of the art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04569](http://arxiv.org/abs/1906.04569)

##### PDF
[http://arxiv.org/pdf/1906.04569](http://arxiv.org/pdf/1906.04569)

