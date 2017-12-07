---
layout: post
title: "FSRNet: End-to-End Learning Face Super-Resolution with Facial Priors"
date: 2017-11-29 06:47:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution Knowledge GAN Face Quantitative
author: Yu Chen, Ying Tai, Xiaoming Liu, Chunhua Shen, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Face Super-Resolution (SR) is a domain-specific super-resolution problem. The specific facial prior knowledge could be leveraged for better super-resolving face images. We present a novel deep end-to-end trainable Face Super-Resolution Network (FSRNet), which makes full use of the geometry prior, i.e., facial landmark heatmaps and parsing maps, to super-resolve very low-resolution (LR) face images without well-aligned requirement. Specifically, we first construct a coarse SR network to recover a coarse high-resolution (HR) image. Then, the coarse HR image is sent to two branches: a fine SR encoder and a prior information estimation network, which extracts the image features, and estimates landmark heatmaps/parsing maps respectively. Both image features and prior information are sent to a fine SR decoder to recover the HR image. To further generate realistic faces, we propose the Face Super-Resolution Generative Adversarial Network (FSRGAN) to incorporate the adversarial loss into FSRNet. Moreover, we introduce two related tasks, face alignment and parsing, as the new evaluation metrics for face SR, which address the inconsistency of classic metrics w.r.t. visual perception. Extensive benchmark experiments show that FSRNet and FSRGAN significantly outperforms state of the arts for very LR face SR, both quantitatively and qualitatively. Code will be made available upon publication.

##### Abstract (translated by Google)
面超分辨率（SR）是一个领域特定的超分辨率问题。可以利用特定的面部先验知识来更好地解析人脸图像。我们提出了一种新的深层端到端可训练的超分辨率网络（FSRNet），它充分利用了以前的几何特征，即面部地标热图和解析图，超分辨率极低分辨率（LR）图像没有完全一致的要求。具体来说，我们首先构造一个粗糙的SR网络来恢复粗糙的高分辨率（HR）图像。然后，将粗糙的HR图像发送到两个分支：精细SR编码器和提取图像特征的先验信息估计网络，并分别估计地标热图/解析图。图像特征和先验信息都被发送到精细SR解码器以恢复HR图像。为了进一步产生逼真的面孔，我们提出面对超分辨率生成对抗网络（FSRGAN），将对抗性损失纳入FSRNet。此外，我们引入了两个相关的任务，即面对齐和解析，作为面向SR的新的评估度量，其解决了经典度量w.r.t的不一致性问题。视觉感知。广泛的基准实验表明，FSRNet和FSRGAN在定量和定性方面均明显优于LR脸SR。代码将在发布后提供。

##### URL
[https://arxiv.org/abs/1711.10703](https://arxiv.org/abs/1711.10703)

##### PDF
[https://arxiv.org/pdf/1711.10703](https://arxiv.org/pdf/1711.10703)

