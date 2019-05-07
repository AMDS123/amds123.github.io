---
layout: post
title: "Convolutional neural networks for segmentation and object detection of human semen"
date: 2017-04-03 09:40:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Optimization Prediction Detection
author: Malte Stær Nissen, Oswin Krause, Kristian Almstrup, Søren Kjærulff, Torben Trindkær Nielsen, Mads Nielsen
mathjax: true
---

* content
{:toc}

##### Abstract
We compare a set of convolutional neural network (CNN) architectures for the task of segmenting and detecting human sperm cells in an image taken from a semen sample. In contrast to previous work, samples are not stained or washed to allow for full sperm quality analysis, making analysis harder due to clutter. Our results indicate that training on full images is superior to training on patches when class-skew is properly handled. Full image training including up-sampling during training proves to be beneficial in deep CNNs for pixel wise accuracy and detection performance. Predicted sperm cells are found by using connected components on the CNN predictions. We investigate optimization of a threshold parameter on the size of detected components. Our best network achieves 93.87% precision and 91.89% recall on our test dataset after thresholding outperforming a classical mage analysis approach.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.00498](https://arxiv.org/abs/1704.00498)

##### PDF
[https://arxiv.org/pdf/1704.00498](https://arxiv.org/pdf/1704.00498)

