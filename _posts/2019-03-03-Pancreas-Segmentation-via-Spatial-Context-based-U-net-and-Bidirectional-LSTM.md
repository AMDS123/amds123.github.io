---
layout: post
title: "Pancreas Segmentation via Spatial Context based U-net and Bidirectional LSTM"
date: 2019-03-03 04:52:49
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation CNN RNN Deep_Learning
author: Hao Li, Jun Li, Xiaozhu Lin, Xiaohua Qian
mathjax: true
---

* content
{:toc}

##### Abstract
Pancreas is characterized by small size and irregular shape, so achieving accurate pancreas segmentation is challenging. Traditional 2D pancreas segmentation network based on the independent 2D image slices, which often leads to spatial discontinuity problem. Therefore, how to utility spatial context information is the key point to improve the segmentation quality. In this paper, we proposed a divide-and-conquer strategy, divided the abdominal CT scans into several isometric blocks. And we designed a multiple channels convolutional neural network to learn the local spatial context characteristics from blocks called SCU-Net. SCU-Net is a partial 3D segmentation idea, which transforms overall pancreas segmentation into a combination of multiple local segmentation results. In order to improve the segmentation accuracy for each layer, we also proposed a new loss function for inter-slice constrain and regularization. Thereafter, we introduced the BiCLSTM network for stimulating the interaction between bidirectional segmentation sequence, thus making up the boundary defect and fault problem of the segmentation results. We trained SCU-Net+BiLSTM network respectively, and evaluated segmentation result on the NIH data set. Keywords: Pancreas Segmentation, Convolutional Neural Networks, Recurrent Neural Networks, Deep Learning, Inter-slice Regularization

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00832](http://arxiv.org/abs/1903.00832)

##### PDF
[http://arxiv.org/pdf/1903.00832](http://arxiv.org/pdf/1903.00832)

