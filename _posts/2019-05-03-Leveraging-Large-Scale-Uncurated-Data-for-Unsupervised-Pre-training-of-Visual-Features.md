---
layout: post
title: "Leveraging Large-Scale Uncurated Data for Unsupervised Pre-training of Visual Features"
date: 2019-05-03 17:20:55
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Mathilde Caron, Piotr Bojanowski, Julien Mairal, Armand Joulin
mathjax: true
---

* content
{:toc}

##### Abstract
Pre-training general-purpose visual features with convolutional neural networks without relying on annotations is a challenging and important task. Most recent efforts in unsupervised feature learning have focused on either small or highly curated datasets like ImageNet, whereas using uncurated raw datasets was found to decrease the feature quality when evaluated on a transfer task. Our goal is to bridge the performance gap between unsupervised methods trained on curated data, which are costly to obtain, and massive raw datasets that are easily available. To that effect, we propose a new unsupervised approach which leverages self-supervision and clustering to capture complementary statistics from large-scale data. We validate our approach on 96 million images from YFCC100M, achieving state-of-the-art results among unsupervised methods on standard benchmarks, which confirms the potential of unsupervised learning when only uncurated data are available. We also show that pre-training a supervised VGG-16 with our method achieves 74.6% top-1 accuracy on the validation set of ImageNet classification, which is an improvement of +0.7% over the same network trained from scratch.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01278](http://arxiv.org/abs/1905.01278)

##### PDF
[http://arxiv.org/pdf/1905.01278](http://arxiv.org/pdf/1905.01278)

