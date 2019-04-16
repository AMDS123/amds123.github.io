---
layout: post
title: "Memory-Efficient Deep Salient Object Segmentation Networks on Gridized Superpixels"
date: 2018-05-22 10:11:36
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Segmentation CNN Semantic_Segmentation Deep_Learning Detection
author: Caglar Aytekin, Xingyang Ni, Francesco Cricri, Lixin Fan, Emre Aksu
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision algorithms with pixel-wise labeling tasks, such as semantic segmentation and salient object detection, have gone through a significant accuracy increase with the incorporation of deep learning. Deep segmentation methods slightly modify and fine-tune pre-trained networks that have hundreds of millions of parameters. In this work, we question the need to have such memory demanding networks for the specific task of salient object segmentation. To this end, we propose a way to learn a memory-efficient network from scratch by training it only on salient object detection datasets. Our method encodes images to gridized superpixels that preserve both the object boundaries and the connectivity rules of regular pixels. This representation allows us to use convolutional neural networks that operate on regular grids. By using these encoded images, we train a memory-efficient network using only 0.048\% of the number of parameters that other deep salient object detection networks have. Our method shows comparable accuracy with the state-of-the-art deep salient object detection methods and provides a faster and a much more memory-efficient alternative to them. Due to its easy deployment, such a network is preferable for applications in memory limited devices such as mobile phones and IoT devices.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.09558](https://arxiv.org/abs/1712.09558)

##### PDF
[https://arxiv.org/pdf/1712.09558](https://arxiv.org/pdf/1712.09558)

