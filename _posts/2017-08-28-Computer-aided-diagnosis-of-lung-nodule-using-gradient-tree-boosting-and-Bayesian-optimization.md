---
layout: post
title: "Computer-aided diagnosis of lung nodule using gradient tree boosting and Bayesian optimization"
date: 2017-08-28 11:52:13
categories: arXiv_CV
tags: arXiv_CV Optimization Classification
author: Mizuho Nishio, Mitsuo Nishizawa, Osamu Sugiyama, Ryosuke Kojima, Masahiro Yakami, Tomohiro Kuroda, Kaori Togashi
mathjax: true
---

* content
{:toc}

##### Abstract
We aimed to evaluate computer-aided diagnosis (CADx) system for lung nodule classification focusing on (i) usefulness of gradient tree boosting (XGBoost) and (ii) effectiveness of parameter optimization using Bayesian optimization (Tree Parzen Estimator, TPE) and random search. 99 lung nodules (62 lung cancers and 37 benign lung nodules) were included from public databases of CT images. A variant of local binary pattern was used for calculating feature vectors. Support vector machine (SVM) or XGBoost was trained using the feature vectors and their labels. TPE or random search was used for parameter optimization of SVM and XGBoost. Leave-one-out cross-validation was used for optimizing and evaluating the performance of our CADx system. Performance was evaluated using area under the curve (AUC) of receiver operating characteristic analysis. AUC was calculated 10 times, and its average was obtained. The best averaged AUC of SVM and XGBoost were 0.850 and 0.896, respectively; both were obtained using TPE. XGBoost was generally superior to SVM. Optimal parameters for achieving high AUC were obtained with fewer numbers of trials when using TPE, compared with random search. In conclusion, XGBoost was better than SVM for classifying lung nodules. TPE was more efficient than random search for parameter optimization.

##### Abstract (translated by Google)
我们旨在评估肺结节分类的计算机辅助诊断（CADx）系统，其重点在于：（i）梯度树增强的有效性（XGBoost）和（ii）使用贝叶斯优化（Tree Parzen Estimator，TPE）和随机搜索。从CT图像的公共数据库中包括99个肺结节（62个肺癌和37个良性肺结节）。使用局部二进制模式的变体来计算特征向量。使用特征向量及其标签对支持向量机（SVM）或XGBoost进行训练。 TPE或随机搜索用于SVM和XGBoost的参数优化。一次性交叉验证用于优化和评估CADx系统的性能。使用受试者工作特征分析的曲线下面积（AUC）评估表现。计算AUC 10次，得到平均值。 SVM和XGBoost的最佳平均AUC分别为0.850和0.896;两者都是使用TPE获得的。 XGBoost总体上优于SVM。与随机搜索相比，在使用TPE时用较少数量的试验获得了实现高AUC的最佳参数。综上所述，XGBoost在肺结节分类方面优于SVM。 TPE比随机搜索参数优化更有效。

##### URL
[https://arxiv.org/abs/1708.05897](https://arxiv.org/abs/1708.05897)

##### PDF
[https://arxiv.org/pdf/1708.05897](https://arxiv.org/pdf/1708.05897)

