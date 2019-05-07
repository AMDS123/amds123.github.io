---
layout: post
title: "Learning Hough Regression Models via Bridge Partial Least Squares for Object Detection"
date: 2016-03-26 09:33:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Jianyu Tang, Hanzi Wang, Yan Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Popular Hough Transform-based object detection approaches usually construct an appearance codebook by clustering local image features. However, how to choose appropriate values for the parameters used in the clustering step remains an open problem. Moreover, some popular histogram features extracted from overlapping image blocks may cause a high degree of redundancy and multicollinearity. In this paper, we propose a novel Hough Transform-based object detection approach. First, to address the above issues, we exploit a Bridge Partial Least Squares (BPLS) technique to establish context-encoded Hough Regression Models (HRMs), which are linear regression models that cast probabilistic Hough votes to predict object locations. BPLS is an efficient variant of Partial Least Squares (PLS). PLS-based regression techniques (including BPLS) can reduce the redundancy and eliminate the multicollinearity of a feature set. And the appropriate value of the only parameter used in PLS (i.e., the number of latent components) can be determined by using a cross-validation procedure. Second, to efficiently handle object scale changes, we propose a novel multi-scale voting scheme. In this scheme, multiple Hough images corresponding to multiple object scales can be obtained simultaneously. Third, an object in a test image may correspond to multiple true and false positive hypotheses at different scales. Based on the proposed multi-scale voting scheme, a principled strategy is proposed to fuse hypotheses to reduce false positives by evaluating normalized pointwise mutual information between hypotheses. In the experiments, we also compare the proposed HRM approach with its several variants to evaluate the influences of its components on its performance. Experimental results show that the proposed HRM approach has achieved desirable performances on popular benchmark datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1603.08092](https://arxiv.org/abs/1603.08092)

##### PDF
[https://arxiv.org/pdf/1603.08092](https://arxiv.org/pdf/1603.08092)

