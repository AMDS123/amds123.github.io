---
layout: post
title: "Noise Contrastive Estimation and Negative Sampling for Conditional Models: Consistency and Statistical Efficiency"
date: 2018-09-06 04:11:46
categories: arXiv_CL
tags: arXiv_CL Classification Language_Model
author: Zhuang Ma, Michael Collins
mathjax: true
---

* content
{:toc}

##### Abstract
Noise Contrastive Estimation (NCE) is a powerful parameter estimation method for log-linear models, which avoids calculation of the partition function or its derivatives at each training step, a computationally demanding step in many cases. It is closely related to negative sampling methods, now widely used in NLP. This paper considers NCE-based estimation of conditional models. Conditional models are frequently encountered in practice; however there has not been a rigorous theoretical analysis of NCE in this setting, and we will argue there are subtle but important questions when generalizing NCE to the conditional case. In particular, we analyze two variants of NCE for conditional models: one based on a classification objective, the other based on a ranking objective. We show that the ranking-based variant of NCE gives consistent parameter estimates under weaker assumptions than the classification-based method; we analyze the statistical efficiency of the ranking-based and classification-based variants of NCE; finally we describe experiments on synthetic data and language modeling showing the effectiveness and trade-offs of both methods.

##### Abstract (translated by Google)
噪声对比度估计（NCE）是对数线性模型的一种强大的参数估计方法，它避免了在每个训练步骤中计算分区函数或其导数，在许多情况下这是一个计算要求很高的步骤。它与负采样方法密切相关，现在广泛用于NLP。本文考虑了基于NCE的条件模型估计。在实践中经常遇到条件模型;然而，在这种情况下，没有对NCE进行严格的理论分析，我们认为在将NCE概括为有条件的情况时，存在微妙但重要的问题。特别是，我们分析了条件模型的两种NCE变体：一种基于分类目标，另一种基于分级目标。我们表明，基于排序的NCE变体在弱假设下给出一致的参数估计，而不是基于分类的方法;我们分析了基于排名和基于分类的NCE变体的统计效率;最后，我们描述了合成数据和语言建模的实验，显示了两种方法的有效性和权衡。

##### URL
[http://arxiv.org/abs/1809.01812](http://arxiv.org/abs/1809.01812)

##### PDF
[http://arxiv.org/pdf/1809.01812](http://arxiv.org/pdf/1809.01812)

