---
layout: post
title: "Context Proposals for Saliency Detection"
date: 2018-06-27 09:11:50
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Segmentation Detection
author: Aymen Azaza, Joost van de Weijer, Ali Douik, Marc Masana
mathjax: true
---

* content
{:toc}

##### Abstract
One of the fundamental properties of a salient object region is its contrast with the immediate context. The problem is that numerous object regions exist which potentially can all be salient. One way to prevent an exhaustive search over all object regions is by using object proposal algorithms. These return a limited set of regions which are most likely to contain an object. Several saliency estimation methods have used object proposals. However, they focus on the saliency of the proposal only, and the importance of its immediate context has not been evaluated. 
 In this paper, we aim to improve salient object detection. Therefore, we extend object proposal methods with context proposals, which allow to incorporate the immediate context in the saliency computation. We propose several saliency features which are computed from the context proposals. In the experiments, we evaluate five object proposal methods for the task of saliency segmentation, and find that Multiscale Combinatorial Grouping outperforms the others. Furthermore, experiments show that the proposed context features improve performance, and that our method matches results on the FT datasets and obtains competitive results on three other datasets (PASCAL-S, MSRA-B and ECSSD).

##### Abstract (translated by Google)
显着目标区域的基本属性之一是其与直接上下文的对比。问题是存在许多可能都是显着的对象区域。阻止对所有对象区域进行穷举搜索的一种方法是使用对象提议算法。这些将返回一组最有可能包含对象的区域。一些显着性估计方法已经使用了对象提议。然而，他们只关注提案的显着性，其直接背景的重要性尚未得到评估。
 在本文中，我们旨在改善显着物体检测。因此，我们使用上下文提议来扩展对象提议方法，这允许在显着性计算中结合直接上下文。我们提出了几个显着性特征，这些特征是从上下文建议中计算出在实验中，我们评估了针对显着分割任务的五种对象提议方法，并发现多尺度组合分组优于其他方法。此外，实验表明，提出的上下文特征提高了性能，并且我们的方法匹配了FT数据集上的结果，并获得了其他三个数据集（PASCAL-S，MSRA-B和ECSSD）的竞争结果。

##### URL
[http://arxiv.org/abs/1806.10359](http://arxiv.org/abs/1806.10359)

##### PDF
[http://arxiv.org/pdf/1806.10359](http://arxiv.org/pdf/1806.10359)

