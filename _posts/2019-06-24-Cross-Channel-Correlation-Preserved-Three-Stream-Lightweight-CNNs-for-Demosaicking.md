---
layout: post
title: "Cross-Channel Correlation Preserved Three-Stream Lightweight CNNs for Demosaicking"
date: 2019-06-24 12:33:49
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Niu Yan, Jihong Ouyang
mathjax: true
---

* content
{:toc}

##### Abstract
Demosaicking is a procedure to reconstruct full RGB images from Color Filter Array (CFA) samples, none of which has all color components available. Recent deep Convolutional Neural Networks (CNN) based models have obtained state of the art accuracy on benchmark datasets. However, due to the sequential feature extraction manner of CNNs, deep demosaicking models may be over slow for daily use cameras. In this paper, we decouple deep sequential demosaicking to three-stream lightweight networks, which restore the green channel, the green-red difference plane and the green-blue difference plane respectively. This strategy allows independent offline training and parallel online estimation, whilst preserving the intrinsic cross-channel correlation of natural images. Moreover, this allows designing each stream according to the various restoration difficulty of each channel. As validated by extensive experiments, our method achieves top accuracy at fast speed. Source code will be released along with paper publication.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09884](http://arxiv.org/abs/1906.09884)

##### PDF
[http://arxiv.org/pdf/1906.09884](http://arxiv.org/pdf/1906.09884)

