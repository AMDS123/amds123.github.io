---
layout: post
title: "Denoising Prior Driven Deep Neural Network for Image Restoration"
date: 2018-01-21 03:08:11
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Weisheng Dong, Peiyao Wang, Wotao Yin, Guangming Shi, Fangfang Wu, Xiaotong Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have shown very promising results for various image restoration (IR) tasks. However, the design of network architectures remains a major challenging for achieving further improvements. While most existing DNN-based methods solve the IR problems by directly mapping low quality images to desirable high-quality images, the observation models characterizing the image degradation processes have been largely ignored. In this paper, we first propose a denoising-based IR algorithm, whose iterative steps can be computed efficiently. Then, the iterative process is unfolded into a deep neural network, which is composed of multiple denoisers modules interleaved with back-projection (BP) modules that ensure the observation consistencies. A convolutional neural network (CNN) based denoiser that can exploit the multi-scale redundancies of natural images is proposed. As such, the proposed network not only exploits the powerful denoising ability of DNNs, but also leverages the prior of the observation model. Through end-to-end training, both the denoisers and the BP modules can be jointly optimized. Experimental results on several IR tasks, e.g., image denoising, super-resolution and deblurring show that the proposed method can lead to very competitive and often state-of-the-art results on several IR tasks, including image denoising, deblurring and super-resolution.

##### Abstract (translated by Google)
深度神经网络（DNN）已经显示出对于各种图像恢复（IR）任务非常有希望的结果。然而，网络架构的设计仍然是实现进一步改进的主要挑战。尽管大多数现有的基于DNN的方法通过将低质量图像直接映射到期望的高质量图像来解决IR问题，但是表征图像劣化过程的观察模型在很大程度上被忽略。在本文中，我们首先提出一种基于去噪的IR算法，其迭代步骤可以被有效地计算。然后将迭代过程展开成一个深度神经网络，由多个分解模块交错组成，保证观测的一致性。提出一种基于卷积神经网络（CNN）的降噪器，可以利用自然图像的多尺度冗余。因此，所提出的网络不仅利用了DNN的强大的去噪能力，而且利用了观测模型的先验性。通过端到端的培训，可以共同优化分子和BP模块。实验结果表明，该方法在图像去噪，超分辨率和去模糊等多项红外任务中具有很强的竞争性和经常性，解析度。

##### URL
[https://arxiv.org/abs/1801.06756](https://arxiv.org/abs/1801.06756)

##### PDF
[https://arxiv.org/pdf/1801.06756](https://arxiv.org/pdf/1801.06756)

