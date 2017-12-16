---
layout: post
title: "Fast Image Processing with Fully-Convolutional Networks"
date: 2017-09-02 22:38:13
categories: arXiv_CV
tags: arXiv_CV Style_Transfer CNN
author: Qifeng Chen, Jia Xu, Vladlen Koltun
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach to accelerating a wide variety of image processing operators. Our approach uses a fully-convolutional network that is trained on input-output pairs that demonstrate the operator's action. After training, the original operator need not be run at all. The trained network operates at full resolution and runs in constant time. We investigate the effect of network architecture on approximation accuracy, runtime, and memory footprint, and identify a specific architecture that balances these considerations. We evaluate the presented approach on ten advanced image processing operators, including multiple variational models, multiscale tone and detail manipulation, photographic style transfer, nonlocal dehazing, and nonphotorealistic stylization. All operators are approximated by the same model. Experiments demonstrate that the presented approach is significantly more accurate than prior approximation schemes. It increases approximation accuracy as measured by PSNR across the evaluated operators by 8.5 dB on the MIT-Adobe dataset (from 27.5 to 36 dB) and reduces DSSIM by a multiplicative factor of 3 compared to the most accurate prior approximation scheme, while being the fastest. We show that our models generalize across datasets and across resolutions, and investigate a number of extensions of the presented approach. The results are shown in the supplementary video at this https URL

##### Abstract (translated by Google)
我们提出了一种加速各种图像处理操作的方法。我们的方法使用一个完全卷积网络，在输入输出对上进行训练，证明操作者的行为。培训结束后，原来的操作员根本不需要运行。训练有素的网络以全分辨率运行，并在恒定时间内运行。我们调查网络架构对逼近精度，运行时间和内存占用情况的影响，并确定一个平衡这些考虑的特定体系结构。我们评估了十个先进的图像处理算子提出的方法，包括多变量模型，多尺度色调和细节处理，照相风格转移，非局部除雾和非照片编程风格化。所有操作员都用相同的模型近似。实验证明，所提出的方法比现有的近似方案显着更准确。在MIT-Adobe数据集（从27.5到36 dB）上，通过评估运营商的PSNR测量，PSNR的逼近精度提高了8.5 dB，与最精确的先验近似方案相比，DSSIM降低了乘以3倍，同时也是最快的。我们显示我们的模型概括跨数据集和跨决议，并调查提出的方法的一些扩展。结果显示在此https网址的补充视频中

##### URL
[https://arxiv.org/abs/1709.00643](https://arxiv.org/abs/1709.00643)

##### PDF
[https://arxiv.org/pdf/1709.00643](https://arxiv.org/pdf/1709.00643)

