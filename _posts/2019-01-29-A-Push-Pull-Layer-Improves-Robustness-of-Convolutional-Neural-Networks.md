---
layout: post
title: "A Push-Pull Layer Improves Robustness of Convolutional Neural Networks"
date: 2019-01-29 10:42:04
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Nicola Strisciuglio, Manuel Lopez-Antequera, Nicolai Petkov
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new layer in Convolutional Neural Networks (CNNs) to increase their robustness to several types of noise perturbations of the input images. We call this a push-pull layer and compute its response as the combination of two half-wave rectified convolutions, with kernels of opposite polarity. It is based on a biologically-motivated non-linear model of certain neurons in the visual system that exhibit a response suppression phenomenon, known as push-pull inhibition. We validate our method by substituting the first convolutional layer of the LeNet-5 and WideResNet architectures with our push-pull layer. We train the networks on nonperturbed training images from the MNIST, CIFAR-10 and CIFAR-100 data sets, and test on images perturbed by noise that is unseen by the training process. We demonstrate that our push-pull layers contribute to a considerable improvement in robustness of classification of images perturbed by noise, while maintaining state-of-the-art performance on the original image classification task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10208](http://arxiv.org/abs/1901.10208)

##### PDF
[http://arxiv.org/pdf/1901.10208](http://arxiv.org/pdf/1901.10208)

