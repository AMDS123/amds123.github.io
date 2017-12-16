---
layout: post
title: "Feedback-Controlled Sequential Lasso Screening"
date: 2016-08-25 22:52:30
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Yun Wang, Xu Chen, Peter J. Ramadge
mathjax: true
---

* content
{:toc}

##### Abstract
One way to solve lasso problems when the dictionary does not fit into available memory is to first screen the dictionary to remove unneeded features. Prior research has shown that sequential screening methods offer the greatest promise in this endeavor. Most existing work on sequential screening targets the context of tuning parameter selection, where one screens and solves a sequence of $N$ lasso problems with a fixed grid of geometrically spaced regularization parameters. In contrast, we focus on the scenario where a target regularization parameter has already been chosen via cross-validated model selection, and we then need to solve many lasso instances using this fixed value. In this context, we propose and explore a feedback controlled sequential screening scheme. Feedback is used at each iteration to select the next problem to be solved. This allows the sequence of problems to be adapted to the instance presented and the number of intermediate problems to be automatically selected. We demonstrate our feedback scheme using several datasets including a dictionary of approximate size 100,000 by 300,000.

##### Abstract (translated by Google)
解决套索问题的一种方法是当字典不适合可用内存时，首先要屏蔽字典以删除不需要的功能。先前的研究已经表明，顺序筛选方法在这一努力中提供了最大的希望。大多数现有的顺序筛选工作都是针对调整参数选择的背景下进行的，其中用几何间隔正则化参数的固定网格来筛选和解决一系列$ N $ lasso问题。相反，我们关注的是通过交叉验证模型选择已经选择目标正则化参数的场景，然后我们需要使用这个固定值来解决许多套索实例。在这种情况下，我们提出并探索一个反馈控制顺序筛选方案。在每次迭代中使用反馈来选择下一个要解决的问题。这可以使问题序列适应所提供的实例以及自动选择的中间问题的数量。我们使用几个数据集来展示我们的反馈方案，其中包括大约100,000到300,000的字典。

##### URL
[https://arxiv.org/abs/1608.06010](https://arxiv.org/abs/1608.06010)

##### PDF
[https://arxiv.org/pdf/1608.06010](https://arxiv.org/pdf/1608.06010)

