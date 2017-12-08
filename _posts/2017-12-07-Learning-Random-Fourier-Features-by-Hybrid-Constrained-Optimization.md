---
layout: post
title: "Learning Random Fourier Features by Hybrid Constrained Optimization"
date: 2017-12-07 08:07:26
categories: arXiv_CV
tags: arXiv_CV Embedding Optimization
author: Jianqiao Wangni, Jingwei Zhuo, Jun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
The kernel embedding algorithm is an important component for adapting kernel methods to large datasets. Since the algorithm consumes a major computation cost in the testing phase, we propose a novel teacher-learner framework of learning computation-efficient kernel embeddings from specific data. In the framework, the high-precision embeddings (teacher) transfer the data information to the computation-efficient kernel embeddings (learner). We jointly select informative embedding functions and pursue an orthogonal transformation between two embeddings. We propose a novel approach of constrained variational expectation maximization (CVEM), where the alternate direction method of multiplier (ADMM) is applied over a nonconvex domain in the maximization step. We also propose two specific formulations based on the prevalent Random Fourier Feature (RFF), the masked and blocked version of Computation-Efficient RFF (CERF), by imposing a random binary mask or a block structure on the transformation matrix. By empirical studies of several applications on different real-world datasets, we demonstrate that the CERF significantly improves the performance of kernel methods upon the RFF, under certain arithmetic operation requirements, and suitable for structured matrix multiplication in Fastfood type algorithms.

##### Abstract (translated by Google)
内核嵌入算法是将内核方法适配到大型数据集的重要组件。由于该算法在测试阶段占用了大量的计算成本，因此提出了一种新颖的学习者学习者框架 - 从特定数据中学习高效的内核嵌入。在该框架中，高精度嵌入（教师）将数据信息传递给计算高效的内核嵌入（学习者）。我们共同选择信息嵌入函数，并在两个嵌入之间进行正交变换。我们提出了一种约束变分期望最大化（CVEM）的新方法，其中乘法器（ADMM）的交替方向方法应用于最大化步骤中的非凸区域。我们还通过在变换矩阵上施加随机二进制掩码或块结构，基于普遍的随机傅里叶特征（RFF）（计算高效的RFF（CERF）的掩蔽版本和阻塞版本）提出两个具体的表达式。通过对不同实际数据集上的几种应用的实证研究，证明了CERF在一定的算术运算需求下，显着提高了RFF上核方法的性能，适用于快餐型算法的结构化矩阵乘法。

##### URL
[http://arxiv.org/abs/1712.02527](http://arxiv.org/abs/1712.02527)

##### PDF
[http://arxiv.org/pdf/1712.02527](http://arxiv.org/pdf/1712.02527)

