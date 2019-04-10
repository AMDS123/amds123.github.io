---
layout: post
title: "SoDeep: a Sorting Deep net to learn ranking loss surrogates"
date: 2019-04-08 18:02:43
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Image_Classification Classification Relation
author: Martin Engilberge, Louis Chevallier, Patrick P&#xe9;rez, Matthieu Cord
mathjax: true
---

* content
{:toc}

##### Abstract
Several tasks in machine learning are evaluated using non-differentiable metrics such as mean average precision or Spearman correlation. However, their non-differentiability prevents from using them as objective functions in a learning framework. Surrogate and relaxation methods exist but tend to be specific to a given metric. 
 In the present work, we introduce a new method to learn approximations of such non-differentiable objective functions. Our approach is based on a deep architecture that approximates the sorting of arbitrary sets of scores. It is trained virtually for free using synthetic data. This sorting deep (SoDeep) net can then be combined in a plug-and-play manner with existing deep architectures. We demonstrate the interest of our approach in three different tasks that require ranking: Cross-modal text-image retrieval, multi-label image classification and visual memorability ranking. Our approach yields very competitive results on these three tasks, which validates the merit and the flexibility of SoDeep as a proxy for sorting operation in ranking-based losses.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04272](http://arxiv.org/abs/1904.04272)

##### PDF
[http://arxiv.org/pdf/1904.04272](http://arxiv.org/pdf/1904.04272)

