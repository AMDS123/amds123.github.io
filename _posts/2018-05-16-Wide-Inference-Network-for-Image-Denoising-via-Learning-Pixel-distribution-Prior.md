---
layout: post
title: "Wide Inference Network for Image Denoising via Learning Pixel-distribution Prior"
date: 2018-05-16 13:40:34
categories: arXiv_CV
tags: arXiv_CV CNN Inference Quantitative
author: Peng Liu, Ruogu Fang
mathjax: true
---

* content
{:toc}

##### Abstract
We explore an innovative strategy for image denoising by using convolutional neural networks (CNN) to learn similar pixel-distribution features from noisy images. Many types of image noise follow a certain pixel-distribution in common, such as additive white Gaussian noise (AWGN). By increasing CNN's width with larger reception fields and more channels in each layer, CNNs can reveal the ability to extract more accurate pixel-distribution features. The key to our approach is a discovery that wider CNNs with more convolutions tend to learn the similar pixel-distribution features, which reveals a new strategy to solve low-level vision problems effectively that the inference mapping primarily relies on the priors behind the noise property instead of deeper CNNs with more stacked nonlinear layers. We evaluate our work, Wide inference Networks (WIN), on AWGN and demonstrate that by learning pixel-distribution features from images, WIN-based network consistently achieves significantly better performance than current state-of-the-art deep CNN-based methods in both quantitative and visual evaluations. \textit{Code and models are available at \url{https://github.com/cswin/WIN}}.

##### Abstract (translated by Google)
我们利用卷积神经网络（CNN）从噪声图像中学习相似的像素分布特征，探索一种创新的图像去噪策略。许多类型的图像噪声遵循某些共同的像素分布，例如加性高斯白噪声（AWGN）。通过在每一层中增加接收场和更多频道来增加CNN的宽度，CNN可以揭示提取更精确的像素分布特征的能力。我们的方法的关键在于发现具有更多卷积的更宽的CNN倾向于学习相似的像素分布特征，这揭示了有效解决低级别视觉问题的新策略，推理映射主要依赖于噪声特性背后的先验而不是具有更多堆叠非线性层的更深的CNN。我们在AWGN上评估了我们的工作，即宽泛推理网络（WIN），并证明通过从图像中学习像素分布特征，基于WIN的网络始终能够获得比当前最先进的基于CNN的深度CNN方法更好的性能定量和视觉评估。 \ textit {代码和模型位于\ url {https://github.com/cswin/WIN}}。

##### URL
[http://arxiv.org/abs/1707.05414](http://arxiv.org/abs/1707.05414)

##### PDF
[http://arxiv.org/e-print/1707.05414](http://arxiv.org/e-print/1707.05414)

