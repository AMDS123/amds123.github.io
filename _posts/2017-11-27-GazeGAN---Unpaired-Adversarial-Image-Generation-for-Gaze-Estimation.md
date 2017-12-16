---
layout: post
title: "GazeGAN - Unpaired Adversarial Image Generation for Gaze Estimation"
date: 2017-11-27 15:32:36
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Inference
author: Matan Sela, Pingmei Xu, Junfeng He, Vidhya Navalpakkam, Dmitry Lagun
mathjax: true
---

* content
{:toc}

##### Abstract
Recent research has demonstrated the ability to estimate gaze on mobile devices by performing inference on the image from the phone's front-facing camera, and without requiring specialized hardware. While this offers wide potential applications such as in human-computer interaction, medical diagnosis and accessibility (e.g., hands free gaze as input for patients with motor disorders), current methods are limited as they rely on collecting data from real users, which is a tedious and expensive process that is hard to scale across devices. There have been some attempts to synthesize eye region data using 3D models that can simulate various head poses and camera settings, however these lack in realism. In this paper, we improve upon a recently suggested method, and propose a generative adversarial framework to generate a large dataset of high resolution colorful images with high diversity (e.g., in subjects, head pose, camera settings) and realism, while simultaneously preserving the accuracy of gaze labels. The proposed approach operates on extended regions of the eye, and even completes missing parts of the image. Using this rich synthesized dataset, and without using any additional training data from real users, we demonstrate improvements over state-of-the-art for estimating 2D gaze position on mobile devices. We further demonstrate cross-device generalization of model performance, as well as improved robustness to diverse head pose, blur and distance.

##### Abstract (translated by Google)
最近的研究已经证明了通过对来自手机的前置摄像头的图像进行推断而不需要专门的硬件来估计移动设备上的注视的能力。虽然这提供了广泛的潜在应用，例如在人机交互，医学诊断和可访问性（例如作为对运动障碍患者的输入的免提注视）中，但是目前的方法是有限的，因为它们依赖于从真实用户收集数据，这是单调乏味且昂贵的流程难以跨设备进行扩展。已经有一些尝试使用3D模型来合成眼睛区域数据，这些模型可以模拟各种头部姿势和相机设置，但是这些缺乏真实性。在本文中，我们改进了最近提出的一种方法，并提出了一个生成对抗框架来生成高分辨率的高分辨率彩色图像（例如，在主题，头部姿势，相机设置）和真实性的大型数据集，同时保留注视标签的准确性。所提出的方法在扩展的眼睛区域上运行，甚至完成图像的缺失部分。使用这个丰富的综合数据集，并且不需要使用任何来自真实用户的额外训练数据，我们展示了在移动设备上估计2D注视位置的先进技术。我们进一步展示了模型性能的跨设备泛化，以及改善了对不同头部姿态，模糊和距离的鲁棒性。

##### URL
[https://arxiv.org/abs/1711.09767](https://arxiv.org/abs/1711.09767)

##### PDF
[https://arxiv.org/pdf/1711.09767](https://arxiv.org/pdf/1711.09767)

