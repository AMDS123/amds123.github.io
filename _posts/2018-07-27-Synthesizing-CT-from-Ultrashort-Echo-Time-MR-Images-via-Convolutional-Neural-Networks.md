---
layout: post
title: "Synthesizing CT from Ultrashort Echo-Time MR Images via Convolutional Neural Networks"
date: 2018-07-27 22:43:12
categories: arXiv_CV
tags: arXiv_CV CNN
author: Snehashis Roy, John A. Butman, Dzung L. Pham
mathjax: true
---

* content
{:toc}

##### Abstract
With the increasing popularity of PET-MR scanners in clinical applications, synthesis of CT images from MR has been an important research topic. Accurate PET image reconstruction requires attenuation correction, which is based on the electron density of tissues and can be obtained from CT images. While CT measures electron density information for x-ray photons, MR images convey information about the magnetic properties of tissues. Therefore, with the advent of PET-MR systems, the attenuation coefficients need to be indirectly estimated from MR images. In this paper, we propose a fully convolutional neural network (CNN) based method to synthesize head CT from ultra-short echo-time (UTE) dual-echo MR images. Unlike traditional $T_1$-w images which do not have any bone signal, UTE images show some signal for bone, which makes it a good candidate for MR to CT synthesis. A notable advantage of our approach is that accurate results were achieved with a small training data set. Using an atlas of a single CT and dual-echo UTE pair, we train a deep neural network model to learn the transform of MR intensities to CT using patches. We compared our CNN based model with a state-of-the-art registration based as well as a Bayesian model based CT synthesis method, and showed that the proposed CNN model outperforms both of them. We also compared the proposed model when only $T_1$-w images are available instead of UTE, and show that UTE images produce better synthesis than using just $T_1$-w images.

##### Abstract (translated by Google)
随着PET-MR扫描仪在临床应用中的日益普及，MR合成CT图像已成为一个重要的研究课题。准确的PET图像重建需要衰减校正，其基于组织的电子密度并且可以从CT图像获得。当CT测量X射线光子的电子密度信息时，MR图像传达关于组织的磁性的信息。因此，随着PET-MR系统的出现，需要从MR图像间接估计衰减系数。在本文中，我们提出了一种基于完全卷积神经网络（CNN）的方法，从超短回波时间（UTE）双回波MR图像合成头部CT。与传统的没有任何骨骼信号的$ T_1 $ -w图像不同，UTE图像显示骨骼的一些信号，这使其成为MR到CT合成的良好候选者。我们的方法的一个显着优点是使用小的训练数据集实现了准确的结果。使用单个CT和双回波UTE对的图集，我们训练深度神经网络模型以学习使用贴片将MR强度转换为CT。我们将基于CNN的模型与基于现有技术的基于模型的基于贝叶斯模型的CT合成方法进行了比较，并且表明所提出的CNN模型优于它们。当只有$ T_1 $ -w图像可用而不是UTE时，我们还比较了所提出的模型，并且表明UTE图像比仅使用$ T_1 $ -w图像产生更好的合成。

##### URL
[http://arxiv.org/abs/1807.10850](http://arxiv.org/abs/1807.10850)

##### PDF
[http://arxiv.org/pdf/1807.10850](http://arxiv.org/pdf/1807.10850)

