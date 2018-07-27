---
layout: post
title: "HiDDeN: Hiding Data With Deep Networks"
date: 2018-07-26 03:25:15
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Jiren Zhu, Russell Kaplan, Justin Johnson, Li Fei-Fei
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown that deep neural networks are highly sensitive to tiny perturbations of input images, giving rise to adversarial examples. Though this property is usually considered a weakness of learned models, we explore whether it can be beneficial. We find that neural networks can learn to use invisible perturbations to encode a rich amount of useful information. In fact, one can exploit this capability for the task of data hiding. We jointly train encoder and decoder networks, where given an input message and cover image, the encoder produces a visually indistinguishable encoded image, from which the decoder can recover the original message. We show that these encodings are competitive with existing data hiding algorithms, and further that they can be made robust to noise: our models learn to reconstruct hidden information in an encoded image despite the presence of Gaussian blurring, pixel-wise dropout, cropping, and JPEG compression. Even though JPEG is non-differentiable, we show that a robust model can be trained using differentiable approximations. Finally, we demonstrate that adversarial training improves the visual quality of encoded images.

##### Abstract (translated by Google)
最近的研究表明，深度神经网络对输入图像的微小扰动非常敏感，从而产生了对抗性的例子。虽然这个属性通常被认为是学习模型的弱点，但我们会探索它是否有益。我们发现神经网络可以学习使用不可见的扰动来编码大量有用的信息。事实上，人们可以利用这种能力来完成数据隐藏任务。我们联合训练编码器和解码器网络，在给定输入消息和封面图像的情况下，编码器产生视觉上无法区分的编码图像，解码器可以从中恢复原始消息。我们证明这些编码与现有的数据隐藏算法相比具有竞争力，而且它们可以对噪声具有鲁棒性：尽管存在高斯模糊，像素方式丢失，裁剪和JPEG压缩。尽管JPEG是不可微分的，但我们表明可以使用可微分近似来训练稳健模型。最后，我们证明了对抗训练可以提高编码图像的视觉质量。

##### URL
[http://arxiv.org/abs/1807.09937](http://arxiv.org/abs/1807.09937)

##### PDF
[http://arxiv.org/pdf/1807.09937](http://arxiv.org/pdf/1807.09937)

