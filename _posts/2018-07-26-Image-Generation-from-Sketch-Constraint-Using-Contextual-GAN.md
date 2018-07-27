---
layout: post
title: "Image Generation from Sketch Constraint Using Contextual GAN"
date: 2018-07-26 03:01:01
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial GAN
author: Yongyi Lu, Shangzhe Wu, Yu-Wing Tai, Chi-Keung Tang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we investigate image generation guided by hand sketch. When the input sketch is badly drawn, the output of common image-to-image translation follows the input edges due to the hard condition imposed by the translation process. Instead, we propose to use sketch as weak constraint, where the output edges do not necessarily follow the input edges. We address this problem using a novel joint image completion approach, where the sketch provides the image context for completing, or generating the output image. We train a generated adversarial network, i.e, contextual GAN to learn the joint distribution of sketch and the corresponding image by using joint images. Our contextual GAN has several advantages. First, the simple joint image representation allows for simple and effective learning of joint distribution in the same image-sketch space, which avoids complicated issues in cross-domain learning. Second, while the output is related to its input overall, the generated features exhibit more freedom in appearance and do not strictly align with the input features as previous conditional GANs do. Third, from the joint image's point of view, image and sketch are of no difference, thus exactly the same deep joint image completion network can be used for image-to-sketch generation. Experiments evaluated on three different datasets show that our contextual GAN can generate more realistic images than state-of-the-art conditional GANs on challenging inputs and generalize well on common categories.

##### Abstract (translated by Google)
在本文中，我们研究手绘草图引导的图像生成。当输入草图绘制得很糟糕时，由于翻译过程施加的硬条件，常见的图像到图像平移的输出遵循输入边缘。相反，我们建议使用sketch作为弱约束，其中输出边缘不一定跟随输入边缘。我们使用新颖的联合图像完成方法解决了这个问题，其中草图提供了用于完成或生成输出图像的图像上下文。我们训练生成的对抗网络，即上下文GAN，通过使用联合图像来学习草图和相应图像的联合分布。我们的上下文GAN有几个优点。首先，简单的联合图像表示允许在相同的图像 - 草图空间中简单有效地学习联合分布，这避免了跨域学习中的复杂问题。其次，虽然输出与其整体输入相关，但生成的特征在外观上表现出更大的自由度，并且不像先前的条件GAN那样严格地与输入特征对齐。第三，从关节图像的角度来看，图像和草图没有区别，因此完全相同的深度关节图像完成网络可用于图像到草图的生成。在三个不同数据集上进行的实验评估表明，我们的上下文GAN可以生成比现有条件GAN更具有挑战性的输入更真实的图像，并且可以很好地概括常见类别。

##### URL
[http://arxiv.org/abs/1711.08972](http://arxiv.org/abs/1711.08972)

##### PDF
[http://arxiv.org/pdf/1711.08972](http://arxiv.org/pdf/1711.08972)

