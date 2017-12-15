---
layout: post
title: "Spatial Scaling of Satellite Soil Moisture using Temporal Correlations and Ensemble Learning"
date: 2016-01-21 20:19:19
categories: arXiv_CV
tags: arXiv_CV Face Relation
author: Subit Chakrabarti, Jasmeet Judge, Tara Bongiovanni, Anand Rangarajan, Sanjay Ranka
mathjax: true
---

* content
{:toc}

##### Abstract
A novel algorithm is developed to downscale soil moisture (SM), obtained at satellite scales of 10-40 km by utilizing its temporal correlations to historical auxiliary data at finer scales. Including such correlations drastically reduces the size of the training set needed, accounts for time-lagged relationships, and enables downscaling even in the presence of short gaps in the auxiliary data. The algorithm is based upon bagged regression trees (BRT) and uses correlations between high-resolution remote sensing products and SM observations. The algorithm trains multiple regression trees and automatically chooses the trees that generate the best downscaled estimates. The algorithm was evaluated using a multi-scale synthetic dataset in north central Florida for two years, including two growing seasons of corn and one growing season of cotton per year. The time-averaged error across the region was found to be 0.01 $\mathrm{m}^3/\mathrm{m}^3$, with a standard deviation of 0.012 $\mathrm{m}^3/\mathrm{m}^3$ when 0.02% of the data were used for training in addition to temporal correlations from the past seven days, and all available data from the past year. The maximum spatially averaged errors obtained using this algorithm in downscaled SM were 0.005 $\mathrm{m}^3/\mathrm{m}^3$, for pixels with cotton land-cover. When land surface temperature~(LST) on the day of downscaling was not included in the algorithm to simulate "data gaps", the spatially averaged error increased minimally by 0.015 $\mathrm{m}^3/\mathrm{m}^3$ when LST is unavailable on the day of downscaling. The results indicate that the BRT-based algorithm provides high accuracy for downscaling SM using complex non-linear spatio-temporal correlations, under heterogeneous micro meteorological conditions.

##### Abstract (translated by Google)
一种新的算法被开发来降低土壤湿度（SM），在10-40km的卫星尺度上获得，利用它与时间的相关性，以更精细的尺度的历史辅助数据。包括这样的相关性大大减少了所需的训练集的大小，考虑了时滞关系，并且即使在辅助数据中存在短缺的情况下也能够降级。该算法基于袋装回归树（BRT），并使用高分辨率遥感产品和SM观测值之间的相关性。该算法训练多个回归树，并自动选择产生最佳降尺度估计的树。该算法在佛罗里达州中北部使用多尺度合成数据集进行了两年的评估，包括两个生长季节的玉米和一个生长季节的棉花。该地区的时间平均误差为0.01 $ \ mathrm {m} ^ 3 / \ mathrm {m} ^ 3 $，标准差为0.012 $ \ mathrm {m} ^ 3 / \ mathrm {m除了过去七天的时间相关性以及过去一年的所有可用数据外，还有0.02％的数据用于培训。在缩小的SM中，使用该算法获得的最大空间平均误差对于具有棉花土地覆盖的像素是0.005 $ \ mathrm {m} ^ 3 / \ mathrm {m} ^ 3 $。当降尺度日的地表温度（LST）不包括在模拟“数据间隙”的算法中时，空间平均误差最小增加0.015 $ \ mathrm {m} ^ 3 / \ mathrm {m} ^ 3 $当LST在缩小的那一天不可用时。结果表明，基于BRT的算法在非均匀微观气象条件下，利用复杂的非线性时空相关性为SM降尺度提供了高精度。

##### URL
[https://arxiv.org/abs/1601.05767](https://arxiv.org/abs/1601.05767)

##### PDF
[https://arxiv.org/pdf/1601.05767](https://arxiv.org/pdf/1601.05767)

