---
layout: post
title: "End-to-End Learning Deep CRF models for Multi-Object Tracking"
date: 2019-07-29 02:27:18
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Inference RNN Detection Gradient_Descent
author: Jun Xiang, Ma Chao, Guohan Xu, Jianhua Hou
mathjax: true
---

* content
{:toc}

##### Abstract
Existing deep multi-object tracking (MOT) approaches first learn a deep representation to describe target objects and then associate detection results by optimizing a linear assignment problem. Despite demonstrated successes, it is challenging to discriminate target objects under mutual occlusion or to reduce identity switches in crowded scenes. In this paper, we propose learning deep conditional random field (CRF) networks, aiming to model the assignment costs as unary potentials and the long-term dependencies among detection results as pairwise potentials. Specifically, we use a bidirectional long short-term memory (LSTM) network to encode the long-term dependencies. We pose the CRF inference as a recurrent neural network learning process using the standard gradient descent algorithm, where unary and pairwise potentials are jointly optimized in an end-to-end manner. Extensive experimental results on the challenging MOT datasets including MOT-2015 and MOT-2016, demonstrate that our approach achieves the state of the art performances in comparison with published works on both benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12176](http://arxiv.org/abs/1907.12176)

##### PDF
[http://arxiv.org/pdf/1907.12176](http://arxiv.org/pdf/1907.12176)

