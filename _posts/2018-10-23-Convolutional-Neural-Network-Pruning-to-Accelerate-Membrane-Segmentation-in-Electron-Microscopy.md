---
layout: post
title: "Convolutional Neural Network Pruning to Accelerate Membrane Segmentation in Electron Microscopy"
date: 2018-10-23 09:18:16
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Relation
author: Joris Roels, Jonas De Vylder, Jan Aelterman, Yvan Saeys, Wilfried Philips
mathjax: true
---

* content
{:toc}

##### Abstract
Biological membranes are one of the most basic structures and regions of interest in cell biology. In the study of membranes, segment extraction is a well-known and difficult problem because of impeding noise, directional and thickness variability, etc. Recent advances in electron microscopy membrane segmentation are able to cope with such difficulties by training convolutional neural networks. However, because of the massive amount of features that have to be extracted while propagating forward, the practical usability diminishes, even with state-of-the-art GPU's. A significant part of these network features typically contains redundancy through correlation and sparsity. In this work, we propose a pruning method for convolutional neural networks that ensures the training loss increase is minimized. We show that the pruned networks, after retraining, are more efficient in terms of time and memory, without significantly affecting the network accuracy. This way, we manage to obtain real-time membrane segmentation performance, for our specific electron microscopy setup.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09735](http://arxiv.org/abs/1810.09735)

##### PDF
[http://arxiv.org/pdf/1810.09735](http://arxiv.org/pdf/1810.09735)

