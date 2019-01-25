---
layout: post
title: "DeepCorrect: Correcting DNN models against Image Distortions"
date: 2019-01-24 02:13:57
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Tejas Borkar, Lina Karam
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, the widespread use of deep neural networks (DNNs) has facilitated great improvements in performance for computer vision tasks like image classification and object recognition. In most realistic computer vision applications, an input image undergoes some form of image distortion such as blur and additive noise during image acquisition or transmission. Deep networks trained on pristine images perform poorly when tested on such distortions. In this paper, we evaluate the effect of image distortions like Gaussian blur and additive noise on the activations of pre-trained convolutional filters. We propose a metric to identify the most noise susceptible convolutional filters and rank them in order of the highest gain in classification accuracy upon correction. In our proposed approach called DeepCorrect, we apply small stacks of convolutional layers with residual connections, at the output of these ranked filters and train them to correct the worst distortion affected filter activations, whilst leaving the rest of the pre-trained filter outputs in the network unchanged. Performance results show that applying DeepCorrect models for common vision tasks like image classification (ImageNet), object recognition (Caltech-101, Caltech-256) and scene classification (SUN-397), significantly improves the robustness of DNNs against distorted images and outperforms other alternative approaches..

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1705.02406](http://arxiv.org/abs/1705.02406)

##### PDF
[http://arxiv.org/pdf/1705.02406](http://arxiv.org/pdf/1705.02406)

