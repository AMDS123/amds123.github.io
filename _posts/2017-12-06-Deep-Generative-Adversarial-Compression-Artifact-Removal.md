---
layout: post
title: "Deep Generative Adversarial Compression Artifact Removal"
date: 2017-12-06 18:38:21
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection GAN CNN Detection
author: Leonardo Galteri, Lorenzo Seidenari, Marco Bertini, Alberto Del Bimbo
mathjax: true
---

* content
{:toc}

##### Abstract
Compression artifacts arise in images whenever a lossy compression algorithm is applied. These artifacts eliminate details present in the original image, or add noise and small structures; because of these effects they make images less pleasant for the human eye, and may also lead to decreased performance of computer vision algorithms such as object detectors. To eliminate such artifacts, when decompressing an image, it is required to recover the original image from a disturbed version. To this end, we present a feed-forward fully convolutional residual network model trained using a generative adversarial framework. To provide a baseline, we show that our model can be also trained optimizing the Structural Similarity (SSIM), which is a better loss with respect to the simpler Mean Squared Error (MSE). Our GAN is able to produce images with more photorealistic details than MSE or SSIM based networks. Moreover we show that our approach can be used as a pre-processing step for object detection in case images are degraded by compression to a point that state-of-the art detectors fail. In this task, our GAN method obtains better performance than MSE or SSIM trained networks.

##### Abstract (translated by Google)
无论何时应用有损压缩算法，压缩伪影都会出现在图像中。这些伪影消除了原始图像中的细节，或者增加了噪音和小的结构;由于这些效应，使得人眼对图像不那么愉快，并且也可能导致诸如物体检测器的计算机视觉算法的性能下降。为了消除这种伪影，当解压缩图像时，需要从受干扰的版本恢复原始图像。为此，我们提出了一个使用生成对抗框架训练的前馈完全卷积残差网络模型。为了提供基线，我们证明我们的模型也可以被训练优化结构相似性（SSIM），这对于更简单的均方误差（MSE）来说是更好的损失。我们的GAN能够生成比MSE或SSIM网络更逼真的图像。此外，我们表明，我们的方法可以用作物体检测的预处理步骤，以防止图像因压缩而降级到现有技术检测器失效的程度。在这个任务中，我们的GAN方法比MSE或SSIM训练的网络获得更好的性能。

##### URL
[http://arxiv.org/abs/1704.02518](http://arxiv.org/abs/1704.02518)

##### PDF
[http://arxiv.org/pdf/1704.02518](http://arxiv.org/pdf/1704.02518)

