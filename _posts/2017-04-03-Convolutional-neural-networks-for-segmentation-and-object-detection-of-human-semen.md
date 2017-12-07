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
我们比较了一套卷积神经网络（CNN）体系结构，用于在从精液样本中提取的图像中分割和检测人类精子细胞。与以前的工作相反，样本没有被染色或洗涤以允许完整的精子质量分析，由于杂乱使得分析更困难。我们的结果表明，当正确处理类别偏差时，对完整图像的训练优于对补丁的训练。包括训练期间上采样的全图像训练证明在深CNN中有益于像素明智的精度和检测性能。预测的精子细胞通过在CNN预测中使用连接成分而被发现。我们调查了检测组件大小的阈值参数的优化。我们的最佳网络在经过阈值优于传统的图像分析方法之后，在我们的测试数据集上达到了93.87％的精度和91.89％的查全率。

##### URL
[https://arxiv.org/abs/1704.00498](https://arxiv.org/abs/1704.00498)

##### PDF
[https://arxiv.org/pdf/1704.00498](https://arxiv.org/pdf/1704.00498)

