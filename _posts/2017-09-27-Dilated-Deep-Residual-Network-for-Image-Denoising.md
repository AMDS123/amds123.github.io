---
layout: post
title: "Dilated Deep Residual Network for Image Denoising"
date: 2017-09-27 23:37:46
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Quantitative
author: Tianyang Wang, Mingxuan Sun, Kaoning Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Variations of deep neural networks such as convolutional neural network (CNN) have been successfully applied to image denoising. The goal is to automatically learn a mapping from a noisy image to a clean image given training data consisting of pairs of noisy and clean images. Most existing CNN models for image denoising have many layers. In such cases, the models involve a large amount of parameters and are computationally expensive to train. In this paper, we develop a dilated residual CNN for Gaussian image denoising. Compared with the recently proposed residual denoiser, our method can achieve comparable performance with less computational cost. Specifically, we enlarge receptive field by adopting dilated convolution in residual network, and the dilation factor is set to a certain value. We utilize appropriate zero padding to make the dimension of the output the same as the input. It has been proven that the expansion of receptive field can boost the CNN performance in image classification, and we further demonstrate that it can also lead to competitive performance for denoising problem. Moreover, we present a formula to calculate receptive field size when dilated convolution is incorporated. Thus, the change of receptive field can be interpreted mathematically. To validate the efficacy of our approach, we conduct extensive experiments for both gray and color image denoising with specific or randomized noise levels. Both of the quantitative measurements and the visual results of denoising are promising comparing with state-of-the-art baselines.

##### Abstract (translated by Google)
卷积神经网络（CNN）等深度神经网络的变体已成功应用于图像去噪。我们的目标是自动学习从噪声图像到干净的图像的映射，给出由噪声干净的图像组成的训练数据。大多数现有的图像去噪CNN模型有很多层次。在这种情况下，这些模型涉及大量的参数，并且计算上花费很高。在本文中，我们发展了一个膨胀的残余CNN高斯图像去噪。与最近提出的残余降噪器相比，我们的方法能够以较低的计算成本实现可比较的性能。具体而言，我们通过在残差网络中采用扩张卷积来扩大感受域，并将扩张因子设置为一定值。我们利用适当的零填充使输出的维度与输入相同。已经证明接收域的扩展可以提高CNN在图像分类中的性能，进一步证明它也可以导致降噪问题的竞争性表现。此外，我们提出了一个公式来计算扩大卷积时纳入接收领域的大小。因此，接受场的变化可以从数学上解释。为了验证我们的方法的有效性，我们对具有特定或随机噪声水平的灰度和彩色图像去噪进行了广泛的实验。与最先进的基线相比，定量测量和去噪的视觉效果都是有前途的。

##### URL
[https://arxiv.org/abs/1708.05473](https://arxiv.org/abs/1708.05473)

##### PDF
[https://arxiv.org/pdf/1708.05473](https://arxiv.org/pdf/1708.05473)

