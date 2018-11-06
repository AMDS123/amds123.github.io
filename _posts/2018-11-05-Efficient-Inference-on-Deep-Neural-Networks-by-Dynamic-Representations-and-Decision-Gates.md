---
layout: post
title: "Efficient Inference on Deep Neural Networks by Dynamic Representations and Decision Gates"
date: 2018-11-05 01:37:39
categories: arXiv_CV
tags: arXiv_CV Embedding Inference Prediction
author: Mohammad Saeed Shafiee, Mohammad Javad Shafiee, Alexander Wong
mathjax: true
---

* content
{:toc}

##### Abstract
The current trade-off between depth and computational cost makes it difficult to adopt deep neural networks for many industrial applications, especially when computing power is limited. Here, we are inspired by the idea that, while deeper embeddings are needed to discriminate difficult samples, a large number of samples can be well discriminated via much shallower embeddings. In this study, we introduce the concept of decision gates (d-gate), modules trained to decide whether a sample needs to be projected into a deeper embedding or if an early prediction can be made at the d-gate, thus enabling the computation of dynamic representations at different depths. The proposed d-gate modules can be integrated with any deep neural network and reduces the average computational cost of the deep neural networks while maintaining modeling accuracy. Experimental results show that leveraging the proposed d-gate modules led to a ~38% speed-up and ~39% FLOPS reduction on ResNet-101 and ~46% speed-up and ~36% FLOPS reduction on DenseNet-201 trained on the CIFAR10 dataset with only ~2\% drop in accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01476](http://arxiv.org/abs/1811.01476)

##### PDF
[http://arxiv.org/pdf/1811.01476](http://arxiv.org/pdf/1811.01476)

