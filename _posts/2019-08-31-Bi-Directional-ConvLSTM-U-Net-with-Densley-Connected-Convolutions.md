---
layout: post
title: "Bi-Directional ConvLSTM U-Net with Densley Connected Convolutions"
date: 2019-08-31 08:29:31
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN Deep_Learning
author: Reza Azad, Maryam Asadi-Aghbolaghi, Mahmood Fathy, Sergio Escalera
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep learning-based networks have achieved state-of-the-art performance in medical image segmentation. Among the existing networks, U-Net has been successfully applied on medical image segmentation. In this paper, we propose an extension of U-Net, Bi-directional ConvLSTM U-Net with Densely connected convolutions (BCDU-Net), for medical image segmentation, in which we take full advantages of U-Net, bi-directional ConvLSTM (BConvLSTM) and the mechanism of dense convolutions. Instead of a simple concatenation in the skip connection of U-Net, we employ BConvLSTM to combine the feature maps extracted from the corresponding encoding path and the previous decoding up-convolutional layer in a non-linear way. To strengthen feature propagation and encourage feature reuse, we use densely connected convolutions in the last convolutional layer of the encoding path. Finally, we can accelerate the convergence speed of the proposed network by employing batch normalization (BN). The proposed model is evaluated on three datasets of: retinal blood vessel segmentation, skin lesion segmentation, and lung nodule segmentation, achieving state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00166](http://arxiv.org/abs/1909.00166)

##### PDF
[http://arxiv.org/pdf/1909.00166](http://arxiv.org/pdf/1909.00166)

