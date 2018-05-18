---
layout: post
title: "RotDCF: Decomposition of Convolutional Filters for Rotation-Equivariant Deep Networks"
date: 2018-05-17 16:24:51
categories: arXiv_CV
tags: arXiv_CV CNN
author: Xiuyuan Cheng, Qiang Qiu, Robert Calderbank, Guillermo Sapiro
mathjax: true
---

* content
{:toc}

##### Abstract
Explicit encoding of group actions in deep features makes it possible for convolutional neural networks (CNNs) to handle global deformations of images, which is critical to success in many vision tasks. This paper proposes to decompose the convolutional filters over joint steerable bases across the space and the group geometry simultaneously, namely a rotation-equivariant CNN with decomposed convolutional filters (RotDCF). This decomposition facilitates computing the joint convolution, which is proved to be necessary for the group equivariance. It significantly reduces the model size and computational complexity while preserving performance, and truncation of the bases expansion serves implicitly to regularize the filters. On datasets involving in-plane and out-of-plane object rotations, RotDCF deep features demonstrate greater robustness and interpretability than regular CNNs. The stability of the equivariant representation to input variations is also proved theoretically under generic assumptions on the filters in the decomposed form. The RotDCF framework can be extended to groups other than rotations, providing a general approach which achieves both group equivariance and representation stability at a reduced model size.

##### Abstract (translated by Google)
深度特征中群组操作的显式编码使得卷积神经网络（CNN）能够处理图像的全局变形，这对于许多视觉任务的成功至关重要。本文提出同时分解空间和群几何上的联合可操纵基础上的卷积滤波器，即具有分解卷积滤波器（RotDCF）的旋转等变CNN。这种分解有助于计算联合卷积，这被证明是群变换的必要条件。它在保持性能的同时显着减少了模型大小和计算复杂度，并且基本扩展的截断隐式地用于正则化滤波器。在涉及平面内和平面外物体旋转的数据集上，RotDCF深度特征比常规CNN具有更强的鲁棒性和可解释性。等变表示对输入变化的稳定性也在理论上在分解形式的滤波器的一般假设下得到证明。 RotDCF框架可以扩展到旋转以外的组，从而提供了一种通用的方法，可以在缩小的模型大小下实现组等值变换和表示稳定性。

##### URL
[http://arxiv.org/abs/1805.06846](http://arxiv.org/abs/1805.06846)

##### PDF
[http://arxiv.org/pdf/1805.06846](http://arxiv.org/pdf/1805.06846)

