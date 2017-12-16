---
layout: post
title: "WaterGAN: Unsupervised Generative Network to Enable Real-time Color Correction of Monocular Underwater Images"
date: 2017-10-26 14:46:14
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Survey Deep_Learning
author: Jie Li, Katherine A. Skinner, Ryan M. Eustice, Matthew Johnson-Roberson
mathjax: true
---

* content
{:toc}

##### Abstract
This paper reports on WaterGAN, a generative adversarial network (GAN) for generating realistic underwater images from in-air image and depth pairings in an unsupervised pipeline used for color correction of monocular underwater images. Cameras onboard autonomous and remotely operated vehicles can capture high resolution images to map the seafloor, however, underwater image formation is subject to the complex process of light propagation through the water column. The raw images retrieved are characteristically different than images taken in air due to effects such as absorption and scattering, which cause attenuation of light at different rates for different wavelengths. While this physical process is well described theoretically, the model depends on many parameters intrinsic to the water column as well as the objects in the scene. These factors make recovery of these parameters difficult without simplifying assumptions or field calibration, hence, restoration of underwater images is a non-trivial problem. Deep learning has demonstrated great success in modeling complex nonlinear systems but requires a large amount of training data, which is difficult to compile in deep sea environments. Using WaterGAN, we generate a large training dataset of paired imagery, both raw underwater and true color in-air, as well as depth data. This data serves as input to a novel end-to-end network for color correction of monocular underwater images. Due to the depth-dependent water column effects inherent to underwater environments, we show that our end-to-end network implicitly learns a coarse depth estimate of the underwater scene from monocular underwater images. Our proposed pipeline is validated with testing on real data collected from both a pure water tank and from underwater surveys in field testing. Source code is made publicly available with sample datasets and pretrained models.

##### Abstract (translated by Google)
本文报道了一种用于单目水下图像色彩校正的无监督管道中的水生图像和深度配对生成真实水下图像的生成对抗网络（GAN）WaterGAN。摄像机上的自主和遥控车辆可以捕捉高分辨率的图像来映射海底，然而，水下图像形成受光线在水柱中传播的复杂过程的影响。由于诸如吸收和散射之类的效应，检索到的原始图像在特征上不同于在空气中拍摄的图像，这导致不同波长的光以不同的速率衰减。虽然这个物理过程在理论上得到了很好的描述，但是模型依赖于水柱固有的许多参数以及场景中的物体。这些因素使得这些参数的恢复变得困难，而没有简化假设或现场校准，因此水下图像的恢复是一个不平凡的问题。深度学习在复杂的非线性系统建模方面已经取得了巨大的成功，但是需要大量的训练数据，在深海环境下难以编译。使用WaterGAN，我们可以生成大量的配对图像的训练数据集，包括原始的水下和空中真彩色以及深度数据。该数据用作用于单眼水下图像的颜色校正的新型端到端网络的输入。由于水下环境固有的深度依赖的水柱效应，我们显示我们的端到端网络隐式地从单眼水下图像学习水下场景的粗糙深度估计。我们提出的管道是通过对从纯水罐和实地测试水下调查中收集到的实际数据进行测试来验证的。源代码通过示例数据集和预训练模型公开可用。

##### URL
[https://arxiv.org/abs/1702.07392](https://arxiv.org/abs/1702.07392)

##### PDF
[https://arxiv.org/pdf/1702.07392](https://arxiv.org/pdf/1702.07392)

