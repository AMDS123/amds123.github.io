---
layout: post
title: "Multitask Painting Categorization by Deep Multibranch Neural Network"
date: 2018-12-19 16:12:29
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Simone Bianco, Davide Mazzini, Paolo Napoletano, Raimondo Schettini
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we propose a new deep multibranch neural network to solve the tasks of artist, style, and genre categorization in a multitask formulation. In order to gather clues from low-level texture details and, at the same time, exploit the coarse layout of the painting, the branches of the proposed networks are fed with crops at different resolutions. We propose and compare two different crop strategies: the first one is a random-crop strategy that permits to manage the tradeoff between accuracy and speed; the second one is a smart extractor based on Spatial Transformer Networks trained to extract the most representative subregions. Furthermore, inspired by the results obtained in other domains, we experiment the joint use of hand-crafted features directly computed on the input images along with neural ones. Experiments are performed on a new dataset originally sourced from wikiart.org and hosted by Kaggle, and made suitable for artist, style and genre multitask learning. The dataset here proposed, named MultitaskPainting100k, is composed by 100K paintings, 1508 artists, 125 styles and 41 genres. Our best method, tested on the MultitaskPainting100k dataset, achieves accuracy levels of 56.5%, 57.2%, and 63.6% on the tasks of artist, style and genre prediction respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08052](http://arxiv.org/abs/1812.08052)

##### PDF
[http://arxiv.org/pdf/1812.08052](http://arxiv.org/pdf/1812.08052)

