---
layout: post
title: "ShelfNet for Real-time Semantic Segmentation"
date: 2018-11-27 20:57:48
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference
author: Juntang Zhuang, Junlin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this project, we present ShelfNet, a lightweight convolutional neural network for accurate real-time semantic segmentation. Different from the standard encoder-decoder structure, ShelfNet has multiple encoder-decoder branch pairs with skip connections at each spatial level, which looks like a shelf with multiple columns. The shelf-shaped structure provides multiple paths for information flow and improves segmentation accuracy. Inspired by the success of recurrent convolutional neural networks, we use modified residual blocks where two convolutional layers share weights. The shared-weight block enables efficient feature extraction and model size reduction. We tested ShelfNet with ResNet50 and ResNet101 as the backbone respectively: they achieved 59 FPS and 42 FPS respectively on a GTX 1080Ti GPU with a 512x512 input image. ShelfNet achieved high accuracy: on PASCAL VOC 2012 test set, it achieved 84.2% mIoU with ResNet101 backbone and 82.8% mIoU with ResNet50 backbone; it achieved 75.8% mIoU with ResNet50 backbone on Cityscapes dataset. ShelfNet achieved both higher mIoU and faster inference speed compared with state-of-the-art real-time semantic segmentation models. We provide the implementation https://github.com/juntang-zhuang/ShelfNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11254](http://arxiv.org/abs/1811.11254)

##### PDF
[http://arxiv.org/pdf/1811.11254](http://arxiv.org/pdf/1811.11254)

