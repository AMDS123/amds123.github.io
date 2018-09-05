---
layout: post
title: "Unsupervised Image Super-Resolution using Cycle-in-Cycle Generative Adversarial Networks"
date: 2018-09-03 03:07:00
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN
author: Yuan Yuan, Siyuan Liu, Jiawei Zhang, Yongbing Zhang, Chao Dong, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the single image super-resolution problem in a more general case that the low-/high-resolution pairs and the down-sampling process are unavailable. Different from traditional super-resolution formulation, the low-resolution input is further degraded by noises and blurring. This complicated setting makes supervised learning and accurate kernel estimation impossible. To solve this problem, we resort to unsupervised learning without paired data, inspired by the recent successful image-to-image translation applications. With generative adversarial networks (GAN) as the basic component, we propose a Cycle-in-Cycle network structure to tackle the problem within three steps. First, the noisy and blurry input is mapped to a noise-free low-resolution space. Then the intermediate image is up-sampled with a pre-trained deep model. Finally, we fine-tune the two modules in an end-to-end manner to get the high-resolution output. Experiments on NTIRE2018 datasets demonstrate that the proposed unsupervised method achieves comparable results as the state-of-the-art supervised models.

##### Abstract (translated by Google)
我们在更一般的情况下考虑单图像超分辨率问题，即低/高分辨率对和下采样过程不可用。与传统的超分辨率配方不同，低分辨率输入因噪声和模糊而进一步降低。这种复杂的设置使得监督学习和准确的核估计变得不可能。为了解决这个问题，我们采用无监督学习而没有配对数据，受到最近成功的图像到图像翻译应用程序的启发。以生成对抗网络（GAN）为基本组成部分，我们提出了循环周期网络结构，以便在三个步骤内解决问题。首先，噪声和模糊输入被映射到无噪声的低分辨率空间。然后用预训练的深度模型对中间图像进行上采样。最后，我们以端到端的方式对这两个模块进行微调，以获得高分辨率输出。在NTIRE2018数据集上的实验表明，所提出的无监督方法获得了与最先进的监督模型相当的结果。

##### URL
[http://arxiv.org/abs/1809.00437](http://arxiv.org/abs/1809.00437)

##### PDF
[http://arxiv.org/pdf/1809.00437](http://arxiv.org/pdf/1809.00437)

