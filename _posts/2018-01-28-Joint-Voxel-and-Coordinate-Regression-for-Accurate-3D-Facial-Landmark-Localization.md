---
layout: post
title: "Joint Voxel and Coordinate Regression for Accurate 3D Facial Landmark Localization"
date: 2018-01-28 15:34:16
categories: arXiv_CV
tags: arXiv_CV Face
author: Hongwen Zhang, Qi Li, Zhenan Sun
mathjax: true
---

* content
{:toc}

##### Abstract
3D face shape is more expressive and viewpoint-consistent than its 2D counterpart. However, 3D facial landmark localization in a single image is challenging due to the ambiguous nature of landmarks under 3D perspective. Existing approaches typically adopt a suboptimal two-step strategy, performing 2D landmark localization followed by depth estimation. In this paper, we propose the Joint Voxel and Coordinate Regression (JVCR) method for 3D facial landmark localization, addressing it more effectively in an end-to-end fashion. First, a compact volumetric representation is proposed to encode the per-voxel likelihood of positions being the 3D landmarks. The dimensionality of such a representation is fixed regardless of the number of target landmarks, so that the curse of dimensionality could be avoided. Then, a stacked hourglass network is adopted to estimate the volumetric representation from coarse to fine, followed by a 3D convolution network that takes the estimated volume as input and regresses 3D coordinates of the face shape. In this way, the 3D structural constraints between landmarks could be learned by the neural network in a more efficient manner. Moreover, the proposed pipeline enables end-to-end training and improves the robustness and accuracy of 3D facial landmark localization. The effectiveness of our approach is validated on the 3DFAW and AFLW2000-3D datasets. Experimental results show that the proposed method achieves state-of-the-art performance in comparison with existing methods.

##### Abstract (translated by Google)
三维人脸形状比二维人脸更具表现力和视点一致性。然而，由于三维视角下地标的模糊性，在单个图像中3D面部标志物定位是具有挑战性的。现有的方法通常采用次优的两步策略，执行2D地标定位，然后进行深度估计。在本文中，我们提出三维面部标志物定位的联合体素和坐标回归（JVCR）方法，以端对端的方式更有效地解决这个问题。首先，提出了一种紧凑的体积表示来对作为3D地标的位置的每体素可能性进行编码。无论目标地标的数量如何，这种表示的维度都是固定的，从而避免了维度的诅咒。然后，采用堆积式沙漏网络将体积表示从粗到细估算，之后是三维卷积网络，将估计体积作为输入，并对脸部形状的三维坐标进行回归。通过这种方式，地标之间的三维结构约束可以通过神经网络以更有效的方式学习。此外，所提出的流水线能够实现端到端的训练，并且提高了3D面部标志物定位的鲁棒性和准确性。我们的方法的有效性在3DFAW和AFLW2000-3D数据集上得到验证。实验结果表明，与现有方法相比，所提出的方法达到了最先进的性能。

##### URL
[http://arxiv.org/abs/1801.09242](http://arxiv.org/abs/1801.09242)

##### PDF
[http://arxiv.org/pdf/1801.09242](http://arxiv.org/pdf/1801.09242)

