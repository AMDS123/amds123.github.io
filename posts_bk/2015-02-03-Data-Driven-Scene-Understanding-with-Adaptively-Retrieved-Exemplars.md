---
layout: post
title: "Data-Driven Scene Understanding with Adaptively Retrieved Exemplars"
date: 2015-02-03 06:04:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Xionghao Liu, Wei Yang, Liang Lin, Qing Wang, Zhaoquan Cai, Jianhuang Lai
mathjax: true
---

* content
{:toc}

##### Abstract
This article investigates a data-driven approach for semantically scene understanding, without pixelwise annotation and classifier training. Our framework parses a target image with two steps: (i) retrieving its exemplars (i.e. references) from an image database, where all images are unsegmented but annotated with tags; (ii) recovering its pixel labels by propagating semantics from the references. We present a novel framework making the two steps mutually conditional and bootstrapped under the probabilistic Expectation-Maximization (EM) formulation. In the first step, the references are selected by jointly matching their appearances with the target as well as the semantics (i.e. the assigned labels of the target and the references). We process the second step via a combinatorial graphical representation, in which the vertices are superpixels extracted from the target and its selected references. Then we derive the potentials of assigning labels to one vertex of the target, which depend upon the graph edges that connect the vertex to its spatial neighbors of the target and to its similar vertices of the references. Besides, the proposed framework can be naturally applied to perform image annotation on new test images. In the experiments, we validate our approach on two public databases, and demonstrate superior performances over the state-of-the-art methods in both semantic segmentation and image annotation tasks.

##### Abstract (translated by Google)
本文调查了一种数据驱动的语义场景理解方法，没有像素标注和分类器训练。我们的框架用两个步骤解析目标图像：（i）从图像数据库中检索其示例（即引用），其中所有图像都是未分割的但是用标签注释; （ii）通过从参考中传播语义来恢复其像素标签。我们提出了一个新的框架，使两个步骤互为条件，并在概率期望最大化（EM）公式下引导。在第一步中，通过将它们的外观与目标以及语义（即目标和参考的分配标签）联合匹配来选择参考。我们通过组合图形表示来处理第二步，其中顶点是从目标及其选定参考中提取的超像素。然后，我们推导出将标签分配给目标的一个顶点的可能性，这取决于将顶点连接到其目标的空间邻居的图形边缘及其相似的参考顶点。此外，所提出的框架可以自然地应用于对新的测试图像执行图像标注。在实验中，我们验证了我们在两个公共数据库上的方法，并且在语义分割和图像标注任务中展现了超越现有技术方法的优越性能。

##### URL
[https://arxiv.org/abs/1502.00749](https://arxiv.org/abs/1502.00749)

##### PDF
[https://arxiv.org/pdf/1502.00749](https://arxiv.org/pdf/1502.00749)

