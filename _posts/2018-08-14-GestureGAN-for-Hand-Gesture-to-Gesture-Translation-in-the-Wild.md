---
layout: post
title: "GestureGAN for Hand Gesture-to-Gesture Translation in the Wild"
date: 2018-08-14 18:57:22
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Hao Tang, Wei Wang, Dan Xu, Yan Yan, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
Hand gesture-to-gesture translation in the wild is a challenging task since hand gestures can have arbitrary poses, sizes, locations and self-occlusions. Therefore, this task requires a high-level understanding of the mapping between the input source gesture and the output target gesture. To tackle this problem, we propose a novel hand Gesture Generative Adversarial Network (GestureGAN). GestureGAN consists of a single generator $G$ and a discriminator $D$, which takes as input a conditional hand image and a target hand skeleton image. GestureGAN utilizes the hand skeleton information explicitly, and learns the gesture-to-gesture mapping through two novel losses, the color loss and the cycle-consistency loss. The proposed color loss handles the issue of "channel pollution" while back-propagating the gradients. In addition, we present the Fr\'echet ResNet Distance (FRD) to evaluate the quality of generated images. Extensive experiments on two widely used benchmark datasets demonstrate that the proposed GestureGAN achieves state-of-the-art performance on the unconstrained hand gesture-to-gesture translation task. Meanwhile, the generated images are in high-quality and are photo-realistic, allowing them to be used as data augmentation to improve the performance of a hand gesture classifier. Our model and code are available at https://github.com/Ha0Tang/GestureGAN.

##### Abstract (translated by Google)
野外手势到手势的翻译是一项具有挑战性的任务，因为手势可以具有任意姿势，大小，位置和自我遮挡。因此，该任务需要高度理解输入源手势和输出目标手势之间的映射。为了解决这个问题，我们提出了一种新颖的手势生成对抗网络（GestureGAN）。 GestureGAN由单个生成器$ G $和一个鉴别器$ D $组成，它将条件手图像和目标手骨架图像作为输入。 GestureGAN明确地利用手骨架信息，并通过两个新的损失，颜色损失和周期一致性损失来学习手势到手势的映射。建议的颜色损失处理“通道污染”的问题，同时反向传播梯度。此外，我们还提供了Fr \'echet ResNet Distance（FRD）来评估生成图像的质量。对两个广泛使用的基准数据集进行的大量实验表明，所提出的GestureGAN在无约束的手势到手势转换任务上实现了最先进的性能。同时，生成的图像是高质量的并且是照片般逼真的，允许它们用作数据增强以改善手势分类器的性能。我们的模型和代码可在https://github.com/Ha0Tang/GestureGAN获得。

##### URL
[http://arxiv.org/abs/1808.04859](http://arxiv.org/abs/1808.04859)

##### PDF
[http://arxiv.org/pdf/1808.04859](http://arxiv.org/pdf/1808.04859)

