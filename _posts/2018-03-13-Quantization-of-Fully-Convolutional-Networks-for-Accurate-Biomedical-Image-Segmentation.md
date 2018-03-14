---
layout: post
title: "Quantization of Fully Convolutional Networks for Accurate Biomedical Image Segmentation"
date: 2018-03-13 16:06:13
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Quantitative
author: Xiaowei Xu, Qing Lu, Yu Hu, Lin Yang, Sharon Hu, Danny Chen, Yiyu Shi
mathjax: true
---

* content
{:toc}

##### Abstract
With pervasive applications of medical imaging in health-care, biomedical image segmentation plays a central role in quantitative analysis, clinical diagno- sis, and medical intervention. Since manual anno- tation su ers limited reproducibility, arduous e orts, and excessive time, automatic segmentation is desired to process increasingly larger scale histopathological data. Recently, deep neural networks (DNNs), par- ticularly fully convolutional networks (FCNs), have been widely applied to biomedical image segmenta- tion, attaining much improved performance. At the same time, quantization of DNNs has become an ac- tive research topic, which aims to represent weights with less memory (precision) to considerably reduce memory and computation requirements of DNNs while maintaining acceptable accuracy. In this paper, we apply quantization techniques to FCNs for accurate biomedical image segmentation. Unlike existing litera- ture on quantization which primarily targets memory and computation complexity reduction, we apply quan- tization as a method to reduce over tting in FCNs for better accuracy. Speci cally, we focus on a state-of- the-art segmentation framework, suggestive annotation [22], which judiciously extracts representative annota- tion samples from the original training dataset, obtain- ing an e ective small-sized balanced training dataset. We develop two new quantization processes for this framework: (1) suggestive annotation with quantiza- tion for highly representative training samples, and (2) network training with quantization for high accuracy. Extensive experiments on the MICCAI Gland dataset show that both quantization processes can improve the segmentation performance, and our proposed method exceeds the current state-of-the-art performance by up to 1%. In addition, our method has a reduction of up to 6.4x on memory usage.

##### Abstract (translated by Google)
随着医疗影像在医疗保健中的广泛应用，生物医学图像分割在定量分析，临床诊断和医疗干预中发挥着核心作用。由于手动注册具有有限的重复性，艰苦的工作和过多的时间，因此需要自动分割以处理越来越大规模的组织病理学数据。最近，深度神经网络（DNNs），特别是完全卷积网络（FCNs），已被广泛应用于生物医学图像分割，获得了更好的性能。与此同时，DNN的量化已成为一个活跃的研究课题，其目标是用较少的内存（精度）来表示权重，以在保持可接受的精度的同时大大降低DNN的存储器和计算要求。在本文中，我们将量化技术应用于FCNs，以实现精确的生物医学图像分割。与现有的量化主要针对内存和计算复杂度降低的文献不同，我们将量化作为一种​​方法来减少FCN中的重叠以获得更好的准确性。具体而言，我们专注于最先进的分割框架，提示性注释[22]，它从原始训练数据集中明智地提取代表性注释样本，获得有效的小型平衡训练数据集。我们针对该框架开发了两种新的量化过程：（1）具有高度代表性训练样本量化的暗示性注释;（2）具有高精度量化的网络训练。在MICCAI格兰德数据集上进行的大量实验表明，两种量化过程都可以提高分割性能，并且我们提出的方法超过当前最先进的性能高达1％。另外，我们的方法在内存使用上可以减少高达6.4倍。

##### URL
[http://arxiv.org/abs/1803.04907](http://arxiv.org/abs/1803.04907)

##### PDF
[http://arxiv.org/pdf/1803.04907](http://arxiv.org/pdf/1803.04907)

