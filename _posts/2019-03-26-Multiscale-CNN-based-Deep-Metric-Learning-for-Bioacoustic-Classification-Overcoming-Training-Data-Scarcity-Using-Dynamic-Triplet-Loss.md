---
layout: post
title: "Multiscale CNN based Deep Metric Learning for Bioacoustic Classification: Overcoming Training Data Scarcity Using Dynamic Triplet Loss"
date: 2019-03-26 07:16:38
categories: arXiv_SD
tags: arXiv_SD Embedding CNN Classification
author: Anshul Thakur, Daksh Thapar, Padmanabhan Rajan, Aditya Nigam
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes multiscale convolutional neural network (CNN)-based deep metric learning for bioacoustic classification, under low training data conditions. The proposed CNN is characterized by the utilization of four different filter sizes at each level to analyze input feature maps. This multiscale nature helps in describing different bioacoustic events effectively: smaller filters help in learning the finer details of bioacoustic events, whereas, larger filters help in analyzing a larger context leading to global details. A dynamic triplet loss is employed in the proposed CNN architecture to learn a transformation from the input space to the embedding space, where classification is performed. The triplet loss helps in learning this transformation by analyzing three examples, referred to as triplets, at a time where intra-class distance is minimized while maximizing the inter-class separation by a dynamically increasing margin. The number of possible triplets increases cubically with the dataset size, making triplet loss more suitable than the softmax cross-entropy loss in low training data conditions. Experiments on three different publicly available datasets show that the proposed framework performs better than existing bioacoustic classification frameworks. Experimental results also confirm the superiority of the triplet loss over the cross-entropy loss in low training data conditions

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10713](http://arxiv.org/abs/1903.10713)

##### PDF
[http://arxiv.org/pdf/1903.10713](http://arxiv.org/pdf/1903.10713)

