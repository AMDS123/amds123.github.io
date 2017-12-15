---
layout: post
title: "Graph Construction with Label Information for Semi-Supervised Learning"
date: 2017-02-12 22:20:26
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Liansheng Zhuang, Zihan Zhou, Jingwen Yin, Shenghua Gao, Zhouchen Lin, Yi Ma, Nenghai Yu
mathjax: true
---

* content
{:toc}

##### Abstract
In the literature, most existing graph-based semi-supervised learning (SSL) methods only use the label information of observed samples in the label propagation stage, while ignoring such valuable information when learning the graph. In this paper, we argue that it is beneficial to consider the label information in the graph learning stage. Specifically, by enforcing the weight of edges between labeled samples of different classes to be zero, we explicitly incorporate the label information into the state-of-the-art graph learning methods, such as the Low-Rank Representation (LRR), and propose a novel semi-supervised graph learning method called Semi-Supervised Low-Rank Representation (SSLRR). This results in a convex optimization problem with linear constraints, which can be solved by the linearized alternating direction method. Though we take LRR as an example, our proposed method is in fact very general and can be applied to any self-representation graph learning methods. Experiment results on both synthetic and real datasets demonstrate that the proposed graph learning method can better capture the global geometric structure of the data, and therefore is more effective for semi-supervised learning tasks.

##### Abstract (translated by Google)
在文献中，大多数现有的基于图的半监督学习（SSL）方法只是在标签传播阶段使用观察样本的标签信息，而在学习图时忽略这些有价值的信息。在本文中，我们认为在图学习阶段考虑标签信息是有益的。具体而言，通过将不同类别的标记样本之间的边缘的权重强制为零，我们明确地将标签信息并入最先进的图形学习方法，诸如低位表示（LRR），并且提出一种称为半监督低秩表示（SSLRR）的新型半监督图学习方法。这导致线性约束的凸优化问题，这可以通过线性交替方向方法来解决。虽然我们以LRR为例，但是我们提出的方法实际上是非常普遍的，可以应用于任何自我表示的图形学习方法。在合成和实际数据集上的实验结果表明，所提出的图学习方法能更好地捕捉数据的全局几何结构，因此对半监督学习任务更有效。

##### URL
[https://arxiv.org/abs/1607.02539](https://arxiv.org/abs/1607.02539)

##### PDF
[https://arxiv.org/e-print/1607.02539](https://arxiv.org/e-print/1607.02539)

