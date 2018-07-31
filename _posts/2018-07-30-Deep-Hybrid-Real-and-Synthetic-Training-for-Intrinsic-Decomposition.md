---
layout: post
title: "Deep Hybrid Real and Synthetic Training for Intrinsic Decomposition"
date: 2018-07-30 08:25:54
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Sai Bi, Nima Khademi Kalantari, Ravi Ramamoorthi
mathjax: true
---

* content
{:toc}

##### Abstract
Intrinsic image decomposition is the process of separating the reflectance and shading layers of an image, which is a challenging and underdetermined problem. In this paper, we propose to systematically address this problem using a deep convolutional neural network (CNN). Although deep learning (DL) has been recently used to handle this application, the current DL methods train the network only on synthetic images as obtaining ground truth reflectance and shading for real images is difficult. Therefore, these methods fail to produce reasonable results on real images and often perform worse than the non-DL techniques. We overcome this limitation by proposing a novel hybrid approach to train our network on both synthetic and real images. Specifically, in addition to directly supervising the network using synthetic images, we train the network by enforcing it to produce the same reflectance for a pair of images of the same real-world scene with different illuminations. Furthermore, we improve the results by incorporating a bilateral solver layer into our system during both training and test stages. Experimental results show that our approach produces better results than the state-of-the-art DL and non-DL methods on various synthetic and real datasets both visually and numerically.

##### Abstract (translated by Google)
固有图像分解是分离图像的反射层和阴影层的过程，这是一个具有挑战性和未确定的问题。在本文中，我们建议使用深度卷积神经网络（CNN）系统地解决这个问题。尽管最近已经使用深度学习（DL）来处理该应用，但是当前的DL方法仅在合成图像上训练网络，因为获得地面实况反射并且对于真实图像的阴影是困难的。因此，这些方法不能在真实图像上产生合理的结果，并且通常比非DL技术表现更差。我们通过提出一种新颖的混合方法来克服这一限制，以便在合成和真实图像上训练我们的网络。具体地，除了使用合成图像直接监督网络之外，我们通过强制执行网络来为具有不同照明的相同真实世界场景的一对图像产生相同的反射率来训练网络。此外，我们通过在训练和测试阶段将双边求解器层纳入我们的系统来改善结果。实验结果表明，我们的方法在视觉和数字上对各种合成和真实数据集产生比最先进的DL和非DL方法更好的结果。

##### URL
[http://arxiv.org/abs/1807.11226](http://arxiv.org/abs/1807.11226)

##### PDF
[http://arxiv.org/pdf/1807.11226](http://arxiv.org/pdf/1807.11226)

