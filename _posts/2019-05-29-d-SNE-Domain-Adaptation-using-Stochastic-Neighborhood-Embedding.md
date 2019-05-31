---
layout: post
title: "$d$-SNE: Domain Adaptation using Stochastic Neighborhood Embedding"
date: 2019-05-29 23:16:51
categories: arXiv_CV
tags: arXiv_CV Regularization Embedding
author: Xiang Xu, Xiong Zhou, Ragav Venkatesan, Gurumurthy Swaminathan, Orchid Majumder
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks often require copious amount of labeled-data to train their scads of parameters. Training larger and deeper networks is hard without appropriate regularization, particularly while using a small dataset. Laterally, collecting well-annotated data is expensive, time-consuming and often infeasible. A popular way to regularize these networks is to simply train the network with more data from an alternate representative dataset. This can lead to adverse effects if the statistics of the representative dataset are dissimilar to our target. This predicament is due to the problem of domain shift. Data from a shifted domain might not produce bespoke features when a feature extractor from the representative domain is used. In this paper, we propose a new technique ($d$-SNE) of domain adaptation that cleverly uses stochastic neighborhood embedding techniques and a novel modified-Hausdorff distance. The proposed technique is learnable end-to-end and is therefore, ideally suited to train neural networks. Extensive experiments demonstrate that $d$-SNE outperforms the current states-of-the-art and is robust to the variances in different datasets, even in the one-shot and semi-supervised learning settings. $d$-SNE also demonstrates the ability to generalize to multiple domains concurrently.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12775](http://arxiv.org/abs/1905.12775)

##### PDF
[http://arxiv.org/pdf/1905.12775](http://arxiv.org/pdf/1905.12775)

