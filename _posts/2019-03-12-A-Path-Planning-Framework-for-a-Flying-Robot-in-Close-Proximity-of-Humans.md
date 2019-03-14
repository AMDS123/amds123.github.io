---
layout: post
title: "A Path Planning Framework for a Flying Robot in Close Proximity of Humans"
date: 2019-03-12 19:10:50
categories: arXiv_RO
tags: arXiv_RO Attention
author: Hyung-Jin Yoon, Christopher Widdowson, Thiago Marinho, Ranxiao Frances Wang, Naira Hovakimyan
mathjax: true
---

* content
{:toc}

##### Abstract
We present a path planning framework that takes into account the human's safety perception in the presence of a flying robot. The framework addresses two objectives: (i) estimation of the uncertain parameters of the proposed safety perception model based on test data collected using Virtual Reality (VR) testbed, and (ii) offline optimal control computation using the estimated safety perception model. Due to the unknown factors in the human tests data, it is not suitable to use standard regression techniques that minimize the mean squared error (MSE). We propose to use a Hidden Markov model (HMM) approach where human's attention is considered as a hidden state to infer whether the data samples are relevant to learn the safety perception model. The HMM approach improved log-likelihood over the standard least squares solution. For path planning, we use Bernstein polynomials for discretization, as the resulting path remains within the convex hull of the control points, providing guarantees for deconfliction with obstacles at low computational cost. An example of optimal trajectory generation using the learned human model is presented. The optimal trajectory generated using the proposed model results in reasonable safety distance from the human. In contrast, the paths generated using the standard regression model have undesirable shapes due to overfitting. The example demonstrates that the HMM approach has robustness to the unknown factors compared to the standard MSE model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05156](http://arxiv.org/abs/1903.05156)

##### PDF
[http://arxiv.org/pdf/1903.05156](http://arxiv.org/pdf/1903.05156)

