---
layout: post
title: "Sample Complexity of Nonparametric Semi-Supervised Learning"
date: 2018-09-10 01:12:26
categories: arXiv_AI
tags: arXiv_AI Classification
author: Chen Dan, Liu Leqi, Bryon Aragam, Pradeep Ravikumar, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
We study the sample complexity of semi-supervised learning (SSL) and introduce new assumptions based on the mismatch between a mixture model learned from unlabeled data and the true mixture model induced by the (unknown) class conditional distributions. Under these assumptions, we establish an $\Omega(K\log K)$ labeled sample complexity bound without imposing parametric assumptions, where $K$ is the number of classes. Our results suggest that even in nonparametric settings it is possible to learn a near-optimal classifier using only a few labeled samples. Unlike previous theoretical work which focuses on binary classification, we consider general multiclass classification ($K&gt;2$), which requires solving a difficult permutation learning problem. This permutation defines a classifier whose classification error is controlled by the Wasserstein distance between mixing measures, and we provide finite-sample results characterizing the behaviour of the excess risk of this classifier. Finally, we describe three algorithms for computing these estimators based on a connection to bipartite graph matching, and perform experiments to illustrate the superiority of the MLE over the majority vote estimator.

##### Abstract (translated by Google)
我们研究半监督学习（SSL）的样本复杂性，并基于从未标记数据学习的混合模型与由（未知）类条件分布诱导的真实混合模型之间的不匹配引入新假设。在这些假设下，我们建立$ \ Omega（K \ log K）$标记的样本复杂性约束而不强加参数假设，其中$ K $是类的数量。我们的结果表明，即使在非参数设置中，也可以仅使用少量标记样本来学习近似最佳分类器。与以前关注二元分类的理论工作不同，我们考虑一般多类分类（$ K> 2 $），这需要解决困难的排列学习问题。该排列定义了一种分类器，其分类误差由混合测量之间的Wasserstein距离控制，并且我们提供表征该分类器的超额风险行为的有限样本结果。最后，我们描述了基于与二分图匹配的连接来计算这些估计器的三种算法，并进行实验以说明MLE优于多数投票估计器的优势。

##### URL
[http://arxiv.org/abs/1809.03073](http://arxiv.org/abs/1809.03073)

##### PDF
[http://arxiv.org/pdf/1809.03073](http://arxiv.org/pdf/1809.03073)

