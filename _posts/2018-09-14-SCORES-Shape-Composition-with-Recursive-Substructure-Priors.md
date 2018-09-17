---
layout: post
title: "SCORES: Shape Composition with Recursive Substructure Priors"
date: 2018-09-14 13:20:06
categories: arXiv_CV
tags: arXiv_CV
author: Chenyang Zhu, Kai Xu, Siddhartha Chaudhuri, Renjiao Yi, Hao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce SCORES, a recursive neural network for shape composition. Our network takes as input sets of parts from two or more source 3D shapes and a rough initial placement of the parts. It outputs an optimized part structure for the composed shape, leading to high-quality geometry construction. A unique feature of our composition network is that it is not merely learning how to connect parts. Our goal is to produce a coherent and plausible 3D shape, despite large incompatibilities among the input parts. The network may significantly alter the geometry and structure of the input parts and synthesize a novel shape structure based on the inputs, while adding or removing parts to minimize a structure plausibility loss. We design SCORES as a recursive autoencoder network. During encoding, the input parts are recursively grouped to generate a root code. During synthesis, the root code is decoded, recursively, to produce a new, coherent part assembly. Assembled shape structures may be novel, with little global resemblance to training exemplars, yet have plausible substructures. SCORES therefore learns a hierarchical substructure shape prior based on per-node losses. It is trained on structured shapes from ShapeNet, and is applied iteratively to reduce the plausibility loss.We showresults of shape composition from multiple sources over different categories of man-made shapes and compare with state-of-the-art alternatives, demonstrating that our network can significantly expand the range of composable shapes for assembly-based modeling.

##### Abstract (translated by Google)
我们介绍了SCORES，一种用于形状合成的递归神经网络。我们的网络从两个或多个源3D形状和部件的粗略初始放置中获取部件的输入集。它为组合形状输出优化的零件结构，从而实现高质量的几何结构。我们的合成网络的一个独特之处在于它不仅仅是学习如何连接部件。尽管输入部件之间存在很大的不兼容性，但我们的目标是产生连贯且可信的3D形状。网络可以显着改变输入部件的几何形状和结构，并基于输入合成新颖的形状结构，同时添加或移除部件以最小化结构合理性损失。我们将SCORES设计为递归自动编码器网络。在编码期间，递归地对输入部分进行分组以生成根代码。在合成期间，递归地解码根代码以产生新的相干部件组件。组装的形状结构可能是新颖的，与训练样本几乎没有全局相似性，但具有合理的子结构。因此，SCORES基于每个节点的损失来学习先前的分层子结构形状。它采用ShapeNet的结构形状进行训练，并反复应用以减少合理性损失。我们展示了来自不同类别人造形状的多种来源的形状组成结果，并与最先进的替代方案进行比较，证明了我们的网络可以显着扩展可组合形状的范围，以进行基于装配的建模。

##### URL
[http://arxiv.org/abs/1809.05398](http://arxiv.org/abs/1809.05398)

##### PDF
[http://arxiv.org/pdf/1809.05398](http://arxiv.org/pdf/1809.05398)

