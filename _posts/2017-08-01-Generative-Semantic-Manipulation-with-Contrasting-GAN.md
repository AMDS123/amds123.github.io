---
layout: post
title: "Generative Semantic Manipulation with Contrasting GAN"
date: 2017-08-01 13:46:32
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Style_Transfer Caption Quantitative
author: Xiaodan Liang, Hao Zhang, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have recently achieved significant improvement on paired/unpaired image-to-image translation, such as photo$\rightarrow$ sketch and artist painting style transfer. However, existing models can only be capable of transferring the low-level information (e.g. color or texture changes), but fail to edit high-level semantic meanings (e.g., geometric structure or content) of objects. On the other hand, while some researches can synthesize compelling real-world images given a class label or caption, they cannot condition on arbitrary shapes or structures, which largely limits their application scenarios and interpretive capability of model results. In this work, we focus on a more challenging semantic manipulation task, which aims to modify the semantic meaning of an object while preserving its own characteristics (e.g. viewpoints and shapes), such as cow$\rightarrow$sheep, motor$\rightarrow$ bicycle, cat$\rightarrow$dog. To tackle such large semantic changes, we introduce a contrasting GAN (contrast-GAN) with a novel adversarial contrasting objective. Instead of directly making the synthesized samples close to target data as previous GANs did, our adversarial contrasting objective optimizes over the distance comparisons between samples, that is, enforcing the manipulated data be semantically closer to the real data with target category than the input data. Equipped with the new contrasting objective, a novel mask-conditional contrast-GAN architecture is proposed to enable disentangle image background with object semantic changes. Experiments on several semantic manipulation tasks on ImageNet and MSCOCO dataset show considerable performance gain by our contrast-GAN over other conditional GANs. Quantitative results further demonstrate the superiority of our model on generating manipulated results with high visual fidelity and reasonable object semantics.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.00315](https://arxiv.org/abs/1708.00315)

##### PDF
[https://arxiv.org/pdf/1708.00315](https://arxiv.org/pdf/1708.00315)

