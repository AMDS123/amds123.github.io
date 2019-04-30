---
layout: post
title: "Solo or Ensemble? Choosing a CNN Architecture for Melanoma Classification"
date: 2019-04-29 14:06:19
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Classification Relation
author: F&#xe1;bio Perez, Sandra Avila, Eduardo Valle
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) deliver exceptional results for computer vision, including medical image analysis. With the growing number of available architectures, picking one over another is far from obvious. Existing art suggests that, when performing transfer learning, the performance of CNN architectures on ImageNet correlates strongly with their performance on target tasks. We evaluate that claim for melanoma classification, over 9 CNNs architectures, in 5 sets of splits created on the ISIC Challenge 2017 dataset, and 3 repeated measures, resulting in 135 models. The correlations we found were, to begin with, much smaller than those reported by existing art, and disappeared altogether when we considered only the top-performing networks: uncontrolled nuisances (i.e., splits and randomness) overcome any of the analyzed factors. Whenever possible, the best approach for melanoma classification is still to create ensembles of multiple models. We compared two choices for selecting which models to ensemble: picking them at random (among a pool of high-quality ones) vs. using the validation set to determine which ones to pick first. For small ensembles, we found a slight advantage on the second approach but found that random choice was also competitive. Although our aim in this paper was not to maximize performance, we easily reached AUCs comparable to the first place on the ISIC Challenge 2017.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12724](http://arxiv.org/abs/1904.12724)

##### PDF
[http://arxiv.org/pdf/1904.12724](http://arxiv.org/pdf/1904.12724)

