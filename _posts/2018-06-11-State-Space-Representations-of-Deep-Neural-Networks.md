---
layout: post
title: "State Space Representations of Deep Neural Networks"
date: 2018-06-11 00:26:13
categories: arXiv_AI
tags: arXiv_AI Embedding
author: Michael Hauser, Sean Gunn, Samer Saab Jr, Asok Ray
mathjax: true
---

* content
{:toc}

##### Abstract
This paper deals with neural networks as dynamical systems governed by differential or difference equations. It shows that the introduction of skip connections into network architectures, such as residual networks and dense networks, turns a system of static equations into a system of dynamical equations with varying levels of smoothness on the layer-wise transformations. Closed form solutions for the state space representations of general dense networks, as well as $k^{th}$ order smooth networks, are found in general settings. Furthermore, it is shown that imposing $k^{th}$ order smoothness on a network architecture with $d$-many nodes per layer increases the state space dimension by a multiple of $k$, and so the effective embedding dimension of the data manifold is $k \cdot d$-many dimensions. It follows that network architectures of these types reduce the number of parameters needed to maintain the same embedding dimension by a factor of $k^2$ when compared to an equivalent first-order, residual network, significantly motivating the development of network architectures of these types. Numerical simulations were run to validate parts of the developed theory.

##### Abstract (translated by Google)
本文将神经网络作为由微分或差分方程控制的动力学系统。它表明，将跳转连接引入网络结构（如残余网络和密集网络）会将静态方程系统转变为动态方程系统，其中在层级转换上具有不同程度的平滑性。一般密集网络的状态空间表示以及$ k ^ {order}平滑网络的封闭形式解可以在一般设置中找到。此外，它表明，在每层$ d $ -many节点的网络体系结构中施加$ k ^ {th} $顺序的平滑度将状态空间维数增加了$ k $的倍数，因此，有效的嵌入维数数据流形是$ k \ cdot d $ -many维度。由此可见，与等效的一阶残余网络相比，这些类型的网络架构可以将维持相同嵌入维数所需的参数数量减少$ k ^ 2 $，极大地促进了这些网络架构的开发类型。运行数值模拟来验证发展理论的一部分。

##### URL
[http://arxiv.org/abs/1806.03751](http://arxiv.org/abs/1806.03751)

##### PDF
[http://arxiv.org/pdf/1806.03751](http://arxiv.org/pdf/1806.03751)

