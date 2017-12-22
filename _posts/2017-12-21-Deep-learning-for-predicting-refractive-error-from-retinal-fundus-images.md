---
layout: post
title: "Deep learning for predicting refractive error from retinal fundus images"
date: 2017-12-21 05:27:56
categories: arXiv_CV
tags: arXiv_CV Attention Deep_Learning Prediction
author: Avinash V. Varadarajan, Ryan Poplin, Katy Blumer, Christof Angermueller, Joe Ledsam, Reena Chopra, Pearse A. Keane, Greg S. Corrado, Lily Peng, Dale R. Webster
mathjax: true
---

* content
{:toc}

##### Abstract
Refractive error, one of the leading cause of visual impairment, can be corrected by simple interventions like prescribing eyeglasses. We trained a deep learning algorithm to predict refractive error from the fundus photographs from participants in the UK Biobank cohort, which were 45 degree field of view images and the AREDS clinical trial, which contained 30 degree field of view images. Our model use the "attention" method to identify features that are correlated with refractive error. Mean absolute error (MAE) of the algorithm's prediction compared to the refractive error obtained in the AREDS and UK Biobank. The resulting algorithm had a MAE of 0.56 diopters (95% CI: 0.55-0.56) for estimating spherical equivalent on the UK Biobank dataset and 0.91 diopters (95% CI: 0.89-0.92) for the AREDS dataset. The baseline expected MAE (obtained by simply predicting the mean of this population) was 1.81 diopters (95% CI: 1.79-1.84) for UK Biobank and 1.63 (95% CI: 1.60-1.67) for AREDS. Attention maps suggested that the foveal region was one of the most important areas used by the algorithm to make this prediction, though other regions also contribute to the prediction. The ability to estimate refractive error with high accuracy from retinal fundus photos has not been previously known and demonstrates that deep learning can be applied to make novel predictions from medical images. Given that several groups have recently shown that it is feasible to obtain retinal fundus photos using mobile phones and inexpensive attachments, this work may be particularly relevant in regions of the world where autorefractors may not be readily available.

##### Abstract (translated by Google)
屈光不正是导致视力损害的主要原因之一，可以通过简单的干预措施（如处方眼镜）来纠正。我们训练了一个深度学习算法来预测来自英国生物样本队列的参与者的眼底照片（45度视野图像和包含30度视野图像的AREDS临床试验）的屈光不正的预测。我们的模型使用“注意力”方法来识别与屈光不正相关的特征。算法预测的平均绝对误差（MAE）与AREDS和UK生物库中获得的屈光误差相比较。在英国Biobank数据集上估算的球面当量MAE为0.56屈光度（95％CI：0.55-0.56），AREDS数据集为0.91屈光度（95％CI：0.89-0.92）。英国生物库的基线预期MAE（通过简单预测该人群的平均值获得）为1.81屈光度（95％CI：1.79-1.84），AREDS为1.63（95％CI：1.60-1.67）。注意图表明中央凹区域是该算法用于预测的最重要的区域之一，尽管其他区域也对预测有贡献。从视网膜眼底照片以高准确度估计屈光不正的能力还没有被人们所知，这表明深度学习可以用来从医学图像中进行新的预测。鉴于最近有几个研究小组已经表明，使用手机和便宜的附件获得视网膜底片照片是可行的，这项工作可能在世界上那些自发片可能不易得到的地区特别相关。

##### URL
[http://arxiv.org/abs/1712.07798](http://arxiv.org/abs/1712.07798)

##### PDF
[http://arxiv.org/pdf/1712.07798](http://arxiv.org/pdf/1712.07798)

