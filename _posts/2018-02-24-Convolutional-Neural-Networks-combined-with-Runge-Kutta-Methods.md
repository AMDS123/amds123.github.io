---
layout: post
title: "Convolutional Neural Networks combined with Runge-Kutta Methods"
date: 2018-02-24 10:31:24
categories: arXiv_AI
tags: arXiv_AI Knowledge CNN Image_Classification Classification
author: Mai Zhu, Chong Fu
mathjax: true
---

* content
{:toc}

##### Abstract
A convolutional neural network for image classification can be constructed following some mathematical ways since it models the ventral stream in visual cortex which is regarded as a multi-period dynamical system. In this paper, a new point of view is proposed for constructing network models as well as providing a direction to get inspiration or explanation for neural network. If each period in ventral stream was deemed to be a dynamical system with time as the independent variable, there should be a set of ordinary differential equations (ODEs) for this system. Runge-Kutta methods are common means to solve ODE. Thus, network model ought to be built using these methods. Moreover, convolutional networks could be employed to emulate the increments within every time-step. The model constructed in the above way is named Runge-Kutta Convolutional Neural Network (RKNet). According to this idea, Dense Convolutional Networks (DenseNets) and Residual Networks (ResNets) were varied to RKNets. To prove the feasibility of RKNets, these variants were verified on benchmark datasets, CIFAR and ImageNet. The experimental results show that the RKNets transformed from DenseNets gained similar or even higher parameter efficiency. The success of the experiments denotes that Runge-Kutta methods can be utilized to construct convolutional neural networks for image classification efficiently. Furthermore, the network models might be structured more rationally in the future basing on RKNet and priori knowledge.

##### Abstract (translated by Google)
用于图像分类的卷积神经网络可以按照一些数学方法构建，因为它将视觉皮层中的腹侧流模拟为多周期动力学系统。本文提出了一种新的观点来构建网络模型，并为神经网络的启发和解释提供了方向。如果腹侧流的每个周期被认为是一个以时间为自变量的动力系统，那么这个系统应该有一组常微分方程（ODE）。 Runge-Kutta方法是解决ODE的常用手段。因此，网络模型应该使用这些方法来构建。而且，可以采用卷积网络来模拟每个时间步长内的增量。以上述方式构建的模型被命名为Runge-Kutta卷积神经网络（RKNet）。根据这个想法，密集卷积网络（DenseNets）和剩余网络（ResNets）对RKNets有所不同。为了证明RKNets的可行性，在基准数据集CIFAR和ImageNet上验证了这些变体。实验结果表明，从DenseNets转换的RKNets获得了相似甚至更高的参数效率。实验的成功表明可以利用龙格 - 库塔方法有效地构建用于图像分类的卷积神经网络。此外，基于RKNet和先验知识，未来的网络模型可能会更合理地构建。

##### URL
[http://arxiv.org/abs/1802.08831](http://arxiv.org/abs/1802.08831)

##### PDF
[http://arxiv.org/pdf/1802.08831](http://arxiv.org/pdf/1802.08831)

