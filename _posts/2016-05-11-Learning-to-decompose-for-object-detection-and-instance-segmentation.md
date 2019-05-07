---
layout: post
title: "Learning to decompose for object detection and instance segmentation"
date: 2016-05-11 02:55:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection
author: Eunbyung Park, Alexander C. Berg
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep convolutional neural networks(CNNs) have achieved remarkable results on object detection and segmentation, pre- and post-processing steps such as region proposals and non-maximum suppression(NMS), have been required. These steps result in high computational complexity and sensitivity to hyperparameters, e.g. thresholds for NMS. In this work, we propose a novel end-to-end trainable deep neural network architecture, which consists of convolutional and recurrent layers, that generates the correct number of object instances and their bounding boxes (or segmentation masks) given an image, using only a single network evaluation without any pre- or post-processing steps. We have tested on detecting digits in multi-digit images synthesized using MNIST, automatically segmenting digits in these images, and detecting cars in the KITTI benchmark dataset. The proposed approach outperforms a strong CNN baseline on the synthesized digits datasets and shows promising results on KITTI car detection.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1511.06449](https://arxiv.org/abs/1511.06449)

##### PDF
[https://arxiv.org/pdf/1511.06449](https://arxiv.org/pdf/1511.06449)

