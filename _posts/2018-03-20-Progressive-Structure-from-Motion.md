---
layout: post
title: "Progressive Structure from Motion"
date: 2018-03-20 10:25:06
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Alex Locher, Michal Havlena, Luc Van Gool (ETH Z&#xfc;rich)
mathjax: true
---

* content
{:toc}

##### Abstract
Structure from Motion or the sparse 3D reconstruction out of individual photos is a long studied topic in computer vision. Yet none of the existing reconstruction pipelines fully addresses a progressive scenario where images are only getting available during the reconstruction process and intermediate results are delivered to the user. Incremental pipelines are capable of growing a 3D model but often get stuck in local minima due to wrong (binding) decisions taken based on incomplete information. Global pipelines on the other hand need the access to the complete viewgraph and are not capable of delivering intermediate results. In this paper we propose a new reconstruction pipeline working in a progressive manner rather than in a batch processing scheme. The pipeline is able to recover from failed reconstructions in early stages, avoids to take binding decisions, delivers a progressive output and yet maintains the capabilities of existing pipelines. We demonstrate and evaluate our method on diverse challenging public and dedicated datasets including those with highly symmetric structures and compare to the state of the art.

##### Abstract (translated by Google)
运动结构或个人照片中的稀疏三维重建是计算机视觉领域一个长期研究的课题。然而，现有的重建管线没有一个完全解决了在重建过程中只能获得图像并将中间结果传递给用户的渐进式场景。增量管道能够增长3D模型，但由于基于不完整的信息做出错误（有约束力的）决定，往往会陷入局部极小值。另一方面，全球管道需要访问完整的视图，并且不能提供中间结果。在本文中，我们提出了一种以渐进方式工作的新重建流水线，而不是批处理方案。管道能够在早期阶段从失败的重建中恢复，避免做出具有约束力的决定，提供渐进式输出并保持现有管道的功能。我们在多种具有挑战性的公共和专用数据集上展示和评估我们的方法，包括那些具有高度对称结构并与现有技术状态相比较的数据集。

##### URL
[http://arxiv.org/abs/1803.07349](http://arxiv.org/abs/1803.07349)

##### PDF
[http://arxiv.org/pdf/1803.07349](http://arxiv.org/pdf/1803.07349)

