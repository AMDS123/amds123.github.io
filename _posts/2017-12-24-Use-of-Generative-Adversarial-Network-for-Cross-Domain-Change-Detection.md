---
layout: post
title: "Use of Generative Adversarial Network for Cross-Domain Change Detection"
date: 2017-12-24 02:23:57
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection GAN Detection Recognition
author: Yamaguchi Kousuke, Tanaka Kanji, Sugimoto Takuma
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of cross-domain change detection from a novel perspective of image-to-image translation. In general, change detection aims to identify interesting changes between a given query image and a reference image of the same scene taken at a different time. This problem becomes a challenging one when query and reference images involve different domains (e.g., time of the day, weather, and season) due to variations in object appearance and a limited amount of training examples. In this study, we address the above issue by leveraging a generative adversarial network (GAN). Our key concept is to use a limited amount of training data to train a GAN-based image translator that maps a reference image to a virtual image that cannot be discriminated from query domain images. This enables us to treat the cross-domain change detection task as an in-domain image comparison. This allows us to leverage the large body of literature on in-domain generic change detectors. In addition, we also consider the use of visual place recognition as a method for mining more appropriate reference images over the space of virtual images. Experiments validate efficacy of the proposed approach.

##### Abstract (translated by Google)
本文从图像到图像的翻译新视角探讨了跨域变化检测的问题。一般而言，变化检测旨在识别给定查询图像与在不同时间拍摄的同一场景的参考图像之间的有趣变化。当查询和参考图像由于对象外观的变化和有限的训练示例而涉及不同的领域（例如，一天中的时间，天气和季节）时，这个问题变成具有挑战性的问题。在这项研究中，我们通过利用生成对抗网络（GAN）来解决上述问题。我们的关键概念是使用有限的训练数据来训练基于GAN的图像转换器，将参考图像映射到无法与查询域图像区分的虚拟图像。这使我们能够将跨域更改检测任务视为域内图像比较。这使我们能够利用关于域内通用变化探测器的大量文献。另外，我们还考虑使用视觉位置识别作为在虚拟图像的空间上挖掘更合适的参考图像的方法。实验验证了所提出方法的有效性。

##### URL
[http://arxiv.org/abs/1712.08868](http://arxiv.org/abs/1712.08868)

##### PDF
[http://arxiv.org/pdf/1712.08868](http://arxiv.org/pdf/1712.08868)

