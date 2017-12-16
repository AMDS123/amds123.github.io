---
layout: post
title: "FFDNet: Toward a Fast and Flexible Solution for CNN based Image Denoising"
date: 2017-10-11 12:04:37
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Inference
author: Kai Zhang, Wangmeng Zuo, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the fast inference and good performance, discriminative learning methods have been widely studied in image denoising. However, these methods mostly learn a specific model for each noise level, and require multiple models for denoising images with different noise levels. They also lack flexibility to deal with spatially variant noise, limiting their applications in practical denoising. To address these issues, we present a fast and flexible denoising convolutional neural network, namely FFDNet, with a tunable noise level map as the input. The proposed FFDNet works on downsampled sub-images to speed up the inference, and adopts orthogonal regularization to enhance the generalization ability. In contrast to the existing discriminative denoisers, FFDNet enjoys several desirable properties, including (i) the ability to handle a wide range of noise levels (i.e., [0, 75]) effectively with a single network, (ii) the ability to remove spatially variant noise by specifying a non-uniform noise level map, and (iii) faster speed than benchmark BM3D even on CPU without sacrificing denoising performance. Extensive experiments on synthetic and real noisy images are conducted to evaluate FFDNet in comparison with state-of-the-art denoisers. The results show that FFDNet is effective and efficient, making it highly attractive for practical denoising applications.

##### Abstract (translated by Google)
由于快速推理和良好的性能，在图像去噪方面，有鉴别性的学习方法已被广泛研究。然而，这些方法主要是针对每个噪声水平学习一个特定的模型，并且需要多个模型来对具有不同噪声水平的图像进行去噪。他们也缺乏处理空间变异噪声的灵活性，限制了其在实际去噪中的应用。为了解决这些问题，我们提出了一个快速而灵活的去噪卷积神经网络，即FFDNet，以可调的噪声水平图作为输入。所提出的FFDNet工作在下采样子图像加速推理，并采用正交正则化，以提高泛化能力。与现有的识别性分子不同，FFDNet具有一些理想的特性，包括（i）能够有效地处理各种各样的噪声水平（即[0，75]），（ii）能够去除通过指定非均匀的噪声水平图来产生空间变化的噪声，以及（iii）即使在CPU上也比基准BM3D更快的速度而不牺牲去噪性能。对于合成的和真实的噪声图像进行了大量的实验来评估FFDNet与最先进的分子识别器相比较。结果表明，FFDNet是有效和高效的，使其对实际的去噪应用具有高度的吸引力。

##### URL
[https://arxiv.org/abs/1710.04026](https://arxiv.org/abs/1710.04026)

##### PDF
[https://arxiv.org/pdf/1710.04026](https://arxiv.org/pdf/1710.04026)

