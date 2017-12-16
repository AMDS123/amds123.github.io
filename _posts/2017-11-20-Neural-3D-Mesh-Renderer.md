---
layout: post
title: "Neural 3D Mesh Renderer"
date: 2017-11-20 22:12:23
categories: arXiv_CV
tags: arXiv_CV Style_Transfer
author: Hiroharu Kato, Yoshitaka Ushiku, Tatsuya Harada
mathjax: true
---

* content
{:toc}

##### Abstract
For modeling the 3D world behind 2D images, which 3D representation is most appropriate? A polygon mesh is a promising candidate for its compactness and geometric properties. However, it is not straightforward to model a polygon mesh from 2D images using neural networks because the conversion from a mesh to an image, or rendering, involves a discrete operation called rasterization, which prevents back-propagation. Therefore, in this work, we propose an approximate gradient for rasterization that enables the integration of rendering into neural networks. Using this renderer, we perform single-image 3D mesh reconstruction with silhouette image supervision and our system outperforms the existing voxel-based approach. Additionally, we perform gradient-based 3D mesh editing operations, such as 2D-to-3D style transfer and 3D DeepDream, with 2D supervision for the first time. These applications demonstrate the potential of the integration of a mesh renderer into neural networks and the effectiveness of our proposed renderer.

##### Abstract (translated by Google)
为了在二维图像背后对三维世界进行建模，哪种三维图像最合适？多边形网格是其紧凑性和几何特性的有希望的候选者。然而，使用神经网络从2D图像建模多边形网格并不容易，因为从网格到图像的转换或渲染涉及一个称为光栅化的离散操作，可防止反向传播。因此，在这项工作中，我们提出了一个近似的光栅化梯度，可以将渲染集成到神经网络中。使用这个渲染器，我们使用轮廓图像监督来执行单图像3D网格重建，并且我们的系统胜过了现有的基于体素的方法。另外，我们还首次使用2D监视来执行基于渐变的3D网格编辑操作，如2D到3D风格的转移和3D DeepDream。这些应用程序展示了将网格渲染器集成到神经网络中的潜力以及我们提出的渲染器的有效性。

##### URL
[https://arxiv.org/abs/1711.07566](https://arxiv.org/abs/1711.07566)

##### PDF
[https://arxiv.org/pdf/1711.07566](https://arxiv.org/pdf/1711.07566)

