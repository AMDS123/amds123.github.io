---
layout: post
title: "Deterministic Approximate Methods for Maximum Consensus Robust Fitting"
date: 2017-10-27 06:40:26
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Huu Le, Tat-Jun Chin, Anders Eriksson, David Suter
mathjax: true
---

* content
{:toc}

##### Abstract
Maximum consensus estimation plays a critically important role in robust fitting problems in computer vision. Currently, the most prevalent algorithms for consensus maximization draw from the class of randomized hypothesize-and-verify algorithms, which are cheap but can usually deliver only rough approximate solutions. On the other extreme, there are exact algorithms which are exhaustive search in nature and can be costly for practical-sized inputs. This paper fills the gap between the two extremes by proposing deterministic algorithms to approximately optimize the maximum consensus criterion. Our work begins by reformulating consensus maximization with linear complementarity constraints. Then, we develop two novel algorithms: one based on non-smooth penalty method with a Frank-Wolfe style optimization scheme, the other based on the Alternating Direction Method of Multipliers (ADMM). Both algorithms solve convex subproblems to efficiently perform the optimization. We demonstrate the capability of our algorithms to greatly improve a rough initial estimate, such as those obtained using least squares or a randomized algorithm. Compared to the exact algorithms, our approach is much more practical on realistic input sizes. Further, our approach is naturally applicable to estimation problems with geometric residuals

##### Abstract (translated by Google)
最大一致性估计在计算机视觉中的稳健拟合问题中起着至关重要的作用。目前，最普遍的共识最大化算法是从随机假设和验证算法中得出的，这种算法价格便宜，但通常只能提供粗略的近似解。在另一个极端，有精确的算法，这些算法在性质上是彻底的搜索，并且对于实际大小的输入可能是昂贵的。本文通过提出确定性算法来近似优化最大一致性标准来填补两个极端之间的差距。我们的工作首先用线性互补约束来重新形成共识最大化。然后，我们开发了两种新的算法：一种是基于Frank-Wolfe型优化方案的非平滑惩罚方法，另一种是基于乘法器交替方向法（ADMM）的方法。两种算法均能解决凸子问题，有效地进行优化。我们证明了我们的算法能够极大地改善粗略的初始估计，例如使用最小二乘法或随机算法获得的初始估计。与精确算法相比，我们的方法在实际输入大小上更实用。此外，我们的方法自然适用于几何残差的估计问题

##### URL
[https://arxiv.org/abs/1710.10003](https://arxiv.org/abs/1710.10003)

##### PDF
[https://arxiv.org/pdf/1710.10003](https://arxiv.org/pdf/1710.10003)

