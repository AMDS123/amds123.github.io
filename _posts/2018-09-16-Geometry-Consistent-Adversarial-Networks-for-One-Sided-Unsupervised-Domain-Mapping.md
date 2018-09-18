---
layout: post
title: "Geometry-Consistent Adversarial Networks for One-Sided Unsupervised Domain Mapping"
date: 2018-09-16 10:42:29
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Huan Fu, Mingming Gong, Chaohui Wang, Kayhan Batmanghelich, Kun Zhang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised domain mapping aims at learning a function to translate domain X to Y (GXY : X to Y) in the absence of paired (X,Y) samples. Finding the optimal GXY without paired data is an ill-posed problem and hence appropriate constraints are required to obtain reasonable solutions. One of the most prominent constraint is cycle-consistency, which enforces the translated image by GXY to be translated back to the input image by an inverse mapping GYX. While cycle-consistency requires simultaneous training of GXY and GYX, recent methods have demonstrated one-sided domain mapping (only learn GXY) can be achieved by preserving pairwise distance between images before and after translation. Although cycle-consistency and distance preserving successfully constrain the solution space, they overlook the special properties of images that simple geometric transformations do not change the semantics of an image. Based on this special property, we develop a geometry-consistent adversarial network (GcGAN) which enables one-sided unsupervised domain mapping. Our GcGAN takes the original image and its counterpart image transformed by a predefined geometric transformation as inputs and generates two images in the new domain with the corresponding geometry-consistency constraint. The geometry-consistency constraint eliminates unreasonable solutions and produce more reliable solutions. Quantitative comparisons against baseline (GAN alone) and the state-of-the-art methods, including DistanceGAN and CycleGAN, demonstrate the superiority of our method in generating realistic images.

##### Abstract (translated by Google)
无监督域映射旨在学习在没有配对（X，Y）样本的情况下将域X转换为Y（GXY：X到Y）的函数。在没有配对数据的情况下找到最佳GXY是一个不适定的问题，因此需要适当的约束来获得合理的解决方案。最突出的约束之一是循环一致性，其通过GXY强制翻译的图像通过逆映射GYX被转换回输入图像。虽然循环一致性需要同时训练GXY和GYX，但最近的方法已经证明单侧域映射（仅学习GXY）可以通过保留翻译前后图像之间的成对距离来实现。尽管循环一致性和距离保持成功地约束了解空间，但它们忽略了图像的特殊属性，即简单的几何变换不会改变图像的语义。基于这一特殊属性，我们开发了一种几何一致的对抗网络（GcGAN），可实现单侧无监督域映射。我们的GcGAN将原始图像及其对应图像转换为预定义的几何变换作为输入，并在新域中生成具有相应几何一致性约束的两个图像。几何一致性约束消除了不合理的解决方案并产生了更可靠的解决方案。对基线的定量比较（仅GAN）和最先进的方法，包括DistanceGAN和CycleGAN，证明了我们的方法在生成逼真图像方面的优越性。

##### URL
[http://arxiv.org/abs/1809.05852](http://arxiv.org/abs/1809.05852)

##### PDF
[http://arxiv.org/pdf/1809.05852](http://arxiv.org/pdf/1809.05852)

