---
layout: post
title: "Joint CS-MRI Reconstruction and Segmentation with a Unified Deep Network"
date: 2018-05-06 07:45:32
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Liyan Sun, Zhiwen Fan, Yue Huang, Xinghao Ding, John Paisley
mathjax: true
---

* content
{:toc}

##### Abstract
The need for fast acquisition and automatic analysis of MRI data is growing in the age of big data. Although compressed sensing magnetic resonance imaging (CS-MRI) has been studied to accelerate MRI by reducing k-space measurements, in current CS-MRI techniques MRI applications such as segmentation are overlooked when doing image reconstruction. In this paper, we test the utility of CS-MRI methods in automatic segmentation models and propose a unified deep neural network architecture called SegNetMRI which we apply to the combined CS-MRI reconstruction and segmentation problem. SegNetMRI is built upon a MRI reconstruction network with multiple cascaded blocks each containing an encoder-decoder unit and a data fidelity unit, and MRI segmentation networks having the same encoder-decoder structure. The two subnetworks are pre-trained and fine-tuned with shared reconstruction encoders. The outputs are merged into the final segmentation. Our experiments show that SegNetMRI can improve both the reconstruction and segmentation performance when using compressive measurements.

##### Abstract (translated by Google)
在大数据时代，快速采集和自动分析MRI数据的需求正在增长。尽管已经研究了压缩感测磁共振成像（CS-MRI）以通过减少k空间测量来加速MRI，但是在当前的CS-MRI技术中，当进行图像重建时，诸如分割的MRI应用被忽略。在本文中，我们测试CS-MRI方法在自动分割模型中的效用，并提出了统一的深度神经网络结构，称为SegNetMRI，我们将其应用于CS-MRI组合重建和分割问题。 SegNetMRI建立在具有多个级联块的MRI重建网络上，每个块包含编码器 - 解码器单元和数据保真度单元，以及具有相同编码器 - 解码器结构的MRI分割网络。这两个子网络是预先训练的，并用共享重建编码器进行微调。输出被合并到最终的分割中。我们的实验显示，使用压缩测量时，SegNetMRI可以改善重建和分割性能。

##### URL
[http://arxiv.org/abs/1805.02165](http://arxiv.org/abs/1805.02165)

##### PDF
[http://arxiv.org/pdf/1805.02165](http://arxiv.org/pdf/1805.02165)

