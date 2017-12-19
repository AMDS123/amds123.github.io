---
layout: post
title: "Fast and Accurate Poisson Denoising with Optimized Nonlinear Diffusion"
date: 2015-10-10 13:44:47
categories: arXiv_CV
tags: arXiv_CV
author: Wensen Feng, Yunjin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
The degradation of the acquired signal by Poisson noise is a common problem for various imaging applications, such as medical imaging, night vision and microscopy. Up to now, many state-of-the-art Poisson denoising techniques mainly concentrate on achieving utmost performance, with little consideration for the computation efficiency. Therefore, in this study we aim to propose an efficient Poisson denoising model with both high computational efficiency and recovery quality. To this end, we exploit the newly-developed trainable nonlinear reaction diffusion model which has proven an extremely fast image restoration approach with performance surpassing recent state-of-the-arts. We retrain the model parameters, including the linear filters and influence functions by taking into account the Poisson noise statistics, and end up with an optimized nonlinear diffusion model specialized for Poisson denoising. The trained model provides strongly competitive results against state-of-the-art approaches, meanwhile bearing the properties of simple structure and high efficiency. Furthermore, our proposed model comes along with an additional advantage, that the diffusion process is well-suited for parallel computation on GPUs. For images of size $512 \times 512$, our GPU implementation takes less than 0.1 seconds to produce state-of-the-art Poisson denoising performance.

##### Abstract (translated by Google)
泊松噪声对采集到的信号的退化是各种成像应用（如医学成像，夜视和显微术）的常见问题。到目前为止，许多先进的泊松去噪技术主要集中于实现最佳性能，而对计算效率的考虑很少。因此，在这项研究中，我们的目标是提出一个高效的计算效率和恢复质量的高效泊松去噪模型。为此，我们利用新开发的可训练的非线性反应扩散模型，该模型证明了一种性能超过最新技术水平的极其快速的图像恢复方法。我们通过考虑泊松噪声统计量重新训练模型参数，包括线性滤波器和影响函数，最后得到一个专门用于泊松去噪的非线性扩散模型。经过训练的模型与最先进的方法相比具有极强的竞争力，同时又具有结构简单，效率高的特点。此外，我们提出的模型带来了另一个优点，即扩散过程非常适合于GPU上的并行计算。对于尺寸为$ 512 \ times 512 $的图片，我们的GPU实现花费不到0.1秒的时间来产生最先进的泊松去噪性能。

##### URL
[https://arxiv.org/abs/1510.02930](https://arxiv.org/abs/1510.02930)

##### PDF
[https://arxiv.org/pdf/1510.02930](https://arxiv.org/pdf/1510.02930)

