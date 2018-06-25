---
layout: post
title: "Faster Learning by Reduction of Data Access Time"
date: 2018-06-22 07:38:28
categories: arXiv_AI
tags: arXiv_AI Tracking
author: Vinod Kumar Chauhan, Anuj Sharma, Kalpana Dahiya
mathjax: true
---

* content
{:toc}

##### Abstract
Nowadays, the major challenge in machine learning is the Big Data challenge. The big data problems due to large number of data points or large number of features in each data point, or both, the training of models have become very slow. The training time has two major components: Time to access the data and time to process (learn from) the data. So far, the research has focused only on the second part, i.e., learning from the data. In this paper, we have proposed one possible solution to handle the big data problems in machine learning. The idea is to reduce the training time through reducing data access time by proposing systematic sampling and cyclic/sequential sampling to select mini-batches from the dataset. To prove the effectiveness of proposed sampling techniques, we have used Empirical Risk Minimization, which is commonly used machine learning problem, for strongly convex and smooth case. The problem has been solved using SAG, SAGA, SVRG, SAAG-II and MBSGD (Mini-batched SGD), each using two step determination techniques, namely, constant step size and backtracking line search method. Theoretical results prove the same convergence for systematic sampling, cyclic sampling and the widely used random sampling technique, in expectation. Experimental results with bench marked datasets prove the efficacy of the proposed sampling techniques and show up to six times faster training.

##### Abstract (translated by Google)
如今，机器学习面临的主要挑战是大数据挑战。由于大量数据点或每个数据点中的大量特征或两者造成的大数据问题，模型的训练变得非常缓慢。培训时间有两个主要部分：访问数据的时间和处理（学习）数据的时间。到目前为止，这项研究只侧重于第二部分，即从数据中学习。在本文中，我们提出了一种可能的解决方案来处理机器学习中的大数据问题。这个想法是通过提出系统采样和循环/连续采样来从数据集中选择小批量，通过减少数据访问时间来缩短培训时间。为了证明所提出的抽样技术的有效性，我们使用经验风险最小化，这是常用的机器学习问题，用于强凸和平滑情况。使用SAG，SAGA，SVRG，SAAG-II和MBSGD（小批量SGD）解决了这个问题，每个都使用两步测定技术，即恒定步长和回溯线搜索方法。理论结果证明，系统采样，循环采样和广泛使用的随机采样技术在期望方面具有相同的收敛性。使用基准标记数据集的实验结果证明了所提出的抽样技术的有效性，并且显示了快6倍的训练。

##### URL
[http://arxiv.org/abs/1801.05931](http://arxiv.org/abs/1801.05931)

##### PDF
[http://arxiv.org/pdf/1801.05931](http://arxiv.org/pdf/1801.05931)

