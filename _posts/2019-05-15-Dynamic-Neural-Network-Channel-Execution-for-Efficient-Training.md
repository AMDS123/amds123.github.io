---
layout: post
title: "Dynamic Neural Network Channel Execution for Efficient Training"
date: 2019-05-15 21:10:28
categories: arXiv_CV
tags: arXiv_CV Salient Tracking CNN Image_Classification Inference Classification
author: Simeon E. Spasov, Pietro Lio
mathjax: true
---

* content
{:toc}

##### Abstract
Existing methods for reducing the computational burden of neural networks at run-time, such as parameter pruning or dynamic computational path selection, focus solely on improving computational efficiency during inference. On the other hand, in this work, we propose a novel method which reduces the memory footprint and number of computing operations required for training and inference. Our framework efficiently integrates pruning as part of the training procedure by exploring and tracking the relative importance of convolutional channels. At each training step, we select only a subset of highly salient channels to execute according to the combinatorial upper confidence bound algorithm, and run a forward and backward pass only on these activated channels, hence learning their parameters. Consequently, we enable the efficient discovery of compact models. We validate our approach empirically on state-of-the-art CNNs - VGGNet, ResNet and DenseNet, and on several image classification datasets. Results demonstrate our framework for dynamic channel execution reduces computational cost up to 4x and parameter count up to 9x, thus reducing the memory and computational demands for discovering and training compact neural network models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06435](http://arxiv.org/abs/1905.06435)

##### PDF
[http://arxiv.org/pdf/1905.06435](http://arxiv.org/pdf/1905.06435)

