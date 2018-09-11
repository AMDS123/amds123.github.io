---
layout: post
title: "Deep MR Image Super-Resolution Using Structural Priors"
date: 2018-09-10 05:20:26
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Attention CNN Deep_Learning
author: Venkateswararao Cherukuri, Tiantong Guo, Steven J. Schiff, Vishal Monga
mathjax: true
---

* content
{:toc}

##### Abstract
High resolution magnetic resonance (MR) images are desired for accurate diagnostics. In practice, image resolution is restricted by factors like hardware, cost and processing constraints. Recently, deep learning methods have been shown to produce compelling state of the art results for image super-resolution. Paying particular attention to desired hi-resolution MR image structure, we propose a new regularized network that exploits image priors, namely a low-rank structure and a sharpness prior to enhance deep MR image superresolution. Our contributions are then incorporating these priors in an analytically tractable fashion in the learning of a convolutional neural network (CNN) that accomplishes the super-resolution task. This is particularly challenging for the low rank prior, since the rank is not a differentiable function of the image matrix (and hence the network parameters), an issue we address by pursuing differentiable approximations of the rank. Sharpness is emphasized by the variance of the Laplacian which we show can be implemented by a fixed {\em feedback} layer at the output of the network. Experiments performed on two publicly available MR brain image databases exhibit promising results particularly when training imagery is limited.

##### Abstract (translated by Google)
需要高分辨率磁共振（MR）图像以进行精确诊断。实际上，图像分辨率受硬件，成本和处理约束等因素的限制。最近，深度学习方法已经被证明可以产生令人信服的最先进的图像超分辨率结果。特别注意所需的高分辨率MR图像结构，我们提出了一种新的正则化网络，它利用图像先验，即在增强深度MR图像超分辨率之前的低秩结构和锐度。然后，我们的贡献是以分析易处理的方式将这些先验结合到学习卷积神经网络（CNN）中，以完成超分辨率任务。这对于低秩先验尤其具有挑战性，因为秩不是图像矩阵的可微函数（并且因此是网络参数），这是我们通过追求秩的可微近似来解决的问题。我们展示的拉普拉斯算子的方差强调了清晰度，可以通过网络输出端的固定{\ em反馈}层来实现。在两个公开可用的MR脑图像数据库上进行的实验表现出有希望的结果，特别是当训练图像有限时。

##### URL
[http://arxiv.org/abs/1809.03140](http://arxiv.org/abs/1809.03140)

##### PDF
[http://arxiv.org/pdf/1809.03140](http://arxiv.org/pdf/1809.03140)

