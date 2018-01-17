---
layout: post
title: "An octree cells occupancy geometric dimensionality descriptor for massive on-server point cloud visualisation and classification"
date: 2018-01-15 21:40:24
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Classification Detection
author: Remi Cura, Julien Perret, Nicolas Paparoditis
mathjax: true
---

* content
{:toc}

##### Abstract
Lidar datasets are becoming more and more common. They are appreciated for their precise 3D nature, and have a wide range of applications, such as surface reconstruction, object detection, visualisation, etc. For all this applications, having additional semantic information per point has potential of increasing the quality and the efficiency of the application. In the last decade the use of Machine Learning and more specifically classification methods have proved to be successful to create this semantic information. In this paradigm, the goal is to classify points into a set of given classes (for instance tree, building, ground, other). Some of these methods use descriptors (also called feature) of a point to learn and predict its class. Designing the descriptors is then the heart of these methods. Descriptors can be based on points geometry and attributes, use contextual information, etc. Furthermore, descriptors can be used by humans for easier visual understanding and sometimes filtering. In this work we propose a new simple geometric descriptor that gives information about the implicit local dimensionality of the point cloud at various scale. For instance a tree seen from afar is more volumetric in nature (3D), yet locally each leaves is rather planar (2D). To do so we build an octree centred on the point to consider, and compare the variation of the occupancy of the cells across the levels of the octree. We compare this descriptor with the state of the art dimensionality descriptor and show its interest. We further test the descriptor for classification within the Point Cloud Server, and demonstrate efficiency and correctness results.

##### Abstract (translated by Google)
雷达数据集变得越来越普遍。它们因其精确的3D特性而受到赞赏，并且具有广泛的应用，例如表面重建，物体检测，可视化等。对于所有这些应用，每个点具有额外的语义信息有潜力提高质量和效率应用程序。在过去的十年中，使用机器学习和更具体的分类方法已被证明是成功的创造这个语义信息。在这个范例中，目标是将点分为一组给定的类（例如树，建筑物，地面等）。其中一些方法使用一个点的描述符（也称为特征）来学习和预测它的类。设计描述符是这些方法的核心。描述符可以基于点的几何形状和属性，使用上下文信息等。此外，描述符可以被人类使用，以便于视觉理解并且有时候被过滤。在这项工作中，我们提出了一个新的简单的几何描述符，给出了不同规模的点云的隐式局部维度的信息。例如，从远处看到的一棵树本质上是更大的体积（3D），但是每片叶子在本地是相当平坦的（2D）。为此，我们建立一个以考虑要点为中心的八叉树，并比较八叉树各层细胞占有率的变化。我们将这个描述符与现有的维度描述符进行比较，并显示它的兴趣。我们将进一步测试Point Cloud Server中的分类描述符，并演示效率和正确性结果。

##### URL
[http://arxiv.org/abs/1801.05038](http://arxiv.org/abs/1801.05038)

##### PDF
[http://arxiv.org/pdf/1801.05038](http://arxiv.org/pdf/1801.05038)

