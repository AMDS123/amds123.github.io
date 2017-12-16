---
layout: post
title: "GRASS: Generative Recursive Autoencoders for Shape Structures"
date: 2017-05-13 04:49:23
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification Relation
author: Jun Li, Kai Xu, Siddhartha Chaudhuri, Ersin Yumer, Hao Zhang, Leonidas Guibas
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel neural network architecture for encoding and synthesis of 3D shapes, particularly their structures. Our key insight is that 3D shapes are effectively characterized by their hierarchical organization of parts, which reflects fundamental intra-shape relationships such as adjacency and symmetry. We develop a recursive neural net (RvNN) based autoencoder to map a flat, unlabeled, arbitrary part layout to a compact code. The code effectively captures hierarchical structures of man-made 3D objects of varying structural complexities despite being fixed-dimensional: an associated decoder maps a code back to a full hierarchy. The learned bidirectional mapping is further tuned using an adversarial setup to yield a generative model of plausible structures, from which novel structures can be sampled. Finally, our structure synthesis framework is augmented by a second trained module that produces fine-grained part geometry, conditioned on global and local structural context, leading to a full generative pipeline for 3D shapes. We demonstrate that without supervision, our network learns meaningful structural hierarchies adhering to perceptual grouping principles, produces compact codes which enable applications such as shape classification and partial matching, and supports shape synthesis and interpolation with significant variations in topology and geometry.

##### Abstract (translated by Google)
我们介绍了一种新的神经网络架构，用于3D形状的编码和合成，特别是它们的结构。我们关键的洞察力是三维形状通过零件的等级组织来有效地表征，这反映了基本的形状内关系，如邻接性和对称性。我们开发了一个基于递归神经网络（RvNN）的自动编码器，将一个平坦的，无标签的任意部分布局映射为一个紧凑的代码。该代码有效地捕捉了不同结构复杂性的人造3D对象的层次结构，尽管是固定维度的：相关的解码器将代码映射回完整的层次结构。学习的双向映射进一步调整使用敌对设置产生合理结构的生成模型，从中可以采样新结构。最后，我们的结构综合框架增加了第二个训练模块，该模块生成以全局和局部结构上下文为条件的细粒度零件几何，从而形成完整的三维形状生成流水线。我们证明，没有监督，我们的网络学习有意义的结构层次坚持知觉分组的原则，产生紧凑的代码，使应用程序，如形状分类和部分匹配，并支持形状合成和插值与拓扑结构和几何的显着变化。

##### URL
[https://arxiv.org/abs/1705.02090](https://arxiv.org/abs/1705.02090)

##### PDF
[https://arxiv.org/pdf/1705.02090](https://arxiv.org/pdf/1705.02090)

