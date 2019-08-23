---
layout: post
title: "Optimal input configuration of dynamic contrast enhanced MRI in convolutional neural networks for liver segmentation"
date: 2019-08-22 08:27:28
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Mariëlle J.A. Jansen, Hugo J. Kuijf, Josien P.W. Pluim
mathjax: true
---

* content
{:toc}

##### Abstract
Most MRI liver segmentation methods use a structural 3D scan as input, such as a T1 or T2 weighted scan. Segmentation performance may be improved by utilizing both structural and functional information, as contained in dynamic contrast enhanced (DCE) MR series. Dynamic information can be incorporated in a segmentation method based on convolutional neural networks in a number of ways. In this study, the optimal input configuration of DCE MR images for convolutional neural networks (CNNs) is studied. The performance of three different input configurations for CNNs is studied for a liver segmentation task. The three configurations are I) one phase image of the DCE-MR series as input image; II) the separate phases of the DCE-MR as input images; and III) the separate phases of the DCE-MR as channels of one input image. The three input configurations are fed into a dilated fully convolutional network and into a small U-net. The CNNs were trained using 19 annotated DCE-MR series and tested on another 19 annotated DCE-MR series. The performance of the three input configurations for both networks is evaluated against manual annotations. The results show that both neural networks perform better when the separate phases of the DCE-MR series are used as channels of an input image in comparison to one phase as input image or the separate phases as input images. No significant difference between the performances of the two network architectures was found for the separate phases as channels of an input image.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08251](https://arxiv.org/abs/1908.08251)

##### PDF
[https://arxiv.org/pdf/1908.08251](https://arxiv.org/pdf/1908.08251)

