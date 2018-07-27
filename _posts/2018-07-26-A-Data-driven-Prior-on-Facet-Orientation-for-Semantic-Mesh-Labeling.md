---
layout: post
title: "A Data-driven Prior on Facet Orientation for Semantic Mesh Labeling"
date: 2018-07-26 08:09:15
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Face Relation
author: Andrea Romanoni, Matteo Matteucci
mathjax: true
---

* content
{:toc}

##### Abstract
Mesh labeling is the key problem of classifying the facets of a 3D mesh with a label among a set of possible ones. State-of-the-art methods model mesh labeling as a Markov Random Field over the facets. These algorithms map image segmentations to the mesh by minimizing an energy function that comprises a data term, a smoothness terms, and class-specific priors. The latter favor a labeling with respect to another depending on the orientation of the facet normals. In this paper we propose a novel energy term that acts as a prior, but does not require any prior knowledge about the scene nor scene-specific relationship among classes. It bootstraps from a coarse mapping of the 2D segmentations on the mesh, and it favors the facets to be labeled according to the statistics of the mesh normals in their neighborhood. We tested our approach against five different datasets and, even if we do not inject prior knowledge, our method adapts to the data and overcomes the state-of-the-art.

##### Abstract (translated by Google)
网格标注是使用一组可能的标签中的标签对3D网格的面进行分类的关键问题。最先进的方法将网格标注模拟为小平面上的马尔可夫随机场。这些算法通过最小化包括数据项，平滑项和类特定先验的能量函数将图像分割映射到网格。后者有利于相对于另一个的标记，这取决于小平面法线的方向。在本文中，我们提出了一个新的能量项，作为一个先验，但不需要任何关于场景的先验知识和类之间的场景特定关系。它从网格上的2D分割的粗略映射引导，并且它有利于根据其邻域中的网格法线的统计来标记小平面。我们针对五个不同的数据集测试了我们的方法，即使我们没有注入先验知识，我们的方法也适应数据并克服了最新技术。

##### URL
[http://arxiv.org/abs/1807.09999](http://arxiv.org/abs/1807.09999)

##### PDF
[http://arxiv.org/pdf/1807.09999](http://arxiv.org/pdf/1807.09999)

