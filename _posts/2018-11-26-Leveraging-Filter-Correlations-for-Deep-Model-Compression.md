---
layout: post
title: "Leveraging Filter Correlations for Deep Model Compression"
date: 2018-11-26 18:05:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection Relation
author: Pravendra Singh, Vinay Kumar Verma, Piyush Rai, Vinay P. Namboodiri
mathjax: true
---

* content
{:toc}

##### Abstract
We present a filter correlation based model compression approach for deep convolutional neural networks. Our approach iteratively identifies pairs of filters with largest pairwise correlations and discards one of the filters from each such pair. However, instead of discarding one of the filter from such pairs naïvely, we further optimize the model so that the two filters from each such pair are as highly correlated as possible so that discarding one of the filters from the pairs results in as little information loss as possible. After discarding the filters in each round, we further finetune the model to recover from the potential small loss incurred by the compression. We evaluate our proposed approach using a comprehensive set of experiments and ablation studies. Our compression method yields state-of-the-art FLOPs compression rates on various benchmarks, such as LeNet-5, VGG-16, and ResNet-50,56, which are still achieving excellent predictive performance for tasks such as object detection on benchmark datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.10559](https://arxiv.org/abs/1811.10559)

##### PDF
[https://arxiv.org/pdf/1811.10559](https://arxiv.org/pdf/1811.10559)

