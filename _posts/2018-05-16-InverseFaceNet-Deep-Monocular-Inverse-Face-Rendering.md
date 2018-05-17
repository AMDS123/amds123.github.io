---
layout: post
title: "InverseFaceNet: Deep Monocular Inverse Face Rendering"
date: 2018-05-16 04:31:57
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Hyeongwoo Kim, Michael Zollh&#xf6;fer, Ayush Tewari, Justus Thies, Christian Richardt, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce InverseFaceNet, a deep convolutional inverse rendering framework for faces that jointly estimates facial pose, shape, expression, reflectance and illumination from a single input image. By estimating all parameters from just a single image, advanced editing possibilities on a single face image, such as appearance editing and relighting, become feasible in real time. Most previous learning-based face reconstruction approaches do not jointly recover all dimensions, or are severely limited in terms of visual quality. In contrast, we propose to recover high-quality facial pose, shape, expression, reflectance and illumination using a deep neural network that is trained using a large, synthetically created training corpus. Our approach builds on a novel loss function that measures model-space similarity directly in parameter space and significantly improves reconstruction accuracy. We further propose a self-supervised bootstrapping process in the network training loop, which iteratively updates the synthetic training corpus to better reflect the distribution of real-world imagery. We demonstrate that this strategy outperforms completely synthetically trained networks. Finally, we show high-quality reconstructions and compare our approach to several state-of-the-art approaches.

##### Abstract (translated by Google)
我们引入了InverseFaceNet，一种面向人脸的深度卷积逆向渲染框架，可共同估计来自单个输入图像的面部姿态，形状，表情，反射和照明。通过从单个图像中估计所有参数，单个人脸图像上的高级编辑功能（例如外观编辑和重新照明）可以实时实现。大多数先前的基于学习的人脸重建方法不能共同恢复所有维度，或者在视觉质量方面受到严重限制。相比之下，我们建议使用深度神经网络来恢复高质量的面部姿态，形状，表情，反射率和照度，该深度神经网络使用大型的，合成创建的训练语料库进行训练。我们的方法建立在新的损失函数上，它直接测量参数空间中的模型空间相似性，并显着提高重建准确性。我们在网络训练循环中进一步提出了一个自我监督的自举过程，它迭代地更新合成训练语料库以更好地反映真实世界图像的分布。我们证明，这种策略胜过完全综合训练的网络。最后，我们展示高质量的重建并将我们的方法与几种最先进的方法进行比较。

##### URL
[http://arxiv.org/abs/1703.10956](http://arxiv.org/abs/1703.10956)

##### PDF
[http://arxiv.org/pdf/1703.10956](http://arxiv.org/pdf/1703.10956)

