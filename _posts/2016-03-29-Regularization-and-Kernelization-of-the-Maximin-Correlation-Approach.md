---
layout: post
title: "Regularization and Kernelization of the Maximin Correlation Approach"
date: 2016-03-29 04:42:12
categories: arXiv_CV
tags: arXiv_CV Regularization Classification Prediction Relation Recognition
author: Taehoon Lee, Taesup Moon, Seung Jean Kim, Sungroh Yoon
mathjax: true
---

* content
{:toc}

##### Abstract
Robust classification becomes challenging when each class consists of multiple subclasses. Examples include multi-font optical character recognition and automated protein function prediction. In correlation-based nearest-neighbor classification, the maximin correlation approach (MCA) provides the worst-case optimal solution by minimizing the maximum misclassification risk through an iterative procedure. Despite the optimality, the original MCA has drawbacks that have limited its wide applicability in practice. That is, the MCA tends to be sensitive to outliers, cannot effectively handle nonlinearities in datasets, and suffers from having high computational complexity. To address these limitations, we propose an improved solution, named regularized maximin correlation approach (R-MCA). We first reformulate MCA as a quadratically constrained linear programming (QCLP) problem, incorporate regularization by introducing slack variables in the primal problem of the QCLP, and derive the corresponding Lagrangian dual. The dual formulation enables us to apply the kernel trick to R-MCA so that it can better handle nonlinearities. Our experimental results demonstrate that the regularization and kernelization make the proposed R-MCA more robust and accurate for various classification tasks than the original MCA. Furthermore, when the data size or dimensionality grows, R-MCA runs substantially faster by solving either the primal or dual (whichever has a smaller variable dimension) of the QCLP.

##### Abstract (translated by Google)
当每个类由多个子类组成时，强健的分类变得具有挑战性。例子包括多字体光学字符识别和自动蛋白质功能预测。在基于相关的最近邻分类中，最大相关方法（MCA）通过迭代程序通过最小化最大错误分类风险来提供最坏情况的最优解。尽管是最优的，但最初的MCA存在缺陷，限制了其在实践中的广泛适用性。也就是说，MCA往往对异常值敏感，不能有效地处理数据集中的非线性，并且具有较高的计算复杂度。为了解决这些限制，我们提出了一种改进的解决方案，称为正则化最大相关方法（R-MCA）。我们首先将MCA重构为二次约束线性规划（QCLP）问题，在QCLP的主要问题中引入松弛变量引入正则化，导出相应的拉格朗日对偶。双重公式使我们能够将核心技巧应用于R-MCA，以便更好地处理非线性问题。我们的实验结果表明，正则化和核化使得所提出的R-MCA比原始的MCA更加健壮和准确地用于各种分类任务。此外，当数据大小或维度增长时，R-MCA通过求解QCLP的原始数据或对偶数据（无论哪一个具有较小的可变维度）运行得更快。

##### URL
[https://arxiv.org/abs/1502.06105](https://arxiv.org/abs/1502.06105)

##### PDF
[https://arxiv.org/pdf/1502.06105](https://arxiv.org/pdf/1502.06105)

