---
layout: post
title: "LightMC: A Dynamic and Efficient Multiclass Decomposition Algorithm"
date: 2019-08-25 17:12:01
categories: arXiv_AI
tags: arXiv_AI Classification Relation
author: Ziyu Liu, Guolin Ke, Jiang Bian, Tieyan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Multiclass decomposition splits a multiclass classification problem into a series of independent binary learners and recomposes them by combining their outputs to reconstruct the multiclass classification results. Three widely-used realizations of such decomposition methods are One-Versus-All (OVA), One-Versus-One (OVO), and Error-Correcting-Output-Code (ECOC). While OVA and OVO are quite simple, both of them assume all classes are orthogonal which neglect the latent correlation between classes in real-world. Error-Correcting-Output-Code (ECOC) based decomposition methods, on the other hand, are more preferable due to its integration of the correlation among classes. However, the performance of existing ECOC-based methods highly depends on the design of coding matrix and decoding strategy. Unfortunately, it is quite uncertain and time-consuming to discover an effective coding matrix with appropriate decoding strategy. To address this problem, we propose LightMC, an efficient dynamic multiclass decomposition algorithm. Instead of using fixed coding matrix and decoding strategy, LightMC uses a differentiable decoding strategy, which enables it to dynamically optimize the coding matrix and decoding strategy, toward increasing the overall accuracy of multiclass classification, via back propagation jointly with the training of base learners in an iterative way. Empirical experimental results on several public large-scale multiclass classification datasets have demonstrated the effectiveness of LightMC in terms of both good accuracy and high efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09362](http://arxiv.org/abs/1908.09362)

##### PDF
[http://arxiv.org/pdf/1908.09362](http://arxiv.org/pdf/1908.09362)

