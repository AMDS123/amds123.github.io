---
layout: post
title: "Graph Neural Tangent Kernel: Fusing Graph Neural Networks with Graph Kernels"
date: 2019-05-30 17:23:23
categories: arXiv_AI
tags: arXiv_AI Classification Gradient_Descent
author: Simon S. Du, Kangcheng Hou, Barnab&#xe1;s P&#xf3;czos, Ruslan Salakhutdinov, Ruosong Wang, Keyulu Xu
mathjax: true
---

* content
{:toc}

##### Abstract
While graph kernels (GKs) are easy to train and enjoy provable theoretical guarantees, their practical performances are limited by their expressive power, as the kernel function often depends on hand-crafted combinatorial features of graphs. Compared to graph kernels, graph neural networks (GNNs) usually achieve better practical performance, as GNNs use multi-layer architectures and non-linear activation functions to extract high-order information of graphs as features. However, due to the large number of hyper-parameters and the non-convex nature of the training procedure, GNNs are harder to train. Theoretical guarantees of GNNs are also not well-understood. Furthermore, the expressive power of GNNs scales with the number of parameters, and thus it is hard to exploit the full power of GNNs when computing resources are limited. The current paper presents a new class of graph kernels, Graph Neural Tangent Kernels (GNTKs), which correspond to \emph{infinitely wide} multi-layer GNNs trained by gradient descent. GNTKs enjoy the full expressive power of GNNs and inherit advantages of GKs. Theoretically, we show GNTKs provably learn a class of smooth functions on graphs. Empirically, we test GNTKs on graph classification datasets and show they achieve strong performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13192](http://arxiv.org/abs/1905.13192)

##### PDF
[http://arxiv.org/pdf/1905.13192](http://arxiv.org/pdf/1905.13192)

