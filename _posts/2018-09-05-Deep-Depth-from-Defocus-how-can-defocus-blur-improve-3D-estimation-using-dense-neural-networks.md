---
layout: post
title: "Deep Depth from Defocus: how can defocus blur improve 3D estimation using dense neural networks?"
date: 2018-09-05 15:09:20
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Prediction
author: Marcela Carvalho, Bertrand Le Saux, Pauline Trouv&#xe9;-Peloux, Andr&#xe9;s Almansa, Fr&#xe9;d&#xe9;ric Champagnat
mathjax: true
---

* content
{:toc}

##### Abstract
Depth estimation is of critical interest for scene understanding and accurate 3D reconstruction. Most recent approaches in depth estimation with deep learning exploit geometrical structures of standard sharp images to predict corresponding depth maps. However, cameras can also produce images with defocus blur depending on the depth of the objects and camera settings. Hence, these features may represent an important hint for learning to predict depth. In this paper, we propose a full system for single-image depth prediction in the wild using depth-from-defocus and neural networks. We carry out thorough experiments to test deep convolutional networks on real and simulated defocused images using a realistic model of blur variation with respect to depth. We also investigate the influence of blur on depth prediction observing model uncertainty with a Bayesian neural network approach. From these studies, we show that out-of-focus blur greatly improves the depth-prediction network performances. Furthermore, we transfer the ability learned on a synthetic, indoor dataset to real, indoor and outdoor images. For this purpose, we present a new dataset containing real all-focus and defocused images from a Digital Single-Lens Reflex (DSLR) camera, paired with ground truth depth maps obtained with an active 3D sensor for indoor scenes. The proposed approach is successfully validated on both this new dataset and standard ones as NYUv2 or Depth-in-the-Wild. Code and new datasets are available at https://github.com/marcelampc/d3net_depth_estimation.

##### Abstract (translated by Google)
深度估计对场景理解和精确的3D重建具有重要意义。深度学习的深度估计的最新方法利用标准清晰图像的几何结构来预测相应的深度图。但是，相机也可以根据物体的深度和相机设置生成散焦模糊的图像。因此，这些特征可能代表了学习预测深度的重要提示。在本文中，我们使用深度离散和神经网络提出了一个完整的野外单图像深度预测系统。我们使用相对于深度的模糊变化的真实模型，进行彻底的实验以在真实和模拟的散焦图像上测试深度卷积网络。我们还用贝叶斯神经网络方法研究了模糊对深度预测观测模型不确定性的影响。从这些研究中，我们发现离焦模糊极大地改善了深度预测网络性能。此外，我们将在合成室内数据集上学习的能力转移到真实，室内和室外图像。为此，我们提供了一个新的数据集，其中包含来自数码单镜头反光（DSLR）相机的真实全焦点和散焦图像，与用于室内场景的主动3D传感器获得的地面真实深度图配对。所提出的方法在这个新数据集和标准的数据集上成功验证为NYUv2或Depth-in-the-Wild。代码和新数据集可在https://github.com/marcelampc/d3net_depth_estimation获得。

##### URL
[http://arxiv.org/abs/1809.01567](http://arxiv.org/abs/1809.01567)

##### PDF
[http://arxiv.org/pdf/1809.01567](http://arxiv.org/pdf/1809.01567)

