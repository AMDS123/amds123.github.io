---
layout: post
title: "Infrastructure Quality Assessment in Africa using Satellite Imagery and Deep Learning"
date: 2018-06-03 23:30:01
categories: arXiv_CV
tags: arXiv_CV Survey CNN Deep_Learning Prediction
author: Barak Oshri, Annie Hu, Peter Adelson, Xiao Chen, Pascaline Dupas, Jeremy Weinstein, Marshall Burke, David Lobell, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
The UN Sustainable Development Goals allude to the importance of infrastructure quality in three of its seventeen goals. However, monitoring infrastructure quality in developing regions remains prohibitively expensive and impedes efforts to measure progress toward these goals. To this end, we investigate the use of widely available remote sensing data for the prediction of infrastructure quality in Africa. We train a convolutional neural network to predict ground truth labels from the Afrobarometer Round 6 survey using Landsat 8 and Sentinel 1 satellite imagery. 
 Our best models predict infrastructure quality with AUROC scores of 0.881 on Electricity, 0.862 on Sewerage, 0.739 on Piped Water, and 0.786 on Roads using Landsat 8. These performances are significantly better than models that leverage OpenStreetMap or nighttime light intensity on the same tasks. We also demonstrate that our trained model can accurately make predictions in an unseen country after fine-tuning on a small sample of images. Furthermore, the model can be deployed in regions with limited samples to predict infrastructure outcomes with higher performance than nearest neighbor spatial interpolation.

##### Abstract (translated by Google)
联合国可持续发展目标暗示基础设施质量在其17个目标中的三个目标的重要性。但是，监测发展中地区的基础设施质量仍然非常昂贵，并且阻碍了衡量实现这些目标进展的努力。为此，我们调查了使用广泛可用的遥感数据来预测非洲的基础设施质量。我们使用Landsat 8和Sentinel 1卫星图像训练卷积神经网络，以预测来自Afrobarometer Round 6调查的地面实况标签。
 我们最好的模型预测基础设施的质量，在电力方面AUROC得分为0.881，下水道为0.862，管道水为0.739，道路使用Landsat 8为0.786。这些表现明显优于利用OpenStreetMap或夜间光照强度完成同样任务的模型。我们还证明，我们训练有素的模型可以在对一小部分图像进行微调后，在一个看不见的国家准确地做出预测。此外，该模型可以部署在样本有限的地区，以预测基础设施结果的性能优于最近邻居空间插值。

##### URL
[http://arxiv.org/abs/1806.00894](http://arxiv.org/abs/1806.00894)

##### PDF
[http://arxiv.org/pdf/1806.00894](http://arxiv.org/pdf/1806.00894)

