---
layout: post
title: "Learning to Generate Images with Perceptual Similarity Metrics"
date: 2017-01-24 02:03:41
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Image_Generation CNN Image_Classification Classification
author: Jake Snell, Karl Ridgeway, Renjie Liao, Brett D. Roads, Michael C. Mozer, Richard S. Zemel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep networks are increasingly being applied to problems involving image synthesis, e.g., generating images from textual descriptions and reconstructing an input image from a compact representation. Supervised training of image-synthesis networks typically uses a pixel-wise loss (PL) to indicate the mismatch between a generated image and its corresponding target image. We propose instead to use a loss function that is better calibrated to human perceptual judgments of image quality: the multiscale structural-similarity score (MS-SSIM). Because MS-SSIM is differentiable, it is easily incorporated into gradient-descent learning. We compare the consequences of using MS-SSIM versus PL loss on training deterministic and stochastic autoencoders. For three different architectures, we collected human judgments of the quality of image reconstructions. Observers reliably prefer images synthesized by MS-SSIM-optimized models over those synthesized by PL-optimized models, for two distinct PL measures ($\ell_1$ and $\ell_2$ distances). We also explore the effect of training objective on image encoding and analyze conditions under which perceptually-optimized representations yield better performance on image classification. Finally, we demonstrate the superiority of perceptually-optimized networks for super-resolution imaging. Just as computer vision has advanced through the use of convolutional architectures that mimic the structure of the mammalian visual system, we argue that significant additional advances can be made in modeling images through the use of training objectives that are well aligned to characteristics of human perception.

##### Abstract (translated by Google)
深度网络越来越多地应用于涉及图像合成的问题，例如从文本描述中生成图像并且从紧凑表示重建输入图像。图像合成网络的监督训练通常使用逐像素损失（PL）来表示生成的图像与其对应的目标图像之间的不匹配。我们建议使用更好地校准人类感官判断图像质量的损失函数：多尺度结构相似性评分（MS-SSIM）。由于MS-SSIM是可区分的，所以很容易融入到渐变下降学习中。我们比较使用MS-SSIM和PL损失对训练确定性和随机自动编码器的后果。对于三种不同的架构，我们收集人类对图像重建质量的判断。对于两种不同的PL度量（$ \ ell_1 $和$ \ ell_2 $ distance），观察者可以更可靠地选择通过PL优化模型合成的MS-SSIM优化模型合成的图像。我们还探索了训练目标对图像编码的影响，并分析了感知优化表示在图像分类上产生更好性能的条件。最后，我们证明了超分辨率成像的感知优化网络的优越性。正如计算机视觉通过使用模仿哺乳动物视觉系统结构的卷积体系结构所取得的进展，我们认为，通过使用与人类感知特性完全一致的训练目标，可以在图像建模方面取得重大进展。

##### URL
[https://arxiv.org/abs/1511.06409](https://arxiv.org/abs/1511.06409)

##### PDF
[https://arxiv.org/pdf/1511.06409](https://arxiv.org/pdf/1511.06409)

