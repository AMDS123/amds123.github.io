---
layout: post
title: "Learning from Ambiguously Labeled Face Images"
date: 2017-07-01 05:35:22
categories: arXiv_CV
tags: arXiv_CV Caption
author: Ching-Hui Chen, Vishal M. Patel, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a classifier from ambiguously labeled face images is challenging since training images are not always explicitly-labeled. For instance, face images of two persons in a news photo are not explicitly labeled by their names in the caption. We propose a Matrix Completion for Ambiguity Resolution (MCar) method for predicting the actual labels from ambiguously labeled images. This step is followed by learning a standard supervised classifier from the disambiguated labels to classify new images. To prevent the majority labels from dominating the result of MCar, we generalize MCar to a weighted MCar (WMCar) that handles label imbalance. Since WMCar outputs a soft labeling vector of reduced ambiguity for each instance, we can iteratively refine it by feeding it as the input to WMCar. Nevertheless, such an iterative implementation can be affected by the noisy soft labeling vectors, and thus the performance may degrade. Our proposed Iterative Candidate Elimination (ICE) procedure makes the iterative ambiguity resolution possible by gradually eliminating a portion of least likely candidates in ambiguously labeled face. We further extend MCar to incorporate the labeling constraints between instances when such prior knowledge is available. Compared to existing methods, our approach demonstrates improvement on several ambiguously labeled datasets.

##### Abstract (translated by Google)
从模糊标记的脸部图像学习分类器是具有挑战性的，因为训练图像并不总是被明确地标记。例如，新闻照片中两个人的脸部图像在标题中没有明确标注他们的名字。我们提出了一个模糊解析矩阵完成（MCar）方法，用于预测含糊标签图像的实际标签。这一步之后是从消歧标签中学习一个标准的监督分类器，以分类新的图像。为了防止大多数标签主宰MCar的结果，我们将MCar推广到处理标签不平衡的加权MCar（WMCar）。由于WMCar为每个实例输出一个模糊度降低的软标签向量，我们可以通过将其作为输入提供给WMCar来迭代地细化它。然而，这样的迭代实现会受到噪声软标签向量的影响，因此性能可能会下降。我们提出的迭代候选消除（ICE）程序通过逐渐消除模糊标记脸部中最不可能的候选者的部分，使得迭代模糊度解决成为可能。我们进一步扩展MCar，在这种先验知识可用的情况下，将标签约束合并到实例之间。与现有方法相比，我们的方法在多个含糊标签的数据集上显示出改进。

##### URL
[https://arxiv.org/abs/1702.04455](https://arxiv.org/abs/1702.04455)

