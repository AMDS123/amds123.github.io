---
layout: post
title: "Monocular Semantic Occupancy Grid Mapping with Convolutional Variational Encoder-Decoder Networks"
date: 2018-09-11 07:39:12
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Chenyang Lu, Marinus Jacobus Gerardus van de Molengraft, Gijs Dubbelman
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we research and evaluate end-to-end learning of monocular semantic-metric occupancy grid mapping from weak binocular ground truth. The network learns to predict four classes, as well as a camera to bird's eye view mapping, which is shown to be more robust than using an inertial measurement unit (IMU) aided flat-plane assumption. At the core, it utilizes a variational encoder-decoder network that encodes the front-view visual information of the driving scene and subsequently decodes it into a 2-D top-view Cartesian coordinate system. It is demonstrated that the network learns to be invariant to pitch and roll perturbation of the camera view without requiring IMU data. The evaluations on Cityscapes show that our end-to-end learning of semantic-metric occupancy grids achieves 72.1% frequency weighted IoU, compared to 60.2% when using an IMU-aided flat-plane assumption. Furthermore, our network achieves real-time inference rates of approx. 35 Hertz for an input image with a resolution of 256x512 pixels and an output map with 64x64 occupancy grid cells using a Titan V GPU.

##### Abstract (translated by Google)
在这项工作中，我们研究和评估从弱双眼地面实况的单眼语义度量占用网格映射的端到端学习。网络学习预测四个类，以及相机到鸟瞰图的映射，这被证明比使用惯性测量单元（IMU）辅助平面假设更稳健。它的核心是利用变分编码器 - 解码器网络，该网络对驾驶场景的前视视觉信息进行编码，然后将其解码为二维俯视笛卡尔坐标系。证明了网络学习对于俯仰和滚动摄像机视图的扰动是不变的，而不需要IMU数据。对Cityscapes的评估表明，我们对语义度量占用网格的端到端学习实现了72.1％的频率加权IoU，而使用IMU辅助平面假设则为60.2％。此外，我们的网络实现了大约的实时推断率。 35赫兹用于输入图像，分辨率为256x512像素，输出图为64x64占用网格单元，使用Titan V GPU。

##### URL
[http://arxiv.org/abs/1804.02176](http://arxiv.org/abs/1804.02176)

##### PDF
[http://arxiv.org/pdf/1804.02176](http://arxiv.org/pdf/1804.02176)

