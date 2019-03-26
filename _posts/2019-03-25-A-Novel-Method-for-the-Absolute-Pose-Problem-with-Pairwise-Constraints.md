---
layout: post
title: "A Novel Method for the Absolute Pose Problem with Pairwise Constraints"
date: 2019-03-25 08:37:49
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Yinlong Liu, Xuechen Li, Manning Wang, Guang Chen, Zhijian Song, Alois Knoll
mathjax: true
---

* content
{:toc}

##### Abstract
Absolute pose estimation is a fundamental problem in computer vision, and it is a typical parameter estimation problem, meaning that efforts to solve it will always suffer from outlier-contaminated data. Conventionally, for a fixed dimensionality d and the number of measurements N, a robust estimation problem cannot be solved faster than O(N^d). Furthermore, it is almost impossible to remove d from the exponent of the runtime of a globally optimal algorithm. However, absolute pose estimation is a geometric parameter estimation problem, and thus has special constraints. In this paper, we consider pairwise constraints and propose a globally optimal algorithm for solving the absolute pose estimation problem. The proposed algorithm has a linear complexity in the number of correspondences at a given outlier ratio. Concretely, we first decouple the rotation and the translation subproblems by utilizing the pairwise constraints, and then we solve the rotation subproblem using the branch-and-bound algorithm. Lastly, we estimate the translation based on the known rotation by using another branch-and-bound algorithm. The advantages of our method are demonstrated via thorough testing on both synthetic and real-world data

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10175](http://arxiv.org/abs/1903.10175)

##### PDF
[http://arxiv.org/pdf/1903.10175](http://arxiv.org/pdf/1903.10175)

