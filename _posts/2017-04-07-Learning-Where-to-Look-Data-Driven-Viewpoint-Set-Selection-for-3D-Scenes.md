---
layout: post
title: "Learning Where to Look: Data-Driven Viewpoint Set Selection for 3D Scenes"
date: 2017-04-07 22:40:46
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Semantic_Segmentation
author: Kyle Genova, Manolis Savva, Angel X. Chang, Thomas Funkhouser
mathjax: true
---

* content
{:toc}

##### Abstract
The use of rendered images, whether from completely synthetic datasets or from 3D reconstructions, is increasingly prevalent in vision tasks. However, little attention has been given to how the selection of viewpoints affects the performance of rendered training sets. In this paper, we propose a data-driven approach to view set selection. Given a set of example images, we extract statistics describing their contents and generate a set of views matching the distribution of those statistics. Motivated by semantic segmentation tasks, we model the spatial distribution of each semantic object category within an image view volume. We provide a search algorithm that generates a sampling of likely candidate views according to the example distribution, and a set selection algorithm that chooses a subset of the candidates that jointly cover the example distribution. Results of experiments with these algorithms on SUNCG indicate that they are indeed able to produce view distributions similar to an example set from NYUDv2 according to the earth mover's distance. Furthermore, the selected views improve performance on semantic segmentation compared to alternative view selection algorithms.

##### Abstract (translated by Google)
渲染图像的使用，无论是从完全合成的数据集或从3D重建，在视觉任务中越来越普遍。然而，很少关注如何选择观点影响渲染训练集的性能。在本文中，我们提出了一个数据驱动的方法来查看集合的选择。给定一组示例图像，我们提取描述其内容的统计信息，并生成一组与这些统计信息相匹配的视图。受语义分割任务的驱动，我们对图像视图体内的每个语义对象类别的空间分布进行建模。我们提供一种搜索算法，根据示例分布生成可能候选视图的采样，以及选择共同覆盖示例分布的候选的子集的集合选择算法。在SUNCG上的这些算法的实验结果表明，他们确实能够根据地球移动者的距离产生类似于来自NYUDv2的示例的视图分布。此外，与其他视图选择算法相比，所选择的视图提高了语义分割的性能。

##### URL
[https://arxiv.org/abs/1704.02393](https://arxiv.org/abs/1704.02393)

##### PDF
[https://arxiv.org/pdf/1704.02393](https://arxiv.org/pdf/1704.02393)

