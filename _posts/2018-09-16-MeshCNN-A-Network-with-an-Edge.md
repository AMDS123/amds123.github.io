---
layout: post
title: "MeshCNN: A Network with an Edge"
date: 2018-09-16 16:32:29
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Rana Hanocka, Amir Hertz, Noa Fish, Raja Giryes, Shachar Fleishman, Daniel Cohen-Or
mathjax: true
---

* content
{:toc}

##### Abstract
A polygonal mesh representation provides an efficient approximation for 3D shapes. It explicitly captures both shape surface and topology, and leverages non-uniformity to represent large flat regions as well as sharp, intricate features. This non-uniformity and irregularity, however, inhibits mesh analysis efforts using neural networks that combine convolution and pooling operations. In this paper, we utilize the unique properties of the mesh for a direct analysis of 3D shapes using MeshCNN, a convolutional neural network designed specifically for triangular meshes. Analogous to classic CNNs, MeshCNN combines specialized convolution and pooling layers that operate on the mesh edges, by leveraging their intrinsic geodesic connections. Convolutions are applied on edges and the four edges of their incident triangles, and pooling is applied via an edge collapse operation that retains surface topology, thereby, generating new mesh connectivity for the subsequent convolutions. MeshCNN learns which edges to collapse, thus forming a task-driven process where the network exposes and expands the important features while discarding the redundant ones. We demonstrate the effectiveness of our task-driven pooling on various learning tasks applied to 3D meshes.

##### Abstract (translated by Google)
多边形网格表示为3D形状提供了有效的近似。它明确地捕获了形状表面和拓扑结构，并利用非均匀性来表示大的平坦区域以及清晰，复杂的特征。然而，这种不均匀性和不规则性使用结合了卷积和汇集操作的神经网络来抑制网格分析工作。在本文中，我们利用网格的独特属性，使用MeshCNN（一种专为三角网格设计的卷积神经网络）直接分析三维形状。类似于传统的CNN，MeshCNN通过利用其固有的测地连接，结合了在网格边缘上运行的专用卷积和池化层。卷积应用于边缘和它们的入射三角形的四个边缘，并且通过保留表面拓扑的边缘折叠操作来应用汇集，从而为后续卷积生成新的网格连通性。 MeshCNN学习哪些边缘崩溃，从而形成一个任务驱动的过程，网络暴露并扩展重要特征，同时丢弃冗余特征。我们展示了我们的任务驱动池对应用于3D网格的各种学习任务的有效性。

##### URL
[http://arxiv.org/abs/1809.05910](http://arxiv.org/abs/1809.05910)

##### PDF
[http://arxiv.org/pdf/1809.05910](http://arxiv.org/pdf/1809.05910)

