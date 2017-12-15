---
layout: post
title: "A Neural Approach to Blind Motion Deblurring"
date: 2016-08-01 18:53:00
categories: arXiv_CV
tags: arXiv_CV Inference
author: Ayan Chakrabarti
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new method for blind motion deblurring that uses a neural network trained to compute estimates of sharp image patches from observations that are blurred by an unknown motion kernel. Instead of regressing directly to patch intensities, this network learns to predict the complex Fourier coefficients of a deconvolution filter to be applied to the input patch for restoration. For inference, we apply the network independently to all overlapping patches in the observed image, and average its outputs to form an initial estimate of the sharp image. We then explicitly estimate a single global blur kernel by relating this estimate to the observed image, and finally perform non-blind deconvolution with this kernel. Our method exhibits accuracy and robustness close to state-of-the-art iterative methods, while being much faster when parallelized on GPU hardware.

##### Abstract (translated by Google)
我们提出了一种盲运动去模糊的新方法，该方法使用经过训练的神经网络来计算来自未知运动核心模糊的观察的清晰图像块的估计。该网络不是直接回归补丁强度，而是学习去预测复卷滤波器的复数傅立叶系数，以应用于输入补丁以进行恢复。为了进行推理，我们将网络独立地应用于所观察图像中的所有重叠小片，并且将其输出平均以形成锐利图像的初始估计。然后，我们通过将这个估计与观察到的图像相关联来明确地估计单个全局模糊核，并且最终用该内核执行非盲去卷积。我们的方法展现了接近最先进的迭代方法的准确性和鲁棒性，而在GPU硬件上并行化时速度更快。

##### URL
[https://arxiv.org/abs/1603.04771](https://arxiv.org/abs/1603.04771)

##### PDF
[https://arxiv.org/pdf/1603.04771](https://arxiv.org/pdf/1603.04771)

