---
layout: post
title: "TV-GAN: Generative Adversarial Network Based Thermal to Visible Face Recognition"
date: 2017-12-07 07:06:39
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Face Recognition Face_Recognition
author: Teng Zhang, Arnold Wiliem, Siqi Yang, Brian C. Lovell
mathjax: true
---

* content
{:toc}

##### Abstract
This work tackles the face recognition task on images captured using thermal camera sensors which can operate in the non-light environment. While it can greatly increase the scope and benefits of the current security surveillance systems, performing such a task using thermal images is a challenging problem compared to face recognition task in the Visible Light Domain (VLD). This is partly due to the much smaller amount number of thermal imagery data collected compared to the VLD data. Unfortunately, direct application of the existing very strong face recognition models trained using VLD data into the thermal imagery data will not produce a satisfactory performance. This is due to the existence of the domain gap between the thermal and VLD images. To this end, we propose a Thermal-to-Visible Generative Adversarial Network (TV-GAN) that is able to transform thermal face images into their corresponding VLD images whilst maintaining identity information which is sufficient enough for the existing VLD face recognition models to perform recognition. Some examples are presented in Figure 1. Unlike the previous methods, our proposed TV-GAN uses an explicit closed-set face recognition loss to regularize the discriminator network training. This information will then be conveyed into the generator network in the forms of gradient loss. In the experiment, we show that by using this additional explicit regularization for the discriminator network, the TV-GAN is able to preserve more identity information when translating a thermal image of a person which is not seen before by the TV-GAN.

##### Abstract (translated by Google)
这项工作解决了使用可在非光照环境下工作的热照相机传感器捕获的图像上的人脸识别任务。虽然可以大大增加当前安全监视系统的范围和优势，但与可见光域（VLD）中的人脸识别任务相比，使用热图像执行这样的任务是一个具有挑战性的问题。这部分是由于与VLD数据相比所收集的热成像数据数量少得多。不幸的是，将现有的使用VLD数据训练的非常强大的人脸识别模型直接应用于热成像数据将不会产生令人满意的性能。这是由于热图像和VLD图像之间存在域差距的缘故。为此，我们提出一种能够将热人脸图像转换为其相应的VLD图像的热到可见生成对抗网络（TV-GAN），同时维持足以使现有的VLD人脸识别模型执行的身份信息承认。一些例子如图1所示。与以前的方法不同，我们提出的TV-GAN使用明确的闭集面部识别损失来规范鉴别器网络训练。这些信息将以梯度损失的形式传送到发电机网络。在实验中，我们表明，通过对鉴别器网络使用这个附加的显式正则化，TV-GAN能够在翻译TV-GAN之前没有看到的人的热图像时保存更多的身份信息。

##### URL
[http://arxiv.org/abs/1712.02514](http://arxiv.org/abs/1712.02514)

##### PDF
[http://arxiv.org/pdf/1712.02514](http://arxiv.org/pdf/1712.02514)

