---
layout: post
title: "Topologically Controlled Lossy Compression"
date: 2018-02-08 07:35:43
categories: arXiv_CV
tags: arXiv_CV
author: Maxime Soler, Melanie Plainchault, Bruno Conche, Julien Tierny
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new algorithm for the lossy compression of scalar data defined on 2D or 3D regular grids, with topological control. Certain techniques allow users to control the pointwise error induced by the compression. However, in many scenarios it is desirable to control in a similar way the preservation of higher-level notions, such as topological features , in order to provide guarantees on the outcome of post-hoc data analyses. This paper presents the first compression technique for scalar data which supports a strictly controlled loss of topological features. It provides users with specific guarantees both on the preservation of the important features and on the size of the smaller features destroyed during compression. In particular, we present a simple compression strategy based on a topologically adaptive quantization of the range. Our algorithm provides strong guarantees on the bottleneck distance between persistence diagrams of the input and decompressed data, specifically those associated with extrema. A simple extension of our strategy additionally enables a control on the pointwise error. We also show how to combine our approach with state-of-the-art compressors, to further improve the geometrical reconstruction. Extensive experiments, for comparable compression rates, demonstrate the superiority of our algorithm in terms of the preservation of topological features. We show the utility of our approach by illustrating the compatibility between the output of post-hoc topological data analysis pipelines, executed on the input and decompressed data, for simulated or acquired data sets. We also provide a lightweight VTK-based C++ implementation of our approach for reproduction purposes.

##### Abstract (translated by Google)
本文提出了一种新的二维或三维网格标量数据有损压缩算法，并进行拓扑控制。某些技术允许用户控制由压缩引起的逐点误差。但是，在许多情况下，为了保证事后数据分析的结果，需要以类似的方式控制高级概念（如拓扑特征）的保留。本文首次提出了标量数据压缩技术，该技术支持严格控制的拓扑特征损失。它为用户提供了重要特征的保存以及在压缩过程中被破坏的较小特征的大小。特别是，我们提出了一个简单的压缩策略，基于范围的拓扑自适应量化。我们的算法为输入和解压缩数据的持久性图之间的瓶颈距离提供了有力的保证，特别是那些与极值有关的持久性图。我们的战略的一个简单的扩展另外使得对逐点错误的控制成为可能。我们还展示了如何将我们的方法与最先进的压缩机相结合，以进一步改善几何重建。对于可比较的压缩率的大量实验证明了我们的算法在保留拓扑特征方面的优越性。通过说明在输入和解压缩数据上执行的事后拓扑数据分析流水线的输出与模拟或采集数据集之间的兼容性，我们展示了我们的方法的实用性。我们还提供了一个轻量级的基于VTK的C ++实现方法，用于复制目的。

##### URL
[http://arxiv.org/abs/1802.02731](http://arxiv.org/abs/1802.02731)

##### PDF
[http://arxiv.org/pdf/1802.02731](http://arxiv.org/pdf/1802.02731)

