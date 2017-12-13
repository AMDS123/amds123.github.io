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
应用最为广泛的机器学习框架要求用户仔细调整内存使用量，以便深度神经网络（DNN）适合GPU的DRAM容量。这个限制阻碍了研究人员灵活地研究不同的机器学习算法，迫使他们使用不太理想的网络架构，或者在多个GPU上并行处理。我们提出了一个运行时内存管理器，它可以虚拟化DNN的内存使用情况，从而可以同时利用GPU和CPU内存来训练更大的DNN。我们的虚拟化DNN（vDNN）将AlexNet的平均GPU内存使用率降低了89％，OverFeat降低了91％，GoogLeNet降低了95％，这大大降低了DNN的内存需求。 VGG-16上的类似实验是迄今为止最深刻，最令人难忘的DNN之一，它展示了我们提议的记忆效率。 vDNN使批量大小为256的VGG-16（需要28 GB内存）能够在包含12 GB内存的单个NVIDIA Titan X GPU卡上进行培训，与具有足够内存的假想oracular GPU相比，性能损失达18％整个DNN。

##### URL
[https://arxiv.org/abs/1602.08124](https://arxiv.org/abs/1602.08124)

##### PDF
[https://arxiv.org/pdf/1602.08124](https://arxiv.org/pdf/1602.08124)

