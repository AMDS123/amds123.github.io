---
layout: post
title: "Clustering and Classification Networks"
date: 2019-06-20 15:59:22
categories: arXiv_CV
tags: arXiv_CV Classification
author: Jin-mo Choi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we will describe a network architecture that demonstrates high performance on various sizes of datasets. To do this, we will perform an architecture search by dividing the fully connected layer into three levels in the existing network architecture. The first step is to learn existing CNN layer and existing fully connected layer for 1 epoch. The second step is clustering similar classes by applying L1 distance to the result of Softmax. The third step is to reclassify using clustering class masks. We accomplished the result of state-of-the-art by performing the above three steps sequentially or recursively. The technology recorded an error of 11.56% on Cifar-100.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08714](http://arxiv.org/abs/1906.08714)

##### PDF
[http://arxiv.org/pdf/1906.08714](http://arxiv.org/pdf/1906.08714)

