---
layout: post
title: "Efficient Relaxations for Dense CRFs with Sparse Higher Order Potentials"
date: 2018-10-26 11:58:27
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Semantic_Segmentation Inference
author: Thomas Joy, Alban Desmaison, Thalaiyasingam Ajanthan, Rudy Bunel, Mathieu Salzmann, Pushmeet Kohli, Philip H.S. Torr, M. Pawan Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
Dense conditional random fields (CRFs) have become a popular framework for modelling several problems in computer vision such as stereo correspondence and multi-class semantic segmentation. By modelling long-range interactions, dense CRFs provide a labelling that captures finer detail than their sparse counterparts. Currently, the state-of-the-art algorithm performs mean-field inference using a filter-based method but fails to provide a strong theoretical guarantee on the quality of the solution. A question naturally arises as to whether it is possible to obtain a maximum a posteriori (MAP) estimate of a dense CRF using a principled method. Within this paper, we show that this is indeed possible. We will show that, by using a filter-based method, continuous relaxations of the MAP problem can be optimised efficiently using state-of-the-art algorithms. Specifically, we will solve a quadratic programming (QP) relaxation using the Frank-Wolfe algorithm and a linear programming (LP) relaxation by developing a proximal minimisation framework. By exploiting labelling consistency in the higher-order potentials and utilising the filter-based method, we are able to formulate the above algorithms such that each iteration has a complexity linear in the number of classes and random variables. The presented algorithms can be applied to any labelling problem using a dense CRF with sparse higher-order potentials. In this paper, we use semantic segmentation as an example application as it demonstrates the ability of the algorithm to scale to dense CRFs with large dimensions. We perform experiments on the Pascal dataset to indicate that the presented algorithms are able to attain lower energies than the mean-field inference method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.09028](http://arxiv.org/abs/1805.09028)

##### PDF
[http://arxiv.org/pdf/1805.09028](http://arxiv.org/pdf/1805.09028)

