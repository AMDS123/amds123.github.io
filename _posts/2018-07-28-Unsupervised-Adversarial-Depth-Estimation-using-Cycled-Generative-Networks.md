---
layout: post
title: "Unsupervised Adversarial Depth Estimation using Cycled Generative Networks"
date: 2018-07-28 09:49:41
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning
author: Andrea Pilzer, Dan Xu, Mihai Marian Puscas, Elisa Ricci, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
While recent deep monocular depth estimation approaches based on supervised regression have achieved remarkable performance, costly ground truth annotations are required during training. To cope with this issue, in this paper we present a novel unsupervised deep learning approach for predicting depth maps and show that the depth estimation task can be effectively tackled within an adversarial learning framework. Specifically, we propose a deep generative network that learns to predict the correspondence field i.e. the disparity map between two image views in a calibrated stereo camera setting. The proposed architecture consists of two generative sub-networks jointly trained with adversarial learning for reconstructing the disparity map and organized in a cycle such as to provide mutual constraints and supervision to each other. Extensive experiments on the publicly available datasets KITTI and Cityscapes demonstrate the effectiveness of the proposed model and competitive results with state of the art methods. The code and trained model are available on https://github.com/andrea-pilzer/unsup-stereo-depthGAN.

##### Abstract (translated by Google)
虽然最近基于监督回归的深单眼深度估计方法已经取得了显着的性能，但在训练期间需要昂贵的地面实况注释。为了解决这个问题，在本文中，我们提出了一种新的无监督深度学习方法来预测深度​​图，并表明深度估计任务可以在对抗性学习框架内有效地解决。具体地，我们提出了一种深度生成网络，其学习预测对应场，即校准立体摄像机设置中两个图像视图之间的视差图。所提出的体系结构由两个生成子网络组成，这两个子网络通过对抗性学习联合训练，用于重建视差图并在一个周期中组织，以便相互提供相互约束和监督。在公开可用的数据集KITTI和Cityscapes上进行的大量实验证明了所提出的模型的有效性以及与最先进方法的竞争结果。代码和训练模型可在https://github.com/andrea-pilzer/unsup-stereo-depthGAN上找到。

##### URL
[http://arxiv.org/abs/1807.10915](http://arxiv.org/abs/1807.10915)

##### PDF
[http://arxiv.org/pdf/1807.10915](http://arxiv.org/pdf/1807.10915)

