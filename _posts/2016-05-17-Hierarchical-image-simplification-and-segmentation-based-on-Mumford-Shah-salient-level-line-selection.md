---
layout: post
title: "Hierarchical image simplification and segmentation based on Mumford-Shah-salient level line selection"
date: 2016-05-17 14:38:04
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Optimization Quantitative
author: Yongchao Xu (LRDE, LIGM, TSI), Thierry Géraud (LRDE), Laurent Najman (LIGM)
mathjax: true
---

* content
{:toc}

##### Abstract
Hierarchies, such as the tree of shapes, are popular representations for image simplification and segmentation thanks to their multiscale structures. Selecting meaningful level lines (boundaries of shapes) yields to simplify image while preserving intact salient structures. Many image simplification and segmentation methods are driven by the optimization of an energy functional, for instance the celebrated Mumford-Shah functional. In this paper, we propose an efficient approach to hierarchical image simplification and segmentation based on the minimization of the piecewise-constant Mumford-Shah functional. This method conforms to the current trend that consists in producing hierarchical results rather than a unique partition. Contrary to classical approaches which compute optimal hierarchical segmentations from an input hierarchy of segmentations, we rely on the tree of shapes, a unique and well-defined representation equivalent to the image. Simply put, we compute for each level line of the image an attribute function that characterizes its persistence under the energy minimization. Then we stack the level lines from meaningless ones to salient ones through a saliency map based on extinction values defined on the tree-based shape space. Qualitative illustrations and quantitative evaluation on Weizmann segmentation evaluation database demonstrate the state-of-the-art performance of our method.

##### Abstract (translated by Google)
诸如形状树之类的层次结构由于其多尺度结构而成为图像简化和分割的流行表示。选择有意义的水平线（形状边界）可以简化图像，同时保留完整的显着结构。许多图像简化和分割方法是由能量功能的优化驱动的，例如着名的Mumford-Shah功能。在本文中，我们提出了一种有效的分层图像简化和分割的方法，基于分段常数Mumford-Shah函数的最小化。这种方法符合当前的趋势，即生成分层结果而不是唯一的分区。与经典的方法相比，这些方法根据分割的输入层次来计算最佳的分层分割，我们依赖于形状树，这是一种与图像等效的独特且定义明确的表示。简而言之，我们计算图像的每个级别线的一个属性函数，表征其在能量最小化下的持久性。然后，我们通过基于树状形状空间上定义的消失值的显着图，将无意义层面的层次线叠加到显着层面。对Weizmann分割评估数据库进行定性的插图和定量评估证明了我们方法的最新性能。

##### URL
[https://arxiv.org/abs/1603.04838](https://arxiv.org/abs/1603.04838)

##### PDF
[https://arxiv.org/pdf/1603.04838](https://arxiv.org/pdf/1603.04838)

