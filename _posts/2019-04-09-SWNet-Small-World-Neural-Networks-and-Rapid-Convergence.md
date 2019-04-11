---
layout: post
title: "SWNet: Small-World Neural Networks and Rapid Convergence"
date: 2019-04-09 18:41:26
categories: arXiv_AI
tags: arXiv_AI Image_Classification Classification Deep_Learning
author: Mojan Javaheripi, Bita Darvish Rouhani, Farinaz Koushanfar
mathjax: true
---

* content
{:toc}

##### Abstract
Training large and highly accurate deep learning (DL) models is computationally costly. This cost is in great part due to the excessive number of trained parameters, which are well-known to be redundant and compressible for the execution phase. This paper proposes a novel transformation which changes the topology of the DL architecture such that it reaches an optimal cross-layer connectivity. This transformation leverages our important observation that for a set level of accuracy, convergence is fastest when network topology reaches the boundary of a Small-World Network. Small-world graphs are known to possess a specific connectivity structure that enables enhanced signal propagation among nodes. Our small-world models, called SWNets, provide several intriguing benefits: they facilitate data (gradient) flow within the network, enable feature-map reuse by adding long-range connections and accommodate various network architectures/datasets. Compared to densely connected networks (e.g., DenseNets), SWNets require a substantially fewer number of training parameters while maintaining a similar level of classification accuracy. We evaluate our networks on various DL model architectures and image classification datasets, namely, CIFAR10, CIFAR100, and ILSVRC (ImageNet). Our experiments demonstrate an average of ~2.1x improvement in convergence speed to the desired accuracy

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04862](http://arxiv.org/abs/1904.04862)

##### PDF
[http://arxiv.org/pdf/1904.04862](http://arxiv.org/pdf/1904.04862)

