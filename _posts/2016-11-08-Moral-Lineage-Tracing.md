---
layout: post
title: "Moral Lineage Tracing"
date: 2016-11-08 10:42:12
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Tracking
author: Florian Jug, Evgeny Levinkov, Corinna Blasse, Eugene W. Myers, Bjoern Andres
mathjax: true
---

* content
{:toc}

##### Abstract
Lineage tracing, the tracking of living cells as they move and divide, is a central problem in biological image analysis. Solutions, called lineage forests, are key to understanding how the structure of multicellular organisms emerges. We propose an integer linear program (ILP) whose feasible solutions define a decomposition of each image in a sequence into cells (segmentation), and a lineage forest of cells across images (tracing). Unlike previous formulations, we do not constrain the set of decompositions, except by contracting pixels to superpixels. The main challenge, as we show, is to enforce the morality of lineages, i.e., the constraint that cells do not merge. To enforce morality, we introduce path-cut inequalities. To find feasible solutions of the NP-hard ILP, with certified bounds to the global optimum, we define efficient separation procedures and apply these as part of a branch-and-cut algorithm. We show the effectiveness of this approach by analyzing feasible solutions for real microscopy data in terms of bounds and run-time, and by their weighted edit distance to ground truth lineage forests traced by humans.

##### Abstract (translated by Google)
谱系追踪，追踪活细胞移动和分裂，是生物图像分析中的核心问题。称为谱系森林的解决方案是理解多细胞生物体结构如何出现的关键。我们提出了一个整数线性规划（ILP），其可行的解决方案定义了一个序列中的每个图像分解成细胞（分割），和细胞跨越图像（追踪）沿袭森林。与以前的公式不同，我们不限制分解集合，除了将像素缩小为超像素。正如我们所表明的那样，主要的挑战是强化谱系的道德，即细胞不合并的约束。为了强化道德，我们引入了路径不平等。为了找到NP-hard ILP的可行解，并证明了全局最优的界限，我们定义了高效的分离程序，并将其作为分支和切割算法的一部分。我们通过分析实际显微镜数据的边界和运行时间方面的可行解决方案，以及它们与人类追踪的地面实况谱系森林的加权编辑距离来展示这种方法的有效性。

##### URL
[https://arxiv.org/abs/1511.05512](https://arxiv.org/abs/1511.05512)

##### PDF
[https://arxiv.org/pdf/1511.05512](https://arxiv.org/pdf/1511.05512)

