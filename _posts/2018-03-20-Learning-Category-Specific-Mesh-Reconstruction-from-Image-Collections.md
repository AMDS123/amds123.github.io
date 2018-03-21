---
layout: post
title: "Learning Category-Specific Mesh Reconstruction from Image Collections"
date: 2018-03-20 17:44:30
categories: arXiv_CV
tags: arXiv_CV Inference Prediction Quantitative
author: Angjoo Kanazawa, Shubham Tulsiani, Alexei A. Efros, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
We present a learning framework for recovering the 3D shape, camera, and texture of an object from a single image. The shape is represented as a deformable 3D mesh model of an object category where a shape is parameterized by a learned mean shape and per-instance predicted deformation. Our approach allows leveraging an annotated image collection for training, where the deformable model and the 3D prediction mechanism are learned without relying on ground-truth 3D or multi-view supervision. Our representation enables us to go beyond existing 3D prediction approaches by incorporating texture inference as prediction of an image in a canonical appearance space. Additionally, we show that semantic keypoints can be easily associated with the predicted shapes. We present qualitative and quantitative results of our approach on the CUB dataset, and show that we can learn to predict the diverse shapes and textures across birds using only an annotated image collection. We also demonstrate the the applicability of our method for learning the 3D structure of other generic categories.

##### Abstract (translated by Google)
我们提供了一个学习框架，用于从单个图像中恢复对象的3D形状，相机和纹理。形状被表示为对象类别的可变形3D网格模型，其中通过学习的平均形状和每个实例的预测变形对形状进行参数化。我们的方法允许利用带注释的图像集进行训练，其中可变形模型和3D预测机制是在不依赖于地面真实3D或多视图监督的情况下学习的。我们的表示使我们能够超越现有的3D预测方法，将纹理推理结合为规范外观空间中的图像预测。此外，我们表明，语义关键点可以很容易地与预测的形状相关联。我们在CUB数据集上提供了我们方法的定性和定量结果，并且表明我们可以学习使用仅带注释的图像集合来预测鸟类的不同形状和纹理。我们还演示了我们的方法用于学习其他通用类别的3D结构的适用性。

##### URL
[http://arxiv.org/abs/1803.07549](http://arxiv.org/abs/1803.07549)

##### PDF
[http://arxiv.org/pdf/1803.07549](http://arxiv.org/pdf/1803.07549)

