---
layout: post
title: "Fine-grained Optimization of Deep Neural Networks"
date: 2019-05-22 10:18:58
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Classification
author: Mete Ozay
mathjax: true
---

* content
{:toc}

##### Abstract
In recent studies, several asymptotic upper bounds on generalization errors on deep neural networks (DNNs) are theoretically derived. These bounds are functions of several norms of weights of the DNNs, such as the Frobenius and spectral norms, and they are computed for weights grouped according to either input and output channels of the DNNs. In this work, we conjecture that if we can impose multiple constraints on weights of DNNs to upper bound the norms of the weights, and train the DNNs with these weights, then we can attain empirical generalization errors closer to the derived theoretical bounds, and improve accuracy of the DNNs. 
 To this end, we pose two problems. First, we aim to obtain weights whose different norms are all upper bounded by a constant number, e.g. 1.0. To achieve these bounds, we propose a two-stage renormalization procedure; (i) normalization of weights according to different norms used in the bounds, and (ii) reparameterization of the normalized weights to set a constant and finite upper bound of their norms. In the second problem, we consider training DNNs with these renormalized weights. To this end, we first propose a strategy to construct joint spaces (manifolds) of weights according to different constraints in DNNs. Next, we propose a fine-grained SGD algorithm (FG-SGD) for optimization on the weight manifolds to train DNNs with assurance of convergence to minima. Experimental results show that image classification accuracy of baseline DNNs can be boosted using FG-SGD on collections of manifolds identified by multiple constraints.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09054](http://arxiv.org/abs/1905.09054)

##### PDF
[http://arxiv.org/pdf/1905.09054](http://arxiv.org/pdf/1905.09054)

