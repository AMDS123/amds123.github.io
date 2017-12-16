---
layout: post
title: "Multi-view Registration Based on Weighted Low Rank and Sparse Matrix Decomposition of Motions"
date: 2017-09-25 09:30:02
categories: arXiv_CV
tags: arXiv_CV Sparse Relation
author: Congcong Jin, Jihua Zhu, Yaochen Li, Shanmin Pang, Lei Chen, Jun Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the low rank and sparse (LRS) matrix decomposition has been introduced as an effective mean to solve the multi-view registration. However, this method presents two notable disadvantages: the registration result is quite sensitive to the sparsity of the LRS matrix; besides, the decomposition process treats each block element equally in spite of their reliability. Therefore, this paper firstly proposes a matrix completion method based on the overlap percentage of scan pairs. By completing the LRS matrix with reliable block elements as much as possible, more synchronization constraints of relative motions can be utilized for registration. Furthermore, it is observed that the reliability of each element in the LRS matrix can be weighed by the relationship between its corresponding model and data shapes. Therefore, a weight matrix is designed to measure the contribution of each element to decomposition and accordingly, the decomposition result is closer to the ground truth than before. Benefited from the more informative LRS matrix as well as the weight matrix, experimental results conducted on several public datasets demonstrate the superiority of the proposed approach over other methods on both accuracy and robustness.

##### Abstract (translated by Google)
最近，低秩稀疏（LRS）矩阵分解被引入作为解决多视图配准的有效手段。然而，这种方法存在两个明显的缺点：配准结果对LRS矩阵的稀疏性非常敏感;此外，尽管分解过程的可靠性，分解过程同样对待每个块元素。因此，本文首先提出一种基于扫描对重叠百分比的矩阵完成方法。通过尽可能地用可靠的块单元完成LRS矩阵，可以利用更多的相对运动的同步约束来进行配准。此外，观察到LRS矩阵中每个元素的可靠性可以通过其对应的模型和数据形状之间的关系来加以权衡。因此，设计一个权重矩阵来衡量每个元素对分解的贡献，因此分解结果比以前更接近实际情况。受益于更多信息的LRS矩阵以及权重矩阵，在若干公共数据集上进行的实验结果证明了所提出的方法相对于其他方法在精度和稳健性方面的优越性。

##### URL
[https://arxiv.org/abs/1709.08393](https://arxiv.org/abs/1709.08393)

##### PDF
[https://arxiv.org/pdf/1709.08393](https://arxiv.org/pdf/1709.08393)

