---
layout: post
title: "The Topology ToolKit"
date: 2018-05-22 10:27:24
categories: arXiv_CV
tags: arXiv_CV Face
author: Julien Tierny, Guillaume Favelier, Joshua A. Levine, Charles Gueunet, Michael Michaux
mathjax: true
---

* content
{:toc}

##### Abstract
This system paper presents the Topology ToolKit (TTK), a software platform designed for topological data analysis in scientific visualization. TTK provides a unified, generic, efficient, and robust implementation of key algorithms for the topological analysis of scalar data, including: critical points, integral lines, persistence diagrams, persistence curves, merge trees, contour trees, Morse-Smale complexes, fiber surfaces, continuous scatterplots, Jacobi sets, Reeb spaces, and more. TTK is easily accessible to end users due to a tight integration with ParaView. It is also easily accessible to developers through a variety of bindings (Python, VTK/C++) for fast prototyping or through direct, dependence-free, C++, to ease integration into pre-existing complex systems. While developing TTK, we faced several algorithmic and software engineering challenges, which we document in this paper. In particular, we present an algorithm for the construction of a discrete gradient that complies to the critical points extracted in the piecewise-linear setting. This algorithm guarantees a combinatorial consistency across the topological abstractions supported by TTK, and importantly, a unified implementation of topological data simplification for multi-scale exploration and analysis. We also present a cached triangulation data structure, that supports time efficient and generic traversals, which self-adjusts its memory usage on demand for input simplicial meshes and which implicitly emulates a triangulation for regular grids with no memory overhead. Finally, we describe an original software architecture, which guarantees memory efficient and direct accesses to TTK features, while still allowing for researchers powerful and easy bindings and extensions. TTK is open source (BSD license) and its code, online documentation and video tutorials are available on TTK's website.

##### Abstract (translated by Google)
本系统文章介绍了拓扑工具包（TTK），这是一种用于科学可视化拓扑数据分析的软件平台。 TTK为标量数据的拓扑分析提供统一的，通用的，高效的和可靠的关键算法实现，包括：临界点，积分线，持久性图，持久性曲线，合并树，等高线树，Morse-Smale复合体，纤维表面，连续散点图，雅可比集，Reeb空间等等。由于与ParaView紧密集成，终端用户可轻松访问TTK。开发人员还可以通过各种绑定（Python，VTK / C ++）轻松实现快速原型开发，或通过直接，无依赖关系的C ++轻松访问，以便轻松集成到预先存在的复杂系统中。在开发TTK的同时，我们遇到了几个算法和软件工程方面的挑战，我们在本文中对此进行了介绍。具体而言，我们提出了一种构建离散梯度的算法，该算法符合分段线性设置中提取的临界点。该算法保证了TTK支持的拓扑抽象的组合一致性，重要的是统一实现了多尺度探索和分析的拓扑数据简化。我们还提供了一个缓存的三角测量数据结构，该结构支持时间有效和通用的遍历，根据输入单纯网格的需求自动调整其内存使用量，并隐式模拟常规网格的三角剖分，无内存开销。最后，我们描述了一个原始的软件架构，它保证了对TTK特性的内存有效和直接的访问，同时仍然为研究人员提供了强大而简单的绑定和扩展。 TTK是开源的（BSD许可证），其代码，在线文档和视频教程可在TTK网站上获得。

##### URL
[http://arxiv.org/abs/1805.09110](http://arxiv.org/abs/1805.09110)

##### PDF
[http://arxiv.org/pdf/1805.09110](http://arxiv.org/pdf/1805.09110)

