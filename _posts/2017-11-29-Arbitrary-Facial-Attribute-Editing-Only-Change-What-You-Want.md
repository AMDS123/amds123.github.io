---
layout: post
title: "Arbitrary Facial Attribute Editing: Only Change What You Want"
date: 2017-11-29 04:50:31
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification
author: Zhenliang He, Wangmeng Zuo, Meina Kan, Shiguang Shan, Xilin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Facial attribute editing aims to modify either single or multiple attributes on a face image. Recently, the generative adversarial net (GAN) and the encoder-decoder architecture are usually incorporated to handle this task. The attribute editing can then be conducted by decoding the latent representation of the face image conditioned on the specified attributes. A few existing methods attempt to establish attribute-independent latent representation for arbitrarily changing the attributes. However, since the attributes portray the characteristics of the face image, the attribute-independent constraint on the latent representation is excessive. Such constraint may result in information loss and unexpected distortion on the generated images (e.g. over smoothing), especially for those identifiable attributes such as gender, race etc. Instead of imposing the attribute-independent constraint on the latent representation, we introduce an attribute classification constraint on the generated image, just requiring the correct change of the attributes. Meanwhile, reconstruction learning is introduced in order to guarantee the preservation of all other attribute-excluding details on the generated image, and adversarial learning is employed for visually realistic generation. Moreover, our method can be naturally extended to attribute intensity manipulation. Experiments on the CelebA dataset show that our method outperforms the state-of-the-arts on generating realistic attribute editing results with facial details well preserved.

##### Abstract (translated by Google)
面部属性编辑旨在修改面部图像上的单个或多个属性。最近，生成对抗网（GAN）和编码器 - 解码器架构通常被并入来处理这个任务。然后可以通过解码在指定属性上调节的面部图像的潜在表示来进行属性编辑。一些现有的方法试图建立任意改变属性的属性无关的潜在表示。然而，由于这些属性描绘了人脸图像的特征，所以潜在表示的与属性无关的约束是过度的。这样的约束可能导致信息丢失和所产生图像上意想不到的失真（例如，在平滑过程中），特别是对于诸如性别，种族等那些可识别的属性。不是对潜在表示施加与属性无关的约束，而是引入属性分类约束生成的图像，只需要正确更改属性。同时引入重构学习，保证所生成图像的所有其他属性排除细节的保留，并采用敌对学习进行视觉逼真生成。而且，我们的方法自然可以扩展到属性强度操作。 CelebA数据集上的实验表明，我们的方法在生成逼真的属性编辑结果方面的表现优于现有的属性编辑结果，并且保留了面部细节。

##### URL
[https://arxiv.org/abs/1711.10678](https://arxiv.org/abs/1711.10678)

##### PDF
[https://arxiv.org/pdf/1711.10678](https://arxiv.org/pdf/1711.10678)

