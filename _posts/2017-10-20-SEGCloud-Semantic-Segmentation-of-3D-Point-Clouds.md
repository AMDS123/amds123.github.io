---
layout: post
title: "SEGCloud: Semantic Segmentation of 3D Point Clouds"
date: 2017-10-20 15:05:41
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Optimization Prediction
author: Lyne P. Tchapmi, Christopher B. Choy, Iro Armeni, JunYoung Gwak, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
3D semantic scene labeling is fundamental to agents operating in the real world. In particular, labeling raw 3D point sets from sensors provides fine-grained semantics. Recent works leverage the capabilities of Neural Networks (NNs), but are limited to coarse voxel predictions and do not explicitly enforce global consistency. We present SEGCloud, an end-to-end framework to obtain 3D point-level segmentation that combines the advantages of NNs, trilinear interpolation(TI) and fully connected Conditional Random Fields (FC-CRF). Coarse voxel predictions from a 3D Fully Convolutional NN are transferred back to the raw 3D points via trilinear interpolation. Then the FC-CRF enforces global consistency and provides fine-grained semantics on the points. We implement the latter as a differentiable Recurrent NN to allow joint optimization. We evaluate the framework on two indoor and two outdoor 3D datasets (NYU V2, S3DIS, KITTI, Semantic3D.net), and show performance comparable or superior to the state-of-the-art on all datasets.

##### Abstract (translated by Google)
3D语义场景标签是代理商在现实世界中运作的基础。特别是，从传感器标记原始3D点集提供了细粒度的语义。最近的作品利用了神经网络（NN）的功能，但仅限于粗体素预测，并没有明确强调全局一致性。我们提出了一个端到端的框架SEGCloud来获得结合神经网络，三线性插值（TI）和完全连接的条件随机场（FC-CRF）的优点的三维点级分割。来自3D全卷积NN的粗体素预测通过三线性内插被转移回原始3D点。然后，FC-CRF执行全局一致性，并提供精细的语义。我们将后者作为可微分的递归神经网络来实现，以实现联合优化。我们评估了两个室内和两个户外三维数据集（NYU V2，S3DIS，KITTI，Semantic3D.net）的框架，并且在所有数据集上显示出与现有技术相当或优越的性能。

##### URL
[https://arxiv.org/abs/1710.07563](https://arxiv.org/abs/1710.07563)

##### PDF
[https://arxiv.org/pdf/1710.07563](https://arxiv.org/pdf/1710.07563)

