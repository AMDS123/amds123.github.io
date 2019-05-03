---
layout: post
title: "Human Action Recognition with Deep Temporal Pyramids"
date: 2019-05-02 13:48:17
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Recognition
author: Ahmed Mazari, Hichem Sahbi
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) are nowadays achieving significant leaps in different pattern recognition tasks including action recognition. Current CNNs are increasingly deeper, data-hungrier and this makes their success tributary of the abundance of labeled training data. CNNs also rely on max/average pooling which reduces dimensionality of output layers and hence attenuates their sensitivity to the availability of labeled data. However, this process may dilute the information of upstream convolutional layers and thereby affect the discrimination power of the trained representations, especially when the learned categories are fine-grained. 
 In this paper, we introduce a novel hierarchical aggregation design, for final pooling, that controls granularity of the learned representations w.r.t the actual granularity of action categories. Our solution is based on a tree-structured temporal pyramid that aggregates outputs of CNNs at different levels. Top levels of this hierarchy are dedicated to coarse categories while deep levels are more suitable to fine-grained ones. The design of our temporal pyramid is based on solving a constrained minimization problem whose solution corresponds to the distribution of weights of different representations in the temporal pyramid. Experiments conducted using the challenging UCF101 database show the relevance of our hierarchical design w.r.t other related methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00745](http://arxiv.org/abs/1905.00745)

##### PDF
[http://arxiv.org/pdf/1905.00745](http://arxiv.org/pdf/1905.00745)

