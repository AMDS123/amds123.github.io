---
layout: post
title: "Self-Learning to Detect and Segment Cysts in Lung CT Images without Manual Annotation"
date: 2018-01-25 17:02:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Deep_Learning Prediction Detection
author: Ling Zhang, Vissagan Gopalakrishnan, Le Lu, Ronald M. Summers, Joel Moss, Jianhua Yao
mathjax: true
---

* content
{:toc}

##### Abstract
Image segmentation is a fundamental problem in medical image analysis. In recent years, deep neural networks achieve impressive performances on many medical image segmentation tasks by supervised learning on large manually annotated data. However, expert annotations on big medical datasets are tedious, expensive or sometimes unavailable. Weakly supervised learning could reduce the effort for annotation but still required certain amounts of expertise. Recently, deep learning shows a potential to produce more accurate predictions than the original erroneous labels. Inspired by this, we introduce a very weakly supervised learning method, for cystic lesion detection and segmentation in lung CT images, without any manual annotation. Our method works in a self-learning manner, where segmentation generated in previous steps (first by unsupervised segmentation then by neural networks) is used as ground truth for the next level of network learning. Experiments on a cystic lung lesion dataset show that the deep learning could perform better than the initial unsupervised annotation, and progressively improve itself after self-learning.

##### Abstract (translated by Google)
图像分割是医学图像分析中的一个基本问题。近年来，深度神经网络在大量手动标注的数据上进行监督学习，在许多医学图像分割任务上实现了令人印象深刻的性能。然而，对于大型医疗数据集的专家注释非常繁琐，昂贵或者有时无法使用。弱监督学习可以减少注解的工作，但仍需要一定的专业知识。最近，深度学习显示出比原始错误标签更准确的预测。受此启发，我们引入了一种非常弱的监督学习方法，用于肺部CT图像中的囊性病变检测和分割，而没有任何手动注释。我们的方法是以自我学习的方式工作的，在前面的步骤中产生的分割（首先通过无监督分割然后通过神经网络）被用作下一级网络学习的基础事实。囊性肺病灶数据集的实验表明，深度学习可以比初始无监督注释表现更好，自学后逐渐提高。

##### URL
[http://arxiv.org/abs/1801.08486](http://arxiv.org/abs/1801.08486)

##### PDF
[http://arxiv.org/pdf/1801.08486](http://arxiv.org/pdf/1801.08486)

