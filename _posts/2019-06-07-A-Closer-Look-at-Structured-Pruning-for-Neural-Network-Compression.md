---
layout: post
title: "A Closer Look at Structured Pruning for Neural Network Compression"
date: 2019-06-07 14:23:14
categories: arXiv_CV
tags: arXiv_CV Inference
author: Elliot J. Crowley, Jack Turner, Amos Storkey, Michael O&#x27;Boyle
mathjax: true
---

* content
{:toc}

##### Abstract
Structured pruning is a popular method for compressing a neural network: given a large trained network, one alternates between removing channel connections and fine-tuning; reducing the overall width of the network. However, the efficacy of structured pruning has largely evaded scrutiny. In this paper, we examine ResNets and DenseNets obtained through structured pruning-and-tuning and make two interesting observations: (i) reduced networks---smaller versions of the original network trained from scratch---consistently outperform pruned networks; (ii) if one takes the architecture of a pruned network and then trains it from scratch it is significantly more competitive. Furthermore, these architectures are easy to approximate: we can prune once and obtain a family of new, scalable network architectures that can simply be trained from scratch. Finally, we compare the inference speed of reduced and pruned networks on hardware, and show that reduced networks are significantly faster. Code is available at https://github.com/BayesWatch/pytorch-prunes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.04622](http://arxiv.org/abs/1810.04622)

##### PDF
[http://arxiv.org/pdf/1810.04622](http://arxiv.org/pdf/1810.04622)

