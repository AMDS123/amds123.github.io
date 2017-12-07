---
layout: post
title: "Image2Mesh: A Learning Framework for Single Image 3D Reconstruction"
date: 2017-11-29 03:57:32
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Jhony K. Pontes, Chen Kong, Sridha Sridharan, Simon Lucey, Anders Eriksson, Clinton Fookes
mathjax: true
---

* content
{:toc}

##### Abstract
One challenge that remains open in 3D deep learning is how to efficiently represent 3D data to feed deep networks. Recent works have relied on volumetric or point cloud representations, but such approaches suffer from a number of issues such as computational complexity, unordered data, and lack of finer geometry. This paper demonstrates that a mesh representation (i.e. vertices and faces to form polygonal surfaces) is able to capture fine-grained geometry for 3D reconstruction tasks. A mesh however is also unstructured data similar to point clouds. We address this problem by proposing a learning framework to infer the parameters of a compact mesh representation rather than learning from the mesh itself. This compact representation encodes a mesh using free-form deformation and a sparse linear combination of models allowing us to reconstruct 3D meshes from single images. In contrast to prior work, we do not rely on silhouettes and landmarks to perform 3D reconstruction. We evaluate our method on synthetic and real-world datasets with very promising results. Our framework efficiently reconstructs 3D objects in a low-dimensional way while preserving its important geometrical aspects.

##### Abstract (translated by Google)
在3D深度学习中仍然存在的一个挑战是如何有效地表示3D数据以馈送深度网络。最近的工作依赖于体积或点云表示，但是这样的方法受到诸如计算复杂性，无序数据以及缺少更精细几何结构等许多问题的困扰。本文表明，网格表示（即顶点和面形成多边形曲面）能够捕捉细粒度的几何图形，用于三维重建任务。然而，网格也是类似于点云的非结构化数据。我们通过提出一个学习框架来解决这个问题，来推断一个紧凑的网格表示的参数，而不是从网格本身学习。这种紧凑的表示使用自由形变和网格模型的稀疏线性组合来编码网格，从而允许我们从单个图像重建3D网格。与之前的工作不同，我们不依靠轮廓和地标来执行3D重建。我们在合成和现实世界的数据集上评估我们的方法，结果非常有希望。我们的框架以低维方式有效地重建3D对象，同时保留其重要的几何方面。

##### URL
[https://arxiv.org/abs/1711.10669](https://arxiv.org/abs/1711.10669)

##### PDF
[https://arxiv.org/pdf/1711.10669](https://arxiv.org/pdf/1711.10669)

