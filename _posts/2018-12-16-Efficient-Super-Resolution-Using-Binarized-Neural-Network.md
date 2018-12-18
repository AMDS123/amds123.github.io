---
layout: post
title: "Efficient Super Resolution Using Binarized Neural Network"
date: 2018-12-16 02:44:20
categories: arXiv_AI
tags: arXiv_AI Super_Resolution Image_Enhancement CNN Image_Classification Inference Classification Quantitative Recognition
author: Yinglan Ma, Hongyu Xiong, Zhe Hu, Lizhuang Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (DCNNs) have recently demonstrated high-quality results in single-image super-resolution (SR). DCNNs often suffer from over-parametrization and large amounts of redundancy, which results in inefficient inference and high memory usage, preventing massive applications on mobile devices. As a way to significantly reduce model size and computation time, binarized neural network has only been shown to excel on semantic-level tasks such as image classification and recognition. However, little effort of network quantization has been spent on image enhancement tasks like SR, as network quantization is usually assumed to sacrifice pixel-level accuracy. In this work, we explore an network-binarization approach for SR tasks without sacrificing much reconstruction accuracy. To achieve this, we binarize the convolutional filters in only residual blocks, and adopt a learnable weight for each binary filter. We evaluate this idea on several state-of-the-art DCNN-based architectures, and show that binarized SR networks achieve comparable qualitative and quantitative results as their real-weight counterparts. Moreover, the proposed binarized strategy could help reduce model size by 80% when applying on SRResNet, and could potentially speed up inference by 5 times.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06378](http://arxiv.org/abs/1812.06378)

##### PDF
[http://arxiv.org/pdf/1812.06378](http://arxiv.org/pdf/1812.06378)

