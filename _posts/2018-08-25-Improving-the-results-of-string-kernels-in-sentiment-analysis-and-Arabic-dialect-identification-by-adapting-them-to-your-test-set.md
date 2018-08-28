---
layout: post
title: "Improving the results of string kernels in sentiment analysis and Arabic dialect identification by adapting them to your test set"
date: 2018-08-25 11:08:28
categories: arXiv_CL
tags: arXiv_CL Sentiment Text_Classification Classification
author: Radu Tudor Ionescu, Andrei M. Butnaru
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, string kernels have obtained state-of-the-art results in various text classification tasks such as Arabic dialect identification or native language identification. In this paper, we apply two simple yet effective transductive learning approaches to further improve the results of string kernels. The first approach is based on interpreting the pairwise string kernel similarities between samples in the training set and samples in the test set as features. Our second approach is a simple self-training method based on two learning iterations. In the first iteration, a classifier is trained on the training set and tested on the test set, as usual. In the second iteration, a number of test samples (to which the classifier associated higher confidence scores) are added to the training set for another round of training. However, the ground-truth labels of the added test samples are not necessary. Instead, we use the labels predicted by the classifier in the first training iteration. By adapting string kernels to the test set, we report significantly better accuracy rates in English polarity classification and Arabic dialect identification.

##### Abstract (translated by Google)
最近，字符串内核在各种文本分类任务（例如阿拉伯语方言识别或本地语言识别）中获得了最先进的结果。在本文中，我们应用两种简单而有效的转换学习方法来进一步改进字符串内核的结果。第一种方法基于将训练集中的样本与测试集中的样本之间的成对字符串核相似性解释为特征。我们的第二种方法是基于两次学习迭代的简单自我训练方法。在第一次迭代中，像往常一样，在训练集上训练分类器并在测试集上进行测试。在第二次迭代中，将多个测试样本（分类器与较高置信度分数相关联）添加到训练集中以进行另一轮训练。但是，添加的测试样品的地面实况标签不是必需的。相反，我们在第一次训练迭代中使用分类器预测的标签。通过使字符串内核适应测试集，我们在英语极性分类和阿拉伯方言识别中报告显着更高的准确率。

##### URL
[http://arxiv.org/abs/1808.08409](http://arxiv.org/abs/1808.08409)

##### PDF
[http://arxiv.org/pdf/1808.08409](http://arxiv.org/pdf/1808.08409)

