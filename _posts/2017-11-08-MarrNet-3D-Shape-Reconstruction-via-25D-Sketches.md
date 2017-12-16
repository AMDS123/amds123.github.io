---
layout: post
title: "MarrNet: 3D Shape Reconstruction via 2.5D Sketches"
date: 2017-11-08 19:29:01
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Jiajun Wu, Yifan Wang, Tianfan Xue, Xingyuan Sun, William T Freeman, Joshua B Tenenbaum
mathjax: true
---

* content
{:toc}

##### Abstract
3D object reconstruction from a single image is a highly under-determined problem, requiring strong prior knowledge of plausible 3D shapes. This introduces challenges for learning-based approaches, as 3D object annotations are scarce in real images. Previous work chose to train on synthetic data with ground truth 3D information, but suffered from domain adaptation when tested on real data. In this work, we propose MarrNet, an end-to-end trainable model that sequentially estimates 2.5D sketches and 3D object shape. Our disentangled, two-step formulation has three advantages. First, compared to full 3D shape, 2.5D sketches are much easier to be recovered from a 2D image; models that recover 2.5D sketches are also more likely to transfer from synthetic to real data. Second, for 3D reconstruction from 2.5D sketches, systems can learn purely from synthetic data. This is because we can easily render realistic 2.5D sketches without modeling object appearance variations in real images, including lighting, texture, etc. This further relieves the domain adaptation problem. Third, we derive differentiable projective functions from 3D shape to 2.5D sketches; the framework is therefore end-to-end trainable on real images, requiring no human annotations. Our model achieves state-of-the-art performance on 3D shape reconstruction.

##### Abstract (translated by Google)
从单个图像重建3D对象是一个非常不确定的问题，需要关于合理的3D形状的强大的先验知识。这为基于学习的方法带来了挑战，因为3D对象注释在真实图像中很少。之前的工作选择了对具有地面真实3D信息的合成数据进行训练，但是在对真实数据进行测试时遭受了域适应。在这项工作中，我们提出了MarrNet，一个端到端的可训练模型，可以连续估计2.5D草图和3D物体形状。我们解开的，两步式的配方有三个优点。首先，与完整的3D形状相比，2.5D草图更容易从2D图像恢复;恢复2.5D草图的模型也更有可能从合成数据转换为真实数据。其次，从2.5D草图的三维重建，系统可以纯粹从合成数据学习。这是因为我们可以很容易地渲染逼真的2.5D草图，而不需要模拟实际图像中的对象外观变化，包括照明，纹理等。这进一步缓解了领域适应问题。第三，我们从三维形状到2.5D草图推导可微投影函数;因此该框架可以在实际图像上进行端到端的培训，不需要人工注释。我们的模型在三维形状重建上达到了最先进的性能。

##### URL
[https://arxiv.org/abs/1711.03129](https://arxiv.org/abs/1711.03129)

##### PDF
[https://arxiv.org/pdf/1711.03129](https://arxiv.org/pdf/1711.03129)

