---
layout: post
title: "Sem-GAN: Semantically-Consistent Image-to-Image Translation"
date: 2018-07-12 02:55:19
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Semantic_Segmentation
author: Anoop Cherian, Alan Sullivan
mathjax: true
---

* content
{:toc}

##### Abstract
Unpaired image-to-image translation is the problem of mapping an image in the source domain to one in the target domain, without requiring corresponding image pairs. To ensure the translated images are realistically plausible, recent works, such as Cycle-GAN, demands this mapping to be invertible. While, this requirement demonstrates promising results when the domains are unimodal, its performance is unpredictable in a multi-modal scenario such as in an image segmentation task. This is because, invertibility does not necessarily enforce semantic correctness. To this end, we present a semantically-consistent GAN framework, dubbed Sem-GAN, in which the semantics are defined by the class identities of image segments in the source domain as produced by a semantic segmentation algorithm. Our proposed framework includes consistency constraints on the translation task that, together with the GAN loss and the cycle-constraints, enforces that the images when translated will inherit the appearances of the target domain, while (approximately) maintaining their identities from the source domain. We present experiments on several image-to-image translation tasks and demonstrate that Sem-GAN improves the quality of the translated images significantly, sometimes by more than 20% on the FCN score. Further, we show that semantic segmentation models, trained with synthetic images translated via Sem-GAN, leads to significantly better segmentation results than other variants.

##### Abstract (translated by Google)
不成对的图像到图像转换是将源域中的图像映射到目标域中的图像的问题，而不需要相应的图像对。为了确保翻译的图像真实可信，最近的工作，例如Cycle-GAN，要求这种映射是可逆的。然而，当域是单峰时，该要求表明了有希望的结果，其性能在多模态场景中是不可预测的，例如在图像分割任务中。这是因为，可逆性不一定强制语义正确性。为此，我们提出了一个语义一致的GAN框架，称为Sem-GAN，其中语义由源域中的图像片段的类标识定义，如由语义分割算法产生的。我们提出的框架包括对翻译任务的一致性约束，它与GAN损失和周期约束一起强制执行翻译后的图像将继承目标域的外观，同时（大致）保持其与源域的身份。我们提供了几个图像到图像翻译任务的实验，并证明Sem-GAN显着提高了翻译图像的质量，有时甚至超过了FCN得分的20％。此外，我们表明，通过Sem-GAN翻译的合成图像训练的语义分割模型导致比其他变体明显更好的分割结果。

##### URL
[http://arxiv.org/abs/1807.04409](http://arxiv.org/abs/1807.04409)

##### PDF
[http://arxiv.org/pdf/1807.04409](http://arxiv.org/pdf/1807.04409)

