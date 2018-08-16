---
layout: post
title: "cGANs with Projection Discriminator"
date: 2018-08-15 00:02:46
categories: arXiv_CV
tags: arXiv_CV Super_Resolution GAN
author: Takeru Miyato, Masanori Koyama
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel, projection based way to incorporate the conditional information into the discriminator of GANs that respects the role of the conditional information in the underlining probabilistic model. This approach is in contrast with most frameworks of conditional GANs used in application today, which use the conditional information by concatenating the (embedded) conditional vector to the feature vectors. With this modification, we were able to significantly improve the quality of the class conditional image generation on ILSVRC2012 (ImageNet) 1000-class image dataset from the current state-of-the-art result, and we achieved this with a single pair of a discriminator and a generator. We were also able to extend the application to super-resolution and succeeded in producing highly discriminative super-resolution images. This new structure also enabled high quality category transformation based on parametric functional transformation of conditional batch normalization layers in the generator.

##### Abstract (translated by Google)
我们提出了一种新颖的，基于投影的方法，将条件信息结合到GAN的鉴别器中，该鉴别器尊重条件信息在下划线概率模型中的作用。该方法与当今应用中使用的条件GAN的大多数框架形成对比，其通过将（嵌入的）条件向量连接到特征向量来使用条件信息。通过这种修改，我们能够从当前最先进的结果中显着提高ILSVRC2012（ImageNet）1000级图像数据集上的类条件图像生成的质量，我们用一对a来实现这一目标。鉴别器和发电机。我们还能够将应用程序扩展到超分辨率，并成功生成高度辨别力的超分辨率图像。这种新结构还支持基于生成器中条件批量标准化层的参数功能转换的高质量类别转换。

##### URL
[http://arxiv.org/abs/1802.05637](http://arxiv.org/abs/1802.05637)

##### PDF
[http://arxiv.org/pdf/1802.05637](http://arxiv.org/pdf/1802.05637)

