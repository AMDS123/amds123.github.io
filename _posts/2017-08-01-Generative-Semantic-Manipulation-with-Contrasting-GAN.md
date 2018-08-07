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
生成对抗网络（GAN）最近在成对/不成对的图像到图像转换方面取得了显着的改进，例如照片$ \ rightarrow $ sketch和艺术家绘画风格转移。然而，现有模型仅能够传送低级信息（例如颜色或纹理变化），但是不能编辑对象的高级语义含义（例如，几何结构或内容）。另一方面，虽然一些研究可以在给定类标签或标题的情况下合成引人注目的真实世界图像，但它们不能对任意形状或结构进行条件限制，这在很大程度上限制了它们的应用场景和模型结果的解释能力。在这项工作中，我们专注于一个更具挑战性的语义操作任务，旨在修改对象的语义，同时保留自己的特征（例如视点和形状），如牛$ \ rightarrow $ sheep，motor $ \ rightarrow $自行车，猫$ \ rightarrow $ dog。为了解决如此大的语义变化，我们引入了一种对比的GAN（对比度GAN）和一种新颖的对抗性对比目标。我们的对抗性对比目标不是像以前的GAN那样直接使合成样本接近目标数据，而是优化样本之间的距离比较，即，在语义上强制操纵数据更接近目标类别的实际数据而不是输入数据。配备了新的对比目标，提出了一种新颖的掩模条件对比-GAN架构，以实现具有对象语义变化的图像背景。在ImageNet和MSCOCO数据集上的几个语义操作任务的实验表明，我们的对比GAN相对于其他条件GAN可以获得相当大的性能提升。定量结果进一步证明了我们的模型在生成具有高视觉保真度和合理的对象语义的操纵结果方面的优越性。

##### URL
[https://arxiv.org/abs/1708.00315](https://arxiv.org/abs/1708.00315)

##### PDF
[https://arxiv.org/pdf/1708.00315](https://arxiv.org/pdf/1708.00315)

