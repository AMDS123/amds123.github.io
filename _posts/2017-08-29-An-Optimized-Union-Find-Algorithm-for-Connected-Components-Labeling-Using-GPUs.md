---
layout: post
title: "An Optimized Union-Find Algorithm for Connected Components Labeling Using GPUs"
date: 2017-08-29 00:54:28
categories: arXiv_CV
tags: arXiv_CV
author: Jun Chen, Qiang Yao, Houari Sabirin, Keisuke Nonaka, Hiroshi Sankoh, Sei Naito
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we report an optimized union-find (UF) algorithm that can label the connected components on a 2D image efficiently by employing the GPU architecture. The proposed method contains three phases: UF-based local merge, boundary analysis, and link. The coarse labeling in local merge reduces the number atomic operations, while the boundary analysis only manages the pixels on the boundary of each block. Evaluation results showed that the proposed algorithm speed up the average running time by more than 1.3X.

##### Abstract (translated by Google)
在本文中，我们报告了一种优化的联合发现（UF）算法，可以通过采用GPU架构有效地在二维图像上标记连接组件。所提出的方法包含三个阶段：基于UF的本地合并，边界分析和链接。局部合并中的粗标记减少了原子操作的数量，而边界分析仅处理每个块的边界上的像素。评估结果表明，该算法加速平均运行时间超过1.3倍。

##### URL
[https://arxiv.org/abs/1708.08180](https://arxiv.org/abs/1708.08180)

##### PDF
[https://arxiv.org/pdf/1708.08180](https://arxiv.org/pdf/1708.08180)

