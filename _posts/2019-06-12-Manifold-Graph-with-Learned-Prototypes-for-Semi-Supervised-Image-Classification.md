---
layout: post
title: "Manifold Graph with Learned Prototypes for Semi-Supervised Image Classification"
date: 2019-06-12 15:18:36
categories: arXiv_CV
tags: arXiv_CV Regularization Image_Classification Classification Quantitative
author: Chia-Wen Kuo, Chih-Yao Ma, Jia-Bin Huang, Zsolt Kira
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in semi-supervised learning methods rely on estimating categories for unlabeled data using a model trained on the labeled data (pseudo-labeling) and using the unlabeled data for various consistency-based regularization. In this work, we propose to additionally explicitly leverage the structure of the data manifold based on a Manifold Graph constructed over the image instances within the feature space. Specifically, we propose an architecture based on graph networks that jointly optimizes feature extraction, graph connectivity, and feature propagation and aggregation to unlabeled data in an end-to-end manner. Further, we present a novel Prototype Generator for producing a diverse set of prototypes that compactly represent each category, which supports feature propagation. To evaluate our method, we first contribute a strong baseline that combines two consistency-based regularizers that already achieves state of art results especially with fewer labels. We then show that when combined with these losses, the proposed method facilitates the propagation of information from generated prototypes to image data to further improve results. We provide extensive qualitative and quantitative experimental results on semi-supervised benchmarks demonstrating the improvements arising from our design and show that our method achieves state-of-the-art performance when compared with existing methods using a single model and comparable with ensemble methods. Specifically, we achieve error rates of 3.35% on SVHN, 8.27% on CIFAR-10, and 33.97 on CIFAR-100. With much fewer labels, we surpass the state of art by significant margins, with 39% relative error decrease on average.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.05202](http://arxiv.org/abs/1906.05202)

##### PDF
[http://arxiv.org/pdf/1906.05202](http://arxiv.org/pdf/1906.05202)

