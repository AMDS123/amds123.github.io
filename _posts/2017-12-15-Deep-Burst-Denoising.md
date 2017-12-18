---
layout: post
title: "Deep Burst Denoising"
date: 2017-12-15 18:55:16
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Image_Enhancement CNN
author: Cl&#xe9;ment Godard, Kevin Matzen, Matt Uyttendaele
mathjax: true
---

* content
{:toc}

##### Abstract
Noise is an inherent issue of low-light image capture, one which is exacerbated on mobile devices due to their narrow apertures and small sensors. One strategy for mitigating noise in a low-light situation is to increase the shutter time of the camera, thus allowing each photosite to integrate more light and decrease noise variance. However, there are two downsides of long exposures: (a) bright regions can exceed the sensor range, and (b) camera and scene motion will result in blurred images. Another way of gathering more light is to capture multiple short (thus noisy) frames in a "burst" and intelligently integrate the content, thus avoiding the above downsides. In this paper, we use the burst-capture strategy and implement the intelligent integration via a recurrent fully convolutional deep neural net (CNN). We build our novel, multiframe architecture to be a simple addition to any single frame denoising model, and design to handle an arbitrary number of noisy input frames. We show that it achieves state of the art denoising results on our burst dataset, improving on the best published multi-frame techniques, such as VBM4D and FlexISP. Finally, we explore other applications of image enhancement by integrating content from multiple frames and demonstrate that our DNN architecture generalizes well to image super-resolution.

##### Abstract (translated by Google)
噪声是低照度图像捕获的固有问题，由于其窄的孔径和小的传感器，在移动设备上恶化了噪声。在弱光情况下减轻噪声的一个策略是增加照相机的快门时间，从而使每个照片光照更多，减少噪音方差。然而，长时间曝光有两个缺点：（a）明亮区域可能超过传感器范围，（b）相机和场景运动会导致图像模糊。收集更多光线的另一种方式是在“突发”中捕捉多个短（因此噪声）的帧，并智能地整合内容，从而避免上述缺点。在本文中，我们使用突发捕获策略，并通过循环完全卷积深度神经网络（CNN）实现智能集成。我们构建了我们的新颖的多帧结构，使其成为任何单帧去噪模型的简单补充，并设计为处理任意数量的噪声输入帧。我们展示了它在我们的突发数据集上实现了最先进的去噪结果，改进了最佳公布的多帧技术，如VBM4D和FlexISP。最后，我们通过集成来自多个帧的内容来探索图像增强的其他应用，并且证明了我们的DNN体系结构很好地适用于图像超分辨率。

##### URL
[http://arxiv.org/abs/1712.05790](http://arxiv.org/abs/1712.05790)

##### PDF
[http://arxiv.org/pdf/1712.05790](http://arxiv.org/pdf/1712.05790)

