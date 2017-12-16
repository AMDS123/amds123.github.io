---
layout: post
title: "Semantic 3D Occupancy Mapping through Efficient High Order CRFs"
date: 2017-07-24 03:24:52
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Optimization Inference Prediction
author: Shichao Yang, Yulan Huang, Sebastian Scherer
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic 3D mapping can be used for many applications such as robot navigation and virtual interaction. In recent years, there has been great progress in semantic segmentation and geometric 3D mapping. However, it is still challenging to combine these two tasks for accurate and large-scale semantic mapping from images. In the paper, we propose an incremental and (near) real-time semantic mapping system. A 3D scrolling occupancy grid map is built to represent the world, which is memory and computationally efficient and bounded for large scale environments. We utilize the CNN segmentation as prior prediction and further optimize 3D grid labels through a novel CRF model. Superpixels are utilized to enforce smoothness and form robust P N high order potential. An efficient mean field inference is developed for the graph optimization. We evaluate our system on the KITTI dataset and improve the segmentation accuracy by 10% over existing systems.

##### Abstract (translated by Google)
语义3D映射可用于许多应用程序，如机器人导航和虚拟交互。近年来，在语义分割和几何三维制图方面取得了很大进展。然而，将这两个任务结合起来，对图像进行准确的大规模的语义映射仍然是一个挑战。在本文中，我们提出了一个增量和（近）实时语义映射系统。构建3D滚动占用网格地图来表示世界，这是一个记忆和计算效率高的大型环境。我们利用CNN分割作为先验预测，并通过新的CRF模型进一步优化3D网格标签。超像素被用来强化光滑性并形成稳健的P N高阶势。为图优化开发了一个有效的平均场推断。我们在KITTI数据集上评估我们的系统，并将现有系统的分割精度提高了10％。

##### URL
[https://arxiv.org/abs/1707.07388](https://arxiv.org/abs/1707.07388)

##### PDF
[https://arxiv.org/pdf/1707.07388](https://arxiv.org/pdf/1707.07388)

