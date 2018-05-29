---
layout: post
title: "Generalized Singular Value Thresholding"
date: 2018-05-27 05:56:25
categories: arXiv_CV
tags: arXiv_CV
author: Canyi Lu, Changbo Zhu, Chunyan Xu, Shuicheng Yan, Zhouchen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
This work studies the Generalized Singular Value Thresholding (GSVT) operator ${\text{Prox}}_{g}^{{\sigma}}(\cdot)$, \begin{equation*} 
 {\text{Prox}}_{g}^{{\sigma}}(B)=\arg\min\limits_{X}\sum_{i=1}^{m}g(\sigma_{i}(X)) + \frac{1}{2}||X-B||_{F}^{2}, \end{equation*} associated with a nonconvex function $g$ defined on the singular values of $X$. We prove that GSVT can be obtained by performing the proximal operator of $g$ (denoted as $\text{Prox}_g(\cdot)$) on the singular values since $\text{Prox}_g(\cdot)$ is monotone when $g$ is lower bounded. If the nonconvex $g$ satisfies some conditions (many popular nonconvex surrogate functions, e.g., $\ell_p$-norm, $0&lt;p&lt;1$, of $\ell_0$-norm are special cases), a general solver to find $\text{Prox}_g(b)$ is proposed for any $b\geq0$. GSVT greatly generalizes the known Singular Value Thresholding (SVT) which is a basic subroutine in many convex low rank minimization methods. We are able to solve the nonconvex low rank minimization problem by using GSVT in place of SVT.

##### Abstract (translated by Google)
本工作研究了广义奇异值阈值（GSVT）算子$ {\ text {Prox}} {{}} {{\ sigma}}（\ cdot）$，\ begin {equation *}
 {\文本{的Prox}} _ {G} ^ {{\西格玛}}（B）= \ ARG \分钟\ limits_ {X} \ sum_ {I = 1} ^ {米}克（\ sigma_ {I}（与在$ X $的奇异值上定义的非凸函数$ g $相关联的）\ + frac {1} {2} || XB || _ {F} ^ {2}，\ end {equation *}。由于$ \ text {Prox} _g（\ cdot）$是奇异值，我们证明GSVT可以通过$ g $（表示为$ \ text {Prox} _g（\ cdot）$）当$ g $下限时是单调的。如果非凸$ g $满足一些条件（许多流行的非凸代理函数，例如，$ \ ell_p $ -norm，$ 0 <p <1 $，$ \ ell_0 $ -norm是特殊情况），则寻找一般求解器$ \ text {Prox} _g（b）$被建议用于任何$ b \ geq0 $。 GSVT极大地推广了已知的奇异值阈值（SVT），它是许多凸低秩最小化方法中的基本子程序。我们能够通过使用GSVT代替SVT来解决非凸低秩最小化问题。

##### URL
[http://arxiv.org/abs/1412.2231](http://arxiv.org/abs/1412.2231)

##### PDF
[http://arxiv.org/pdf/1412.2231](http://arxiv.org/pdf/1412.2231)

