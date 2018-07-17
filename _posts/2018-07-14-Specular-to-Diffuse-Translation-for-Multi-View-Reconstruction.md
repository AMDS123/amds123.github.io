---
layout: post
title: "Specular-to-Diffuse Translation for Multi-View Reconstruction"
date: 2018-07-14 20:51:30
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation
author: Shihao Wu, Hui Huang, Tiziano Portenier, Matan Sela, Danny Cohen-Or, Ron Kimmel, Matthias Zwicker
mathjax: true
---

* content
{:toc}

##### Abstract
Most multi-view 3D reconstruction algorithms, especially when shape-from-shading cues are used, assume that object appearance is predominantly diffuse. To alleviate this restriction, we introduce S2Dnet, a generative adversarial network for transferring multiple views of objects with specular reflection into diffuse ones, so that multi-view reconstruction methods can be applied more effectively. Our network extends unsupervised image-to-image translation to multi-view "specular to diffuse" translation. To preserve object appearance across multiple views, we introduce a Multi-View Coherence loss (MVC) that evaluates the similarity and faithfulness of local patches after the view-transformation. Our MVC loss ensures that the similarity of local correspondences among multi-view images is preserved under the image-to-image translation. As a result, our network yields significantly better results than several single-view baseline techniques. In addition, we carefully design and generate a large synthetic training data set using physically-based rendering. During testing, our network takes only the raw glossy images as input, without extra information such as segmentation masks or lighting estimation. Results demonstrate that multi-view reconstruction can be significantly improved using the images filtered by our network. We also show promising performance on real world training and testing data.

##### Abstract (translated by Google)
大多数多视图3D重建算法，特别是当使用来自阴影的形状提示时，假设对象外观主要是漫射的。为了缓解这种限制，我们引入了S2Dnet，一种生成的对抗网络，用于将具有镜面反射的物体的多个视图转换为漫反射网络，从而可以更有效地应用多视图重建方法。我们的网络将无监督的图像到图像转换扩展到多视图“镜面到漫反射”的转换。为了在多个视图中保留对象外观，我们引入了一个多视图一致性丢失（MVC），用于评估视图转换后局部补丁的相似性和忠实度。我们的MVC损失确保在图像到图像转换下保留多视图图像之间的局部对应的相似性。因此，与几种单视图基线技术相比，我们的网络产生了明显更好的结果。此外，我们使用基于物理的渲染精心设计并生成大型综合训练数据集。在测试过程中，我们的网络仅将原始光泽图像作为输入，无需额外信息，如分割掩模或光照估计。结果表明，使用我们的网络过滤的图像可以显着改善多视图重建。我们还展示了在现实世界培训和测试数据方面的出色表现。

##### URL
[http://arxiv.org/abs/1807.05439](http://arxiv.org/abs/1807.05439)

##### PDF
[http://arxiv.org/pdf/1807.05439](http://arxiv.org/pdf/1807.05439)

