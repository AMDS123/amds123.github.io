---
layout: post
title: "Dynamic Representations Toward Efficient Inference on Deep Neural Networks by Decision Gates"
date: 2019-05-11 16:35:49
categories: arXiv_CV
tags: arXiv_CV Embedding Inference Prediction
author: Mohammad Saeed Shafiee, Mohammad Javad Shafiee, Alexander Wong
mathjax: true
---

* content
{:toc}

##### Abstract
While deep neural networks extract rich features from the input data, the current trade-off between depth and computational cost makes it difficult to adopt deep neural networks for many industrial applications, especially when computing power is limited. Here, we are inspired by the idea that, while deeper embeddings are needed to discriminate difficult samples (i.e., fine-grained discrimination), a large number of samples can be well discriminated via much shallower embeddings (i.e., coarse-grained discrimination). In this study, we introduce the simple yet effective concept of decision gates (d-gate), modules trained to decide whether a sample needs to be projected into a deeper embedding or if an early prediction can be made at the d-gate, thus enabling the computation of dynamic representations at different depths. The proposed d-gate modules can be integrated with any deep neural network and reduces the average computational cost of the deep neural networks while maintaining modeling accuracy. The proposed d-gate framework is examined via different network architectures and datasets, with experimental results showing that leveraging the proposed d-gate modules led to a ~43% speed-up and 44% FLOPs reduction on ResNet-101 and 55% speed-up and 39% FLOPs reduction on DenseNet-201 trained on the CIFAR10 dataset with only ~2% drop in accuracy. Furthermore, experiments where d-gate modules are integrated into ResNet-101 trained on the ImageNet dataset demonstrate that it is possible to reduce the computational cost of the network by 1.5 GFLOPs without any drop in the modeling accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01476](http://arxiv.org/abs/1811.01476)

##### PDF
[http://arxiv.org/pdf/1811.01476](http://arxiv.org/pdf/1811.01476)

