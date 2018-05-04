---
layout: post
title: "IterGANs: Iterative GANs to Learn and Control 3D Object Transformation"
date: 2018-04-16 13:08:58
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Ysbrand Galama, Thomas Mensink
mathjax: true
---

* content
{:toc}

##### Abstract
We are interested in learning visual representations which allow for 3D manipulations of visual objects based on a single 2D image. We cast this into an image-to-image transformation task, and propose Iterative Generative Adversarial Networks (IterGANs) which iteratively transform an input image into an output image. Our models learn a visual representation that can be used for objects seen in training, but also for never seen objects. Since object manipulation requires a full understanding of the geometry and appearance of the object, our IterGANs learn an implicit 3D model and a full appearance model of the object, which are both inferred from a single (test) image. Two advantages of IterGANs are that the intermediate generated images can be used for an additional supervision signal, even in an unsupervised fashion, and that the number of iterations can be used as a control signal to steer the transformation. Experiments on rotated objects and scenes show how IterGANs help with the generation process.

##### Abstract (translated by Google)
我们对学习视觉表示感兴趣，它允许基于单个2D图像对视觉对象进行3D操作。我们将其转换为图像到图像的转换任务，并提出将输入图像迭代转换为输出图像的迭代生成对抗网络（IterGan）。我们的模型学习可用于训练中看到的物体的视觉表示，也可用于未曾见过的物体。由于对象操作需要对对象的几何形状和外观的全面理解，因此我们的IterGAN可以从单个（测试）图像中推断出隐式3D模型和对象的完整外观模型。 IterGAN的两个优点是，即使在无监督的方式下，中间生成的图像也可以用于额外的监督信号，并且迭代次数可以用作控制信号来控制变换。旋转物体和场景的实验显示了IterGAN如何帮助生成过程。

##### URL
[https://arxiv.org/abs/1804.05651](https://arxiv.org/abs/1804.05651)

##### PDF
[https://arxiv.org/pdf/1804.05651](https://arxiv.org/pdf/1804.05651)

