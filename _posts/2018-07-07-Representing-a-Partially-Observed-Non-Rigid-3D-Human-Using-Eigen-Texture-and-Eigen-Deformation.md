---
layout: post
title: "Representing a Partially Observed Non-Rigid 3D Human Using Eigen-Texture and Eigen-Deformation"
date: 2018-07-07 08:18:31
categories: arXiv_CV
tags: arXiv_CV Attention Face Embedding
author: Ryosuke Kimura, Akihiko Sayo, Fabian Lorenzo Dayrit, Yuta Nakashima, Hiroshi Kawasaki, Ambrosio Blanco, Katsushi Ikeuchi
mathjax: true
---

* content
{:toc}

##### Abstract
Reconstruction of the shape and motion of humans from RGB-D is a challenging problem, receiving much attention in recent years. Recent approaches for full-body reconstruction use a statistic shape model, which is built upon accurate full-body scans of people in skin-tight clothes, to complete invisible parts due to occlusion. Such a statistic model may still be fit to an RGB-D measurement with loose clothes but cannot describe its deformations, such as clothing wrinkles. Observed surfaces may be reconstructed precisely from actual measurements, while we have no cues for unobserved surfaces. For full-body reconstruction with loose clothes, we propose to use lower dimensional embeddings of texture and deformation referred to as eigen-texturing and eigen-deformation, to reproduce views of even unobserved surfaces. Provided a full-body reconstruction from a sequence of partial measurements as 3D meshes, the texture and deformation of each triangle are then embedded using eigen-decomposition. Combined with neural-network-based coefficient regression, our method synthesizes the texture and deformation from arbitrary viewpoints. We evaluate our method using simulated data and visually demonstrate how our method works on real data.

##### Abstract (translated by Google)
从RGB-D重建人的形状和运动是一个具有挑战性的问题，近年来受到很多关注。最近的全身重建方法使用统计形状模型，该模型建立在对紧身衣服的人进行精确的全身扫描的基础上，以完成由于闭塞而导致的不可见部分。这样的统计模型仍然适合于穿着宽松衣服的RGB-D测量，但是不能描述其变形，例如衣服皱纹。可以从实际测量精确地重建观察到的表面，而我们没有观察到未观察到的表面。对于宽松衣服的全身重建，我们建议使用纹理和变形的低维嵌入（称为本征纹理和本征变形）来再现甚至未观察到的表面的视图。提供从一系列部分测量为3D网格的全身重建，然后使用特征分解嵌入每个三角形的纹理和变形。结合基于神经网络的系数回归，我们的方法从任意视点合成纹理和变形。我们使用模拟数据评估我们的方法，并直观地演示我们的方法如何处理实际数据。

##### URL
[http://arxiv.org/abs/1807.02632](http://arxiv.org/abs/1807.02632)

##### PDF
[http://arxiv.org/pdf/1807.02632](http://arxiv.org/pdf/1807.02632)

