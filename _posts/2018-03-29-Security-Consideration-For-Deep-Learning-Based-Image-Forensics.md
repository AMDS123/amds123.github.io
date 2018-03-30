---
layout: post
title: "Security Consideration For Deep Learning-Based Image Forensics"
date: 2018-03-29 17:06:00
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Attention Deep_Learning
author: Wei Zhao, Pengpeng Yang, Rongrong Ni, Yao Zhao, Haorui Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, image forensics community has paied attention to the research on the design of effective algorithms based on deep learning technology and facts proved that combining the domain knowledge of image forensics and deep learning would achieve more robust and better performance than the traditional schemes. Instead of improving it, in this paper, the safety of deep learning based methods in the field of image forensics is taken into account. To the best of our knowledge, this is a first work focusing on this topic. Specifically, we experimentally find that the method using deep learning would fail when adding the slight noise into the images (adversarial images). Furthermore, two kinds of strategys are proposed to enforce security of deep learning-based method. Firstly, an extra penalty term to the loss function is added, which is referred to the 2-norm of the gradient of the loss with respect to the input images, and then an novel training method are adopt to train the model by fusing the normal and adversarial images. Experimental results show that the proposed algorithm can achieve good performance even in the case of adversarial images and provide a safety consideration for deep learning-based image forensics

##### Abstract (translated by Google)
近年来，图像取证界对基于深度学习技术的有效算法设计研究备受关注，事实证明，将图像取证领域知识与深度学习相结合可以实现比传统方案更强大，更好的性能。本文没有改进它，而是考虑了基于深度学习的图像取证领域方法的安全性。据我们所知，这是关于这个主题的第一项工作。具体来说，我们通过实验发现，在图像中添加轻微噪声（对抗图像）时，使用深度学习的方法会失败。此外，还提出了两种策略来强化深度学习方法的安全性。首先对损失函数加入一个额外的惩罚项，称之为损失梯度的相对于输入图像的2-范数，然后采用新颖的训练方法对该模型进行训练，融合法线和敌对图片。实验结果表明，所提出的算法即使在对抗图像的情况下也可以实现良好的性能，并且为基于深度学习的图像取证提供安全考虑

##### URL
[http://arxiv.org/abs/1803.11157](http://arxiv.org/abs/1803.11157)

##### PDF
[http://arxiv.org/pdf/1803.11157](http://arxiv.org/pdf/1803.11157)

