---
layout: post
title: "Adaptive Importance Learning for Improving Lightweight Image Super-resolution Network"
date: 2018-06-05 09:31:19
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Optimization
author: Lei Zhang, Peng Wang, Chunhua Shen, Lingqiao Liu, Wei Wei, Yanning Zhang, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved remarkable success in single image super-resolution (SISR). The computing and memory requirements of these methods have hindered their application to broad classes of real devices with limited computing power, however. One approach to this problem has been lightweight network architectures that bal- ance the super-resolution performance and the computation burden. In this study, we revisit this problem from an orthog- onal view, and propose a novel learning strategy to maxi- mize the pixel-wise fitting capacity of a given lightweight network architecture. Considering that the initial capacity of the lightweight network is very limited, we present an adaptive importance learning scheme for SISR that trains the network with an easy-to-complex paradigm by dynam- ically updating the importance of image pixels on the basis of the training loss. Specifically, we formulate the network training and the importance learning into a joint optimization problem. With a carefully designed importance penalty function, the importance of individual pixels can be gradu- ally increased through solving a convex optimization problem. The training process thus begins with pixels that are easy to reconstruct, and gradually proceeds to more complex pixels as fitting improves.

##### Abstract (translated by Google)
深度神经网络在单幅图像超分辨率（SISR）中取得了显着的成功。然而，这些方法的计算和存储要求阻碍了它们应用于具有有限计算能力的大量实际设备。解决这个问题的一种方法是轻量级的网络架构，以平衡超分辨率性能和计算负担。在这项研究中，我们从正视角度重新审视这个问题，并提出了一种新颖的学习策略，以最大限度地提高给定轻量级网络体系结构的逐像素拟合能力。考虑到轻量级网络的初始容量非常有限，我们提出了一种SISR的自适应重要学习方案，该方案通过动态更新图像像素在培训基础上的重要性，以易于复杂的范例训练网络失利。具体而言，我们将网络训练和重要性学习制定为联合优化问题。通过精心设计的重要性惩罚函数，可以通过求解凸优化问题逐渐增加单个像素的重要性。因此训练过程开始于容易重构的像素，并随着拟合改进逐渐进入更复杂的像素。

##### URL
[http://arxiv.org/abs/1806.01576](http://arxiv.org/abs/1806.01576)

##### PDF
[http://arxiv.org/pdf/1806.01576](http://arxiv.org/pdf/1806.01576)

