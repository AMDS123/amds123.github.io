---
layout: post
title: "Learning Non-local Image Diffusion for Image Denoising"
date: 2017-02-24 06:12:55
categories: arXiv_CV
tags: arXiv_CV
author: Peng Qiao, Yong Dou, Wensen Feng, Yunjin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Image diffusion plays a fundamental role for the task of image denoising. Recently proposed trainable nonlinear reaction diffusion (TNRD) model defines a simple but very effective framework for image denoising. However, as the TNRD model is a local model, the diffusion behavior of which is purely controlled by information of local patches, it is prone to create artifacts in the homogenous regions and over-smooth highly textured regions, especially in the case of strong noise levels. Meanwhile, it is widely known that the non-local self-similarity (NSS) prior stands as an effective image prior for image denoising, which has been widely exploited in many non-local methods. In this work, we are highly motivated to embed the NSS prior into the TNRD model to tackle its weaknesses. In order to preserve the expected property that end-to-end training is available, we exploit the NSS prior by a set of non-local filters, and derive our proposed trainable non-local reaction diffusion (TNLRD) model for image denoising. Together with the local filters and influence functions, the non-local filters are learned by employing loss-specific training. The experimental results show that the trained TNLRD model produces visually plausible recovered images with more textures and less artifacts, compared to its local versions. Moreover, the trained TNLRD model can achieve strongly competitive performance to recent state-of-the-art image denoising methods in terms of peak signal-to-noise ratio (PSNR) and structural similarity index (SSIM).

##### Abstract (translated by Google)
图像扩散是图像去噪任务的基础。最近提出的可训练非线性反应扩散（TNRD）模型为图像去噪定义了一个简单但非常有效的框架。然而，由于TNRD模型是局部模型，其扩散行为纯粹受局部斑块信息控制，容易在均匀区域产生伪影，并且过度平滑高度纹理区域，特别是在强噪声的情况下水平。同时，众所周知，非局部自相似（NSS）先验是图像去噪之前的有效图像，已经在很多非局部方法中得到了广泛的应用。在这项工作中，我们非常积极地将NSS先前纳入TNRD模型来解决其弱点。为了保留端到端训练的预期性质，我们先用一组非局部滤波器来开发NSS，并推导出我们提出的用于图像去噪的可训练非局部反应扩散（TNLRD）模型。结合本地过滤器和影响函数，非局部过滤器通过采用特定于损失的培训来学习。实验结果表明，与其本地版本相比，训练的TNLRD模型产生具有更多纹理和更少伪像的视觉合理的恢复图像。而且，经过训练的TNLRD模型在峰值信噪比（PSNR）和结构相似性指数（SSIM）方面可以实现与最新的最新图像去噪方法的强竞争性能。

##### URL
[https://arxiv.org/abs/1702.07472](https://arxiv.org/abs/1702.07472)

##### PDF
[https://arxiv.org/pdf/1702.07472](https://arxiv.org/pdf/1702.07472)

