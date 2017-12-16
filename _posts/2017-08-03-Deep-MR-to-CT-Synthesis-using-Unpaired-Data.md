---
layout: post
title: "Deep MR to CT Synthesis using Unpaired Data"
date: 2017-08-03 14:18:43
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Deep_Learning Quantitative
author: Jelmer M. Wolterink, Anna M. Dinkla, Mark H.F. Savenije, Peter R. Seevinck, Cornelis A.T. van den Berg, Ivana Isgum
mathjax: true
---

* content
{:toc}

##### Abstract
MR-only radiotherapy treatment planning requires accurate MR-to-CT synthesis. Current deep learning methods for MR-to-CT synthesis depend on pairwise aligned MR and CT training images of the same patient. However, misalignment between paired images could lead to errors in synthesized CT images. To overcome this, we propose to train a generative adversarial network (GAN) with unpaired MR and CT images. A GAN consisting of two synthesis convolutional neural networks (CNNs) and two discriminator CNNs was trained with cycle consistency to transform 2D brain MR image slices into 2D brain CT image slices and vice versa. Brain MR and CT images of 24 patients were analyzed. A quantitative evaluation showed that the model was able to synthesize CT images that closely approximate reference CT images, and was able to outperform a GAN model trained with paired MR and CT images.

##### Abstract (translated by Google)
仅MR的放射治疗计划需要准确的MR-CT综合。 MR-to-CT综合的当前深度学习方法取决于同一患者的成对MR和CT训练图像。然而，配对图像之间的不对齐可能导致合成CT图像的错误。为了克服这个问题，我们提出训练一个具有不成对MR和CT图像的生成对抗网络（GAN）。将由两个合成卷积神经网络（CNN）和两个鉴别器CNN组成的GAN用循环一致性进行训练，以将2D脑MR图像切片转换成2D脑CT图像切片，反之亦然。分析24例患者的脑MR和CT图像。定量评估显示，该模型能够合成与参考CT图像非常近似的CT图像，并且能够胜过用成对的MR和CT图像训练的GAN模型。

##### URL
[https://arxiv.org/abs/1708.01155](https://arxiv.org/abs/1708.01155)

##### PDF
[https://arxiv.org/pdf/1708.01155](https://arxiv.org/pdf/1708.01155)

