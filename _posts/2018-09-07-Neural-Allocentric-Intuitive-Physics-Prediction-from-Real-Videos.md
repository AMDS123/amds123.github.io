---
layout: post
title: "Neural Allocentric Intuitive Physics Prediction from Real Videos"
date: 2018-09-07 10:33:56
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Zhihua Wang, Stefano Rosa, Yishu Miao, Zihang Lai, Linhai Xie, Andrew Markham, Niki Trigoni
mathjax: true
---

* content
{:toc}

##### Abstract
Humans are able to make rich predictions about the future dynamics of physical objects from a glance. On the other hand, most existing computer vision approaches require strong assumptions about the underlying system, ad-hoc modeling, or annotated datasets, to carry out even simple predictions. To tackle this gap, we propose a new perspective on the problem of learning intuitive physics that is inspired by the spatial memory representation of objects and spaces in human brains, in particular the co-existence of egocentric and allocentric spatial representations. We present a generic framework that learns a layered representation of the physical world, using a cascade of invertible modules. In this framework, real images are first converted to a synthetic domain representation that reduces complexity arising from lighting and texture. Then, an allocentric viewpoint transformer removes viewpoint complexity by projecting images to a canonical view. Finally, a novel Recurrent Latent Variation Network (RLVN) architecture learns the dynamics of the objects interacting with the environment and predicts future motion, leveraging the availability of unlimited synthetic simulations. Predicted frames are then projected back to the original camera view and translated back to the real world domain. Experimental results show the ability of the framework to consistently and accurately predict several frames in the future and the ability to adapt to real images.

##### Abstract (translated by Google)
人类能够一目了然地对物理对象的未来动态做出丰富的预测。另一方面，大多数现有的计算机视觉方法需要对底层系统，临时建模或注释数据集进行强有力的假设，以进行简单的预测。为了解决这一差距，我们提出了一个关于学习直觉物理问题的新视角，这个视角受到人类大脑中物体和空间的空间记忆表现的启发，特别是自我中心和分配中心空间表征的共存。我们提出了一个通用框架，它使用一系列可逆模块来学习物理世界的分层表示。在此框架中，首先将真实图像转换为合成域表示，以降低由光照和纹理引起的复杂性。然后，分配中心视点变换器通过将图像投影到规范视图来消除视点复杂性。最后，一种新颖的递归潜变异网络（RLVN）架构学习了与环境相互作用的物体的动态，并预测未来的运动，利用无限合成模拟的可用性。然后将预测帧投射回原始相机视图并转换回现实世界域。实验结果表明，该框架能够持续准确地预测未来的几个帧以及适应真实图像的能力。

##### URL
[http://arxiv.org/abs/1809.03330](http://arxiv.org/abs/1809.03330)

##### PDF
[http://arxiv.org/pdf/1809.03330](http://arxiv.org/pdf/1809.03330)

