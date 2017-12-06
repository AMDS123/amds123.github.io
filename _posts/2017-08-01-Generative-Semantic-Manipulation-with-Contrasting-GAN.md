---
layout: post
title: "Generative Semantic Manipulation with Contrasting GAN"
date: 2017-08-01 13:46:32
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Style_Transfer Caption
author: Xiaodan Liang, Hao Zhang, Eric P. Xing
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have recently achieved significant improvement on paired/unpaired image-to-image translation, such as photo$\rightarrow$ sketch and artist painting style transfer. However, existing models can only be capable of transferring the low-level information (e.g. color or texture changes), but fail to edit high-level semantic meanings (e.g., geometric structure or content) of objects. On the other hand, while some researches can synthesize compelling real-world images given a class label or caption, they cannot condition on arbitrary shapes or structures, which largely limits their application scenarios and interpretive capability of model results. In this work, we focus on a more challenging semantic manipulation task, which aims to modify the semantic meaning of an object while preserving its own characteristics (e.g. viewpoints and shapes), such as cow$\rightarrow$sheep, motor$\rightarrow$ bicycle, cat$\rightarrow$dog. To tackle such large semantic changes, we introduce a contrasting GAN (contrast-GAN) with a novel adversarial contrasting objective. Instead of directly making the synthesized samples close to target data as previous GANs did, our adversarial contrasting objective optimizes over the distance comparisons between samples, that is, enforcing the manipulated data be semantically closer to the real data with target category than the input data. Equipped with the new contrasting objective, a novel mask-conditional contrast-GAN architecture is proposed to enable disentangle image background with object semantic changes. Experiments on several semantic manipulation tasks on ImageNet and MSCOCO dataset show considerable performance gain by our contrast-GAN over other conditional GANs. Quantitative results further demonstrate the superiority of our model on generating manipulated results with high visual fidelity and reasonable object semantics.

##### Abstract (translated by Google)
生成敌对网络（GAN）最近在成对/不成对的图像到图像的翻译方面取得了显着的改进，如照片$右箭头草图和艺术家绘画风格转换。然而，现有模型只能够传递低级别信息（例如颜色或纹理变化），而不能编辑对象的高级语义含义（例如，几何结构或内容）。另一方面，虽然一些研究可以合成逼真的真实世界的图像给予一个类标签或标题，他们不能任意形状或结构条件，这在很大程度上限制了他们的应用场景和模型结果的解释能力。在这项工作中，我们专注于一个更具挑战性的语义操作任务，其目的是修改一个对象的语义含义，同时保留自己的特点（如观点和形状），如牛$ \ rightarrow $羊，马达$ \ rightarrow $自行车，猫$ \ rightarrow $狗。为了解决如此大的语义变化，我们引入了一个对比的GAN（contrast-GAN）和一个新颖的对抗对比目标。我们的敌对对比目标不是像以前的GAN那样直接将目标数据靠近目标数据，而是优化了样本之间的距离比较，也就是说，强制操纵的数据在语义上更接近目标类别与输入数据的真实数据。配合新的对比目标，提出了一种新的面具 - 条件对比度GAN体系结构，使得图像背景能够与对象语义变化相结合。在ImageNet和MSCOCO数据集上的几个语义操作任务的实验显示，我们的对比度GAN比其他条件GAN有显着的性能增益。定量结果进一步证明了我们的模型的优越性，以高视觉保真度和合理的对象语义生成操纵结果。

##### URL
[https://arxiv.org/abs/1708.00315](https://arxiv.org/abs/1708.00315)

