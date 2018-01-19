---
layout: post
title: "Faster Algorithms for Large-scale Machine Learning using Simple Sampling Techniques"
date: 2018-01-18 04:31:40
categories: arXiv_AI
tags: arXiv_AI Tracking
author: Vinod Kumar Chauhan, Kalpana Dahiya, Anuj Sharma
mathjax: true
---

* content
{:toc}

##### Abstract
Now a days, the major challenge in machine learning is the `Big~Data' challenge. The big data problems due to large number of data points or large number of features in each data point, or both, the training of models have become very slow. The training time has two major components: Time to access the data and time to process the data. In this paper, we have proposed one possible solution to handle the big data problems in machine learning. The focus is on reducing the training time through reducing data access time by proposing systematic sampling and cyclic/sequential sampling to select mini-batches from the dataset. To prove the effectiveness of proposed sampling techniques, we have used Empirical Risk Minimization, which is commonly used machine learning problem, for strongly convex and smooth case. The problem has been solved using SAG, SAGA, SVRG, SAAG-II and MBSGD (Mini-batched SGD), each using two step determination techniques, namely, constant step size and backtracking line search method. Theoretical results prove the same convergence for systematic sampling, cyclic sampling and the widely used random sampling technique, in expectation. Experimental results with bench marked datasets prove the efficacy of the proposed sampling techniques.

##### Abstract (translated by Google)
现在机器学习面临的主要挑战是“大数据”挑战。大数据问题由于数据点数量众多或每个数据点的特征数量大，或者两者兼而有之，模型的训练变得非常缓慢。培训时间有两个主要部分：访问数据的时间和处理数据的时间。在本文中，我们提出了一个可能的解决方案来处理机器学习中的大数据问题。重点在于通过提供系统采样和循环/连续采样来从数据集中选择小批量，通过减少数据访问时间来缩短培训时间。为了证明所提出的抽样技术的有效性，我们用经验风险最小化（这是常用的机器学习问题）作为强凸和平滑的情况。使用SAG，SAGA，SVRG，SAAG-II和MBSGD（小批量SGD）已经解决了这个问题，每个都使用两步测定技术，即恒定步长和回溯线搜索方法。理论结果证明，系统采样，循环采样和广泛使用的随机采样技术在期望方面具有相同的收敛性。用标准数据集进行的实验结果证明了所提出的抽样技术的有效性。

##### URL
[http://arxiv.org/abs/1801.05931](http://arxiv.org/abs/1801.05931)

##### PDF
[http://arxiv.org/pdf/1801.05931](http://arxiv.org/pdf/1801.05931)

