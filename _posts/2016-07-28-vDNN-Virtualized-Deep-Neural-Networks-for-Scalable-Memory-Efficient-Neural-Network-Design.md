---
layout: post
title: "vDNN: Virtualized Deep Neural Networks for Scalable, Memory-Efficient Neural Network Design"
date: 2016-07-28 23:19:03
categories: arXiv_CV
tags: arXiv_CV
author: Minsoo Rhu, Natalia Gimelshein, Jason Clemons, Arslan Zulfiqar, Stephen W. Keckler
mathjax: true
---

* content
{:toc}

##### Abstract
The most widely used machine learning frameworks require users to carefully tune their memory usage so that the deep neural network (DNN) fits into the DRAM capacity of a GPU. This restriction hampers a researcher's flexibility to study different machine learning algorithms, forcing them to either use a less desirable network architecture or parallelize the processing across multiple GPUs. We propose a runtime memory manager that virtualizes the memory usage of DNNs such that both GPU and CPU memory can simultaneously be utilized for training larger DNNs. Our virtualized DNN (vDNN) reduces the average GPU memory usage of AlexNet by up to 89%, OverFeat by 91%, and GoogLeNet by 95%, a significant reduction in memory requirements of DNNs. Similar experiments on VGG-16, one of the deepest and memory hungry DNNs to date, demonstrate the memory-efficiency of our proposal. vDNN enables VGG-16 with batch size 256 (requiring 28 GB of memory) to be trained on a single NVIDIA Titan X GPU card containing 12 GB of memory, with 18% performance loss compared to a hypothetical, oracular GPU with enough memory to hold the entire DNN.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1602.08124](https://arxiv.org/abs/1602.08124)

##### PDF
[https://arxiv.org/pdf/1602.08124](https://arxiv.org/pdf/1602.08124)

