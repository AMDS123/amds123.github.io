---
layout: post
title: "Tensor graph convolutional neural network"
date: 2018-03-27 13:34:05
categories: arXiv_CV
tags: arXiv_CV Salient CNN Relation
author: Tong Zhang (1 and 2), Wenming Zheng (2), Zhen Cui (3), Yang Li (1 and 2) ((1) the Department of Information Science and Engineering, Southeast University, Nanjing, China (2) the Key Laboratory of Child Development and Learning Science of Ministry of Education, Research Center for Learning Science, Southeast University, Nanjing, China (3) the School of Computer Science and Engineering, Nanjing University of Science and Technology, Nanjing, China)
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel tensor graph convolutional neural network (TGCNN) to conduct convolution on factorizable graphs, for which here two types of problems are focused, one is sequential dynamic graphs and the other is cross-attribute graphs. Especially, we propose a graph preserving layer to memorize salient nodes of those factorized subgraphs, i.e. cross graph convolution and graph pooling. For cross graph convolution, a parameterized Kronecker sum operation is proposed to generate a conjunctive adjacency matrix characterizing the relationship between every pair of nodes across two subgraphs. Taking this operation, then general graph convolution may be efficiently performed followed by the composition of small matrices, which thus reduces high memory and computational burden. Encapsuling sequence graphs into a recursive learning, the dynamics of graphs can be efficiently encoded as well as the spatial layout of graphs. To validate the proposed TGCNN, experiments are conducted on skeleton action datasets as well as matrix completion dataset. The experiment results demonstrate that our method can achieve more competitive performance with the state-of-the-art methods.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的张量图卷积神经网络（TGCNN）来进行因式分解图上的卷积，这里有两类问题集中在一起，一个是序列动态图，另一个是交叉属性图。特别是，我们提出了一个图保存层来记忆那些因子化子图的显着节点，即交叉图卷积和图形池。对于交叉图卷积，提出了一种参数化Kronecker求和运算来生成表征两个子图上每对节点之间关系的连接邻接矩阵。采取这种操作，然后可以有效地执行一般图形卷积，随后是小矩阵的组合，这因此减少了高存储和计算负担。将序列图封装成递归学习，可以有效地对图的动态编码以及图的空间布局。为了验证所提出的TGCNN，对骨架动作数据集以及矩阵完成数据集进行实验。实验结果表明，我们的方法可以通过最先进的方法实现更具竞争力的性能。

##### URL
[https://arxiv.org/abs/1803.10071](https://arxiv.org/abs/1803.10071)

##### PDF
[https://arxiv.org/pdf/1803.10071](https://arxiv.org/pdf/1803.10071)

