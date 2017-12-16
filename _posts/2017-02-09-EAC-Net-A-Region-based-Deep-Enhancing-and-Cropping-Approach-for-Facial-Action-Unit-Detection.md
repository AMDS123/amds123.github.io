---
layout: post
title: "EAC-Net: A Region-based Deep Enhancing and Cropping Approach for Facial Action Unit Detection"
date: 2017-02-09 18:16:44
categories: arXiv_CV
tags: arXiv_CV Attention CNN Deep_Learning Detection
author: Wei Li, Farnaz Abtahi, Zhigang Zhu, Lijun Yin
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a deep learning based approach for facial action unit detection by enhancing and cropping the regions of interest. The approach is implemented by adding two novel nets (layers): the enhancing layers and the cropping layers, to a pretrained CNN model. For the enhancing layers, we designed an attention map based on facial landmark features and applied it to a pretrained neural network to conduct enhanced learning (The E-Net). For the cropping layers, we crop facial regions around the detected landmarks and design convolutional layers to learn deeper features for each facial region (C-Net). We then fuse the E-Net and the C-Net to obtain our Enhancing and Cropping (EAC) Net, which can learn both feature enhancing and region cropping functions. Our approach shows significant improvement in performance compared to the state-of-the-art methods applied to BP4D and DISFA AU datasets.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于深度学习的面部动作单元检测方法，通过增强和种植感兴趣的区域。该方法是通过添加两个新的网（层）：增强层和耕作层，对预训练CNN模型。对于增强层，我们设计了一个基于面部标志特征的注意图，并将其应用于预训练的神经网络来进行增强学习（E-Net）。对于裁剪图层，我们在检测到的地标周围裁剪面部区域，并设计卷积图层来学习每个面部区域（C-Net）的更深层特征。然后，我们将E-Net和C-Net融合起来，以获得我们的增强和裁剪（EAC）网络，它可以学习功能增强和区域裁剪功能。与应用于BP4D和DISFA AU数据集的最先进的方法相比，我们的方法在性能上有显着的提高。

##### URL
[https://arxiv.org/abs/1702.02925](https://arxiv.org/abs/1702.02925)

##### PDF
[https://arxiv.org/pdf/1702.02925](https://arxiv.org/pdf/1702.02925)

