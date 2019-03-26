---
layout: post
title: "CoSegNet: Deep Co-Segmentation of 3D Shapes with Group Consistency Loss"
date: 2019-03-25 13:14:23
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Quantitative
author: Chenyang Zhu, Kai Xu, Siddhartha Chaudhuri, Li Yi, Leonidas Guibas, Hao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce CoSegNet, a deep neural network architecture for co-segmentation of a set of 3D shapes represented as point clouds. CoSegNet takes as input a set of unsegmented shapes, proposes per-shape parts, and then jointly optimizes the part labelings across the set subjected to a novel group consistency loss expressed via matrix rank estimates. The proposals are refined in each iteration by an auxiliary network that acts as a weak regularizing prior, pre-trained to denoise noisy, unlabeled parts from a large collection of segmented 3D shapes, where the part compositions within the same object category can be highly inconsistent. The output is a consistent part labeling for the input set, with each shape segmented into up to K (a user-specified hyperparameter) parts. The overall pipeline is thus weakly supervised, producing consistent segmentations tailored to the test set, without consistent ground-truth segmentations. We show qualitative and quantitative results from CoSegNet and evaluate it via ablation studies and comparisons to state-of-the-art co-segmentation methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10297](http://arxiv.org/abs/1903.10297)

##### PDF
[http://arxiv.org/pdf/1903.10297](http://arxiv.org/pdf/1903.10297)

