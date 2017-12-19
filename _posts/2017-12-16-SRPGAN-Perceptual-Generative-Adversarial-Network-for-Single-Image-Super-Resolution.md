---
layout: post
title: "SRPGAN: Perceptual Generative Adversarial Network for Single Image Super Resolution"
date: 2017-12-16 09:52:43
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN CNN
author: Bingzhe Wu, Haodong Duan, Zhichao Liu, Guangyu Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Single image super resolution (SISR) is to reconstruct a high resolution image from a single low resolution image. The SISR task has been a very attractive research topic over the last two decades. In recent years, convolutional neural network (CNN) based models have achieved great performance on SISR task. Despite the breakthroughs achieved by using CNN models, there are still some problems remaining unsolved, such as how to recover high frequency details of high resolution images. Previous CNN based models always use a pixel wise loss, such as l2 loss. Although the high resolution images constructed by these models have high peak signal-to-noise ratio (PSNR), they often tend to be blurry and lack high-frequency details, especially at a large scaling factor. In this paper, we build a super resolution perceptual generative adversarial network (SRPGAN) framework for SISR tasks. In the framework, we propose a robust perceptual loss based on the discriminator of the built SRPGAN model. We use the Charbonnier loss function to build the content loss and combine it with the proposed perceptual loss and the adversarial loss. Compared with other state-of-the-art methods, our method has demonstrated great ability to construct images with sharp edges and rich details. We also evaluate our method on different benchmarks and compare it with previous CNN based methods. The results show that our method can achieve much higher structural similarity index (SSIM) scores on most of the benchmarks than the previous state-of-art methods.

##### Abstract (translated by Google)
单幅图像超分辨率（SISR）是从单个低分辨率图像重建高分辨率图像。 SISR任务在过去二十年中一直是一个非常有吸引力的研究课题。近年来，基于卷积神经网络（CNN）的模型在SISR任务上取得了很好的效果。尽管使用CNN模型取得了突破性的进展，但仍然存在一些尚未解决的问题，如如何恢复高分辨率图像的高频细节。以前的基于CNN的模型总是使用像素明智的损失，例如l2损失。尽管由这些模型构成的高分辨率图像具有较高的峰值信噪比（PSNR），但它们通常倾向于模糊且缺乏高频细节，尤其是在较大的比例因子下。在本文中，我们构建了SISR任务的超分辨感知生成对抗网络（SRPGAN）框架。在该框架下，我们基于构建的SRPGAN模型的鉴别器提出了鲁棒的感知损失。我们使用Charbonnier损失函数来建立内容损失，并将其与建议的感知损失和对抗性损失相结合。与其他最先进的方法相比，我们的方法已经显示出很强的构建边缘清晰和细节丰富的图像的能力。我们也评估我们的方法在不同的基准，并将其与以前的基于CNN的方法进行比较。结果表明，我们的方法可以达到比以前最先进的方法更高的结构相似性指数（SSIM）得分在大多数的基准。

##### URL
[http://arxiv.org/abs/1712.05927](http://arxiv.org/abs/1712.05927)

##### PDF
[http://arxiv.org/pdf/1712.05927](http://arxiv.org/pdf/1712.05927)

