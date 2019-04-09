---
layout: post
title: "Can GCNs Go as Deep as CNNs?"
date: 2019-04-07 21:49:26
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Guohao Li, Matthias M&#xfc;ller, Ali Thabet, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) achieve impressive results in a wide variety of fields. Their success benefited from a massive boost with the ability to train very deep CNN models. Despite their positive results, CNNs fail to properly address problems with non-Euclidean data. To overcome this challenge, Graph Convolutional Networks (GCNs) build graphs to represent non-Euclidean data, and borrow concepts from CNNs and apply them to train these models. GCNs show promising results, but they are limited to very shallow models due to the vanishing gradient problem. As a result most state-of-the-art GCN algorithms are no deeper than 3 or 4 layers. In this work, we present new ways to successfully train very deep GCNs. We borrow concepts from CNNs, mainly residual/dense connections and dilated convolutions, and adapt them to GCN architectures. Through extensive experiments, we show the positive effect of these deep GCN frameworks. Finally, we use these new concepts to build a very deep 56-layer GCN, and show how it significantly boosts performance (+3.7% mIoU over state-of-the-art) in the task of point cloud semantic segmentation. The project website is available at https://sites.google.com/view/deep-gcns

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03751](http://arxiv.org/abs/1904.03751)

##### PDF
[http://arxiv.org/pdf/1904.03751](http://arxiv.org/pdf/1904.03751)

