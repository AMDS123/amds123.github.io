---
layout: post
title: "Cascaded Projection: End-to-End Network Compression and Acceleration"
date: 2019-03-12 15:20:10
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification Gradient_Descent
author: Breton Minnehan, Andreas Savakis
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a data-driven approach for deep convolutional neural network compression that achieves high accuracy with high throughput and low memory requirements. Current network compression methods either find a low-rank factorization of the features that requires more memory, or select only a subset of features by pruning entire filter channels. We propose the Cascaded Projection (CaP) compression method that projects the output and input filter channels of successive layers to a unified low dimensional space based on a low-rank projection. We optimize the projection to minimize classification loss and the difference between the next layer's features in the compressed and uncompressed networks. To solve this non-convex optimization problem we propose a new optimization method of a proxy matrix using backpropagation and Stochastic Gradient Descent (SGD) with geometric constraints. Our cascaded projection approach leads to improvements in all critical areas of network compression: high accuracy, low memory consumption, low parameter count and high processing speed. The proposed CaP method demonstrates state-of-the-art results compressing VGG16 and ResNet networks with over 4x reduction in the number of computations and excellent performance in top-5 accuracy on the ImageNet dataset before and after fine-tuning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04988](http://arxiv.org/abs/1903.04988)

##### PDF
[http://arxiv.org/pdf/1903.04988](http://arxiv.org/pdf/1903.04988)

