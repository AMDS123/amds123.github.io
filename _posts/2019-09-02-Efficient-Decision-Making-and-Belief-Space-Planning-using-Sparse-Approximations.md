---
layout: post
title: "Efficient Decision Making and Belief Space Planning using Sparse Approximations"
date: 2019-09-02 23:00:59
categories: arXiv_AI
tags: arXiv_AI Sparse Inference SLAM
author: Khen Elimelech, Vadim Indelman
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we introduce a new approach for the efficient solution of autonomous decision and planning problems, with a special focus on decision making under uncertainty and belief space planning (BSP) in high-dimensional state spaces. Usually, to solve the decision problem, we identify the optimal action, according to some objective function. Instead, we claim that we can sometimes generate and solve an analogous yet simplified decision problem, which can be solved more efficiently. Furthermore, a wise simplification method can lead to the same action selection, or one for which the maximal loss can be guaranteed. This simplification is separated from the state inference, and does not compromise its accuracy, as the selected action would finally be applied on the original state. At first, we develop the concept for general decision problems, and provide a theoretical framework of definitions to allow a coherent discussion. We then practically apply these ideas to BSP problems, in which the problem is simplified by considering a sparse approximation of the initial belief. The scalable sparsification algorithm we provide is able to yield solutions which are guaranteed to be consistent with the original problem. We demonstrate the benefits of the approach in the solution of a highly realistic active-SLAM problem, and manage to significantly reduce computation time, with practically no loss in the quality of solution. This rigorous and fundamental work is conceptually novel, and holds numerous possible extensions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00885](http://arxiv.org/abs/1909.00885)

##### PDF
[http://arxiv.org/pdf/1909.00885](http://arxiv.org/pdf/1909.00885)

