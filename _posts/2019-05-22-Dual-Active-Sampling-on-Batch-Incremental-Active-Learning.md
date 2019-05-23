---
layout: post
title: "Dual Active Sampling on Batch-Incremental Active Learning"
date: 2019-05-22 17:11:57
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Johan Phan, Massimiliano Ruocco, Francesco Scibilia
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, Convolutional Neural Networks (CNNs) have shown unprecedented success in the field of computer vision, especially on challenging image classification tasks by relying on a universal approach, i.e., training a deep model on a massive dataset of supervised examples. While unlabeled data are often an abundant resource, collecting a large set of labeled data, on the other hand, are very expensive, which often require considerable human efforts. One way to ease out this is to effectively select and label highly informative instances from a pool of unlabeled data (i.e., active learning). This paper proposed a new method of batch-mode active learning, Dual Active Sampling(DAS), which is based on a simple assumption, if two deep neural networks (DNNs) of the same structure and trained on the same dataset give significantly different output for a given sample, then that particular sample should be picked for additional training. While other state of the art methods in this field usually require intensive computational power or relying on a complicated structure, DAS is simpler to implement and, managed to get improved results on Cifar-10 with preferable computational time compared to the core-set method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09247](http://arxiv.org/abs/1905.09247)

##### PDF
[http://arxiv.org/pdf/1905.09247](http://arxiv.org/pdf/1905.09247)

