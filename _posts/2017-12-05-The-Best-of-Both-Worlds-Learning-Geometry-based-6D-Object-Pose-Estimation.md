---
layout: post
title: "The Best of Both Worlds: Learning Geometry-based 6D Object Pose Estimation"
date: 2017-12-05 21:01:24
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Pose_Estimation
author: Omid Hosseini Jafari, Siva Karthik Mustikovela, Karl Pertsch, Eric Brachmann, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
We address the task of estimating the 6D pose of known rigid objects, from RGB and RGB-D input images, in scenarios where the objects are heavily occluded. Our main contribution is a new modular processing pipeline. The first module localizes all known objects in the image via an existing instance segmentation network. The next module densely regresses the object surface positions in its local coordinate system, using an encoder-decoder network. The third module is purely a geometry-based algorithm to output the final 6D object poses. While the first two modules are learned from data, and the last one not, we believe that this is the best of both worlds: geometry-based and learning-based algorithms for object 6D pose estimation. This is validated by achieving state-of-the-art results for RGB input and a slight improvement over state-of-the-art for RGB-D input. However, in contrast to previous work, we achieve these results with the same pipeline for RGB and RGB-D input. Furthermore, to obtain these results, we give a second contribution of a new 3D occlusion-aware and object-centric data augmentation procedure.

##### Abstract (translated by Google)
我们针对在RGB和RGB-D输入图像中估计已知刚性物体的6D姿态的任务，在物体被严重遮挡的情况下。我们的主要贡献是新的模块化处理流水线。第一个模块通过现有的实例分段网络来定位图像中的所有已知对象。下一个模块使用编码器 - 解码器网络，密集地回归其局部坐标系中的物体表面位置。第三个模块纯粹是一个基于几何的算法来输出最终的6D对象姿势。虽然前两个模块是从数据中学习的，而最后一个模块是从数据中学习的，但是我们相信这是两全其美的：基于几何和基于学习的对象6D姿态估计算法。通过实现RGB输入的最先进的结果以及比RGB-D输入的最新技术略有改进来验证这一点。但是，与以前的工作相比，我们使用RGB和RGB-D输入的相同流水线来实现这些结果。此外，为了获得这些结果，我们给出了新的3D遮挡感知和以对象为中心的数据增强过程的第二个贡献。

##### URL
[http://arxiv.org/abs/1712.01924](http://arxiv.org/abs/1712.01924)

##### PDF
[http://arxiv.org/pdf/1712.01924](http://arxiv.org/pdf/1712.01924)

