---
layout: post
title: "Spatially-Adaptive Filter Units for Compact and Efficient Deep Neural Networks"
date: 2019-02-20 09:49:55
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation Classification
author: Domen Tabernik, Matej Kristan, Ale&#x161; Leonardis
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks excel in a number of computer vision tasks. One of their most crucial architectural elements is the effective receptive field size, that has to be manually set to accommodate a specific task. Standard solutions involve large kernels, down/up-sampling and dilated convolutions. These require testing a variety of dilation and down/up-sampling factors and result in non-compact representations and excessive number of parameters. We address this issue by proposing a new convolution filter composed of displaced aggregation units (DAU). DAUs learn spatial displacements and adapt the receptive field sizes of individual convolution filters to a given problem, thus eliminating the need for hand-crafted modifications. DAUs provide a seamless substitution of convolutional filters in existing state-of-the-art architectures, which we demonstrate on AlexNet, ResNet50, ResNet101, DeepLab and SRN-DeblurNet. The benefits of this design are demonstrated on a variety of computer vision tasks and datasets, such as image classification (ILSVRC 2012), semantic segmentation (PASCAL VOC 2011, Cityscape) and blind image de-blurring (GOPRO). Results show that DAUs efficiently allocate parameters resulting in up to four times more compact networks at similar or better performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07474](http://arxiv.org/abs/1902.07474)

##### PDF
[http://arxiv.org/pdf/1902.07474](http://arxiv.org/pdf/1902.07474)

