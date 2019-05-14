---
layout: post
title: "Ensemble Super-Resolution with A Reference Dataset"
date: 2019-05-12 11:22:18
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Knowledge Optimization Inference Deep_Learning
author: Junjun Jiang, Yi Yu, Zheng Wang, Suhua Tang, Ruimin Hu, Jiayi Ma
mathjax: true
---

* content
{:toc}

##### Abstract
By developing sophisticated image priors or designing deep(er) architectures, a variety of image Super-Resolution (SR) approaches have been proposed recently and achieved very promising performance. A natural question that arises is whether these methods can be reformulated into a unifying framework and whether this framework assists in SR reconstruction? In this paper, we present a simple but effective single image SR method based on ensemble learning, which can produce a better performance than that could be obtained from any of SR methods to be ensembled (or called component super-resolvers). Based on the assumption that better component super-resolver should have larger ensemble weight when performing SR reconstruction, we present a Maximum A Posteriori (MAP) estimation framework for the inference of optimal ensemble weights. Specially, we introduce a reference dataset, which is composed of High-Resolution (HR) and Low-Resolution (LR) image pairs, to measure the super-resolution abilities (prior knowledge) of different component super-resolvers. To obtain the optimal ensemble weights, we propose to incorporate the reconstruction constraint, which states that the degenerated HR image should be equal to the LR observation one, as well as the prior knowledge of ensemble weights into the MAP estimation framework. Moreover, the proposed optimization problem can be solved by an analytical solution. We study the performance of the proposed method by comparing with different competitive approaches, including four state-of-the-art non-deep learning based methods, four latest deep learning based methods and one ensemble learning based method, and prove its effectiveness and superiority on three public datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04696](http://arxiv.org/abs/1905.04696)

##### PDF
[http://arxiv.org/pdf/1905.04696](http://arxiv.org/pdf/1905.04696)

