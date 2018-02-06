---
layout: post
title: "Image Synthesis in Multi-Contrast MRI with Conditional Generative Adversarial Networks"
date: 2018-02-05 00:10:12
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Salman Ul Hassan Dar, Mahmut Yurt, Levent Karacan, Aykut Erdem, Erkut Erdem, Tolga &#xc7;ukur
mathjax: true
---

* content
{:toc}

##### Abstract
Acquiring images of the same anatomy with multiple different contrasts increases the diversity of diagnostic information available in an MR exam. Yet, scan time limitations may prohibit acquisition of certain contrasts, and images for some contrast may be corrupted by noise and artifacts. In such cases, the ability to synthesize unacquired or corrupted contrasts from remaining contrasts can improve diagnostic utility. For multi-contrast synthesis, current methods learn a nonlinear intensity transformation between the source and target images, either via nonlinear regression or deterministic neural networks. These methods can in turn suffer from loss of high-spatial-frequency information in synthesized images. Here we propose a new approach for multi-contrast MRI synthesis based on conditional generative adversarial networks. The proposed approach preserves high-frequency details via an adversarial loss; and it offers enhanced synthesis performance via a pixel-wise loss for registered multi-contrast images and a cycle-consistency loss for unregistered images. Information from neighboring cross-sections are utilized to further improved synthesis quality. Demonstrations on T1- and T2-weighted images from healthy subjects and patients clearly indicate the superior performance of the proposed approach compared to previous state-of-the-art methods. Our synthesis approach can help improve quality and versatility of multi-contrast MRI exams without the need for prolonged examinations.

##### Abstract (translated by Google)
以多种不同的对比度采集相同解剖结构的图像增加了MR检查中可用的诊断信息的多样性。但是，扫描时间限制可能会阻止获取某些对比度，而某些对比度的图像可能会被噪声和伪像破坏。在这种情况下，从剩余对比度合成未获得或损坏对比的能力可以提高诊断效用。对于多对比度合成，目前的方法通过非线性回归或确定性神经网络学习源图像和目标图像之间的非线性强度变换。这些方法反过来可能会损失合成图像中的高空间频率信息。在此我们提出了一种基于条件生成对抗网络的多对比度MRI合成新方法。所提出的方法通过对抗性损失保持高频率细节;并且通过注册的多对比度图像的逐像素损失和未注册图像的周期一致性损失提供增强的综合性能。来自邻近横截面的信息被用来进一步提高合成质量。来自健康受试者和患者的T1加权像和T2加权像的证明清楚地表明，与先前的现有技术方法相比，所提出方法的优越性能。我们的综合方法可以帮助提高多对比MRI检查的质量和多功能性，而不需要长时间的检查。

##### URL
[http://arxiv.org/abs/1802.01221](http://arxiv.org/abs/1802.01221)

##### PDF
[http://arxiv.org/pdf/1802.01221](http://arxiv.org/pdf/1802.01221)

