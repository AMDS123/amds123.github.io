---
layout: post
title: "Maximum Persistency via Iterative Relaxed Inference with Graphical Models"
date: 2017-02-03 13:21:01
categories: arXiv_CV
tags: arXiv_CV Inference
author: Alexander Shekhovtsov, Paul Swoboda, Bogdan Savchynskyy
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the NP-hard problem of MAP-inference for undirected discrete graphical models. We propose a polynomial time and practically efficient algorithm for finding a part of its optimal solution. Specifically, our algorithm marks some labels of the considered graphical model either as (i) optimal, meaning that they belong to all optimal solutions of the inference problem; (ii) non-optimal if they provably do not belong to any solution. With access to an exact solver of a linear programming relaxation to the MAP-inference problem, our algorithm marks the maximal possible (in a specified sense) number of labels. We also present a version of the algorithm, which has access to a suboptimal dual solver only and still can ensure the (non-)optimality for the marked labels, although the overall number of the marked labels may decrease. We propose an efficient implementation, which runs in time comparable to a single run of a suboptimal dual solver. Our method is well-scalable and shows state-of-the-art results on computational benchmarks from machine learning and computer vision.

##### Abstract (translated by Google)
我们考虑无向离散图模型的MAP推断NP难问题。我们提出一个多项式时间和实际上有效的算法找到其最优解的一部分。具体而言，我们的算法将所考虑的图形模型的一些标签标记为（i）最优的，这意味着它们属于推理问题的所有最优解; （ii）如果它们可能不属于任何解决方案，则是非最优的。通过对MAP推理问题的线性规划放松的准确求解，我们的算法标记了最大可能（在特定意义上）的标签数量。我们还提供了算法的一个版本，它只能访问一个次优的双重求解器，并且仍然可以确保标记的标签的（非）最优性，尽管标记的标签的总数可能会减少。我们提出了一个有效的实施方案，其运行时间可以与次优求解的单次运行相媲美。我们的方法具有良好的可扩展性，并显示了机器学习和计算机视觉的计算基准方面的最新成果。

##### URL
[https://arxiv.org/abs/1508.07902](https://arxiv.org/abs/1508.07902)

##### PDF
[https://arxiv.org/pdf/1508.07902](https://arxiv.org/pdf/1508.07902)

