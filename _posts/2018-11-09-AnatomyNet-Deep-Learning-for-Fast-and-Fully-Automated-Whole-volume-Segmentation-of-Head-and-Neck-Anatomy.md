---
layout: post
title: "AnatomyNet: Deep Learning for Fast and Fully Automated Whole-volume Segmentation of Head and Neck Anatomy"
date: 2018-11-09 00:23:48
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning
author: Wentao Zhu, Yufang Huang, Liang Zeng, Xuming Chen, Yong Liu, Zhen Qian, Nan Du, Wei Fan, Xiaohui Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Methods: Our deep learning model, called AnatomyNet, segments OARs from head and neck CT images in an end-to-end fashion, receiving whole-volume HaN CT images as input and generating masks of all OARs of interest in one shot. AnatomyNet is built upon the popular 3D U-net architecture, but extends it in three important ways: 1) a new encoding scheme to allow auto-segmentation on whole-volume CT images instead of local patches or subsets of slices, 2) incorporating 3D squeeze-and-excitation residual blocks in encoding layers for better feature representation, and 3) a new loss function combining Dice scores and focal loss to facilitate the training of the neural model. These features are designed to address two main challenges in deep-learning-based HaN segmentation: a) segmenting small anatomies (i.e., optic chiasm and optic nerves) occupying only a few slices, and b) training with inconsistent data annotations with missing ground truth for some anatomical structures. 
 Results: We collected 261 HaN CT images to train AnatomyNet, and used MICCAI Head and Neck Auto Segmentation Challenge 2015 as a benchmark dataset to evaluate the performance of AnatomyNet. The objective is to segment nine anatomies: brain stem, chiasm, mandible, optic nerve left, optic nerve right, parotid gland left, parotid gland right, submandibular gland left, and submandibular gland right. Compared to previous state-of-the-art results from the MICCAI 2015 competition, AnatomyNet increases Dice similarity coefficient by 3.3% on average. AnatomyNet takes about 0.12 seconds to fully segment a head and neck CT image of dimension 178 x 302 x 225, significantly faster than previous methods. In addition, the model is able to process whole-volume CT images and delineate all OARs in one pass, requiring little pre- or post-processing. https://github.com/wentaozhu/AnatomyNet-for-anatomical-segmentation.git.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.05238](http://arxiv.org/abs/1808.05238)

##### PDF
[http://arxiv.org/pdf/1808.05238](http://arxiv.org/pdf/1808.05238)

