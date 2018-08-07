---
layout: post
title: "Learning from Ambiguously Labeled Face Images"
date: 2017-07-01 05:35:22
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Caption
author: Ching-Hui Chen, Vishal M. Patel, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a classifier from ambiguously labeled face images is challenging since training images are not always explicitly-labeled. For instance, face images of two persons in a news photo are not explicitly labeled by their names in the caption. We propose a Matrix Completion for Ambiguity Resolution (MCar) method for predicting the actual labels from ambiguously labeled images. This step is followed by learning a standard supervised classifier from the disambiguated labels to classify new images. To prevent the majority labels from dominating the result of MCar, we generalize MCar to a weighted MCar (WMCar) that handles label imbalance. Since WMCar outputs a soft labeling vector of reduced ambiguity for each instance, we can iteratively refine it by feeding it as the input to WMCar. Nevertheless, such an iterative implementation can be affected by the noisy soft labeling vectors, and thus the performance may degrade. Our proposed Iterative Candidate Elimination (ICE) procedure makes the iterative ambiguity resolution possible by gradually eliminating a portion of least likely candidates in ambiguously labeled face. We further extend MCar to incorporate the labeling constraints between instances when such prior knowledge is available. Compared to existing methods, our approach demonstrates improvement on several ambiguously labeled datasets.

##### Abstract (translated by Google)
从模糊标记的面部图像学习分类器是具有挑战性的，因为训练图像并不总是被明确标记。例如，新闻照片中两个人的面部图像没有通过标题中的名称明确标记。我们提出了一种用于模糊度分辨率的矩阵完成（MCar）方法，用于预测来自模糊标记图像的实际标签。该步骤之后是从消除歧义的标签中学习标准监督分类器以对新图像进行分类。为了防止大多数标签主导MCar的结果，我们将MCar推广到处理标签不平衡的加权MCar（WMCar）。由于WMCar为每个实例输出一个降低模糊度的软标记向量，我们可以通过将其作为输入提供给WMCar来迭代地对其进行细化。然而，这种迭代实现可能受到噪声软标记向量的影响，因此性能可能降低。我们提出的迭代候选消除（ICE）过程通过逐渐消除模糊标记的面部中的最不可能候选者的一部分来使得迭代模糊度解决成为可能。我们进一步扩展MCar以在可获得此类先验知识的实例之间纳入标签约束。与现有方法相比，我们的方法证明了对几个模糊标记数据集的改进。

##### URL
[https://arxiv.org/abs/1702.04455](https://arxiv.org/abs/1702.04455)

##### PDF
[https://arxiv.org/pdf/1702.04455](https://arxiv.org/pdf/1702.04455)

