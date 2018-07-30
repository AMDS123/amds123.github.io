---
layout: post
title: "Sparse Range-constrained Learning and Its Application for Medical Image Grading"
date: 2018-07-11 06:59:45
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Jun Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Sparse learning has been shown to be effective in solving many real-world problems. Finding sparse representations is a fundamentally important topic in many fields of science including signal processing, computer vision, genome study and medical imaging. One important issue in applying sparse representation is to find the basis to represent the data,especially in computer vision and medical imaging where the data is not necessary incoherent. In medical imaging, clinicians often grade the severity or measure the risk score of a disease based on images. This process is referred to as medical image grading. Manual grading of the disease severity or risk score is often used. However, it is tedious, subjective and expensive. Sparse learning has been used for automatic grading of medical images for different diseases. In the grading, we usually begin with one step to find a sparse representation of the testing image using a set of reference images or atoms from the dictionary. Then in the second step, the selected atoms are used as references to compute the grades of the testing images. Since the two steps are conducted sequentially, the objective function in the first step is not necessarily optimized for the second step. In this paper, we propose a novel sparse range-constrained learning(SRCL)algorithm for medical image grading.Different from most of existing sparse learning algorithms, SRCL integrates the objective of finding a sparse representation and that of grading the image into one function. It aims to find a sparse representation of the testing image based on atoms that are most similar in both the data or feature representation and the medical grading scores. We apply the new proposed SRCL to CDR computation and cataract grading. Experimental results show that the proposed method is able to improve the accuracy in cup-to-disc ratio computation and cataract grading.

##### Abstract (translated by Google)
稀疏学习已被证明在解决许多现实问题方面是有效的。寻找稀疏表示是许多科学领域中的一个基本重要的主题，包括信号处理，计算机视觉，基因组研究和医学成像。应用稀疏表示的一个重要问题是找到表示数据的基础，特别是在计算机视觉和医学成像中，其中数据不是必需的。在医学成像中，临床医生通常根据图像对严重程度进行评分或测量疾病的风险评分。该过程称为医学图像分级。通常使用人工分级的疾病严重程度或风险评分。然而，这是乏味的，主观的和昂贵的。稀疏学习已被用于针对不同疾病的医学图像的自动分级。在评分中，我们通常从一步开始，使用一组参考图像或字典中的原子来查找测试图像的稀疏表示。然后在第二步中，将所选原子用作参考来计算测试图像的等级。由于这两个步骤是顺序进行的，因此第一步骤中的目标函数不一定针对第二步骤进行优化。在本文中，我们提出了一种新的稀疏距离约束学习（SRCL）算法用于医学图像分级。与大多数现有的稀疏学习算法不同，SRCL集成了寻找稀疏表示和将图像分级为一个函数的目标。它旨在基于在数据或特征表示和医学评分分数中最相似的原子来找到测试图像的稀疏表示。我们将新提出的SRCL应用于CDR计算和白内障分级。实验结果表明，该方法能够提高杯盘比率计算和白内障分级的准确性。

##### URL
[http://arxiv.org/abs/1807.10571](http://arxiv.org/abs/1807.10571)

##### PDF
[http://arxiv.org/pdf/1807.10571](http://arxiv.org/pdf/1807.10571)

