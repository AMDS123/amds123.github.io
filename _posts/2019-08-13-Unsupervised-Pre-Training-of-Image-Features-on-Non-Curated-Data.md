---
layout: post
title: "Unsupervised Pre-Training of Image Features on Non-Curated Data"
date: 2019-08-13 08:31:13
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification
author: Mathilde Caron, Piotr Bojanowski, Julien Mairal, Armand Joulin
mathjax: true
---

* content
{:toc}

##### Abstract
Pre-training general-purpose visual features with convolutional neural networks without relying on annotations is a challenging and important task. Most recent efforts in unsupervised feature learning have focused on either small or highly curated datasets like ImageNet, whereas using uncurated raw datasets was found to decrease the feature quality when evaluated on a transfer task. Our goal is to bridge the performance gap between unsupervised methods trained on curated data, which are costly to obtain, and massive raw datasets that are easily available. To that effect, we propose a new unsupervised approach which leverages self-supervision and clustering to capture complementary statistics from large-scale data. We validate our approach on 96 million images from YFCC100M, achieving state-of-the-art results among unsupervised methods on standard benchmarks, which confirms the potential of unsupervised learning when only uncurated data are available. We also show that pre-training a supervised VGG-16 with our method achieves 74.9% top-1 classification accuracy on the validation set of ImageNet, which is an improvement of +0.8% over the same network trained from scratch. Our code is available at https://github.com/facebookresearch/DeeperCluster.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01278](http://arxiv.org/abs/1905.01278)

##### PDF
[http://arxiv.org/pdf/1905.01278](http://arxiv.org/pdf/1905.01278)

