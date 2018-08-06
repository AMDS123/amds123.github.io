---
layout: post
title: "Pixel2Mesh: Generating 3D Mesh Models from Single RGB Images"
date: 2018-08-03 08:52:33
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Nanyang Wang, Yinda Zhang, Zhuwen Li, Yanwei Fu, Wei Liu, Yu-Gang Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an end-to-end deep learning architecture that produces a 3D shape in triangular mesh from a single color image. Limited by the nature of deep neural network, previous methods usually represent a 3D shape in volume or point cloud, and it is non-trivial to convert them to the more ready-to-use mesh model. Unlike the existing methods, our network represents 3D mesh in a graph-based convolutional neural network and produces correct geometry by progressively deforming an ellipsoid, leveraging perceptual features extracted from the input image. We adopt a coarse-to-fine strategy to make the whole deformation procedure stable, and define various of mesh related losses to capture properties of different levels to guarantee visually appealing and physically accurate 3D geometry. Extensive experiments show that our method not only qualitatively produces mesh model with better details, but also achieves higher 3D shape estimation accuracy compared to the state-of-the-art.

##### Abstract (translated by Google)
我们提出了一种端到端的深度学习架构，该架构可以从单个彩色图像中生成三角形网格中的3D形状。受深度神经网络性质的限制，以前的方法通常表示体积或点云中的3D形状，将它们转换为更易于使用的网格模型并非易事。与现有方法不同，我们的网络在基于图形的卷积神经网络中表示3D网格，并通过逐渐变形椭球产生正确的几何形状，利用从输入图像提取的感知特征。我们采用粗到细的策略使整个变形过程稳定，并定义各种网格相关的损失，以捕捉不同层次的属性，以保证视觉上吸引人和物理上精确的3D几何。大量实验表明，我们的方法不仅可以定性地生成具有更好细节的网格模型，而且与现有技术相比，还可以实现更高的3D形状估计精度。

##### URL
[http://arxiv.org/abs/1804.01654](http://arxiv.org/abs/1804.01654)

##### PDF
[http://arxiv.org/pdf/1804.01654](http://arxiv.org/pdf/1804.01654)

