---
layout: post
title: "$mathcal{G}$-softmax: Improving Intra-class Compactness and Inter-class Separability of Features"
date: 2019-04-08 19:31:25
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Yan Luo, Yongkang Wong, Mohan Kankanhalli, Qi Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Intra-class compactness and inter-class separability are crucial indicators to measure the effectiveness of a model to produce discriminative features, where intra-class compactness indicates how close the features with the same label are to each other and inter-class separability indicates how far away the features with different labels are. In this work, we investigate intra-class compactness and inter-class separability of features learned by convolutional networks and propose a Gaussian-based softmax ($\mathcal{G}$-softmax) function that can effectively improve intra-class compactness and inter-class separability. The proposed function is simple to implement and can easily replace the softmax function. We evaluate the proposed $\mathcal{G}$-softmax function on classification datasets (i.e., CIFAR-10, CIFAR-100, and Tiny ImageNet) and on multi-label classification datasets (i.e., MS COCO and NUS-WIDE). The experimental results show that the proposed $\mathcal{G}$-softmax function improves the state-of-the-art models across all evaluated datasets. In addition, analysis of the intra-class compactness and inter-class separability demonstrates the advantages of the proposed function over the softmax function, which is consistent with the performance improvement. More importantly, we observe that high intra-class compactness and inter-class separability are linearly correlated to average precision on MS COCO and NUS-WIDE. This implies that improvement of intra-class compactness and inter-class separability would lead to improvement of average precision.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04317](http://arxiv.org/abs/1904.04317)

##### PDF
[http://arxiv.org/pdf/1904.04317](http://arxiv.org/pdf/1904.04317)

