---
layout: post
title: "Replication study: Development and validation of deep learning algorithm for detection of diabetic retinopathy in retinal fundus photographs"
date: 2018-08-30 00:28:12
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Detection
author: Mike Voets, Kajsa M&#xf8;llersen, Lars Ailo Bongo
mathjax: true
---

* content
{:toc}

##### Abstract
Replication studies are essential for validation of new methods, and are crucial to maintain the high standards of scientific publications, and to use the results in practice. We have attempted to replicate the main method in 'Development and validation of a deep learning algorithm for detection of diabetic retinopathy in retinal fundus photographs' published in JAMA 2016; 316(22). We re-implemented the method since the source code is not available, and we used publicly available data sets. The original study used non-public fundus images from EyePACS and three hospitals in India for training. We used a different EyePACS data set from Kaggle. The original study used the benchmark data set Messidor-2 to evaluate the algorithm's performance. We used the same data set. In the original study, ophthalmologists re-graded all images for diabetic retinopathy, macular edema, and image gradability. There was one diabetic retinopathy grade per image for our data sets, and we assessed image gradability ourselves. Hyper-parameter settings were not described in the original study. But some of these were later published. We were not able to replicate the original study. Our algorithm's area under the receiver operating curve (AUC) of 0.94 on the Kaggle EyePACS test set and 0.80 on Messidor-2 did not come close to the reported AUC of 0.99 in the original study. This may be caused by the use of a single grade per image, different data, or different not described hyper-parameter settings. This study shows the challenges of replicating deep learning, and the need for more replication studies to validate deep learning methods, especially for medical image analysis. 
 Our source code and instructions are available at: https://github.com/mikevoets/jama16-retina-replication

##### Abstract (translated by Google)
复制研究对于验证新方法至关重要，对于保持科学出版物的高标准以及在实践中使用结果至关重要。我们试图在JAMA 2016上发表的“视网膜眼底照片中检测糖尿病视网膜病变的深度学习算法的开发和验证”中复制主要方法; 316（22）。我们重新实现了该方法，因为源代码不可用，我们使用了公开的数据集。最初的研究使用来自EyePACS和印度三家医院的非公共眼底图像进行培训。我们使用了Kaggle的不同EyePACS数据集。最初的研究使用基准数据集Messidor-2来评估算法的性能。我们使用了相同的数据集。在最初的研究中，眼科医生重新评估了糖尿病视网膜病变，黄斑水肿和图像可分级性的所有图像。我们的数据集中每个图像有一个糖尿病视网膜病变等级，我们自己评估了图像的可分级性。原始研究中未描述超参数设置。但其中一些后来发表。我们无法复制原始研究。我们的算法在Kaggle EyePACS测试集上的接收器操作曲线（AUC）下为0.94，在Messidor-2上为0.80，在原始研究中未接近报告的AUC为0.99。这可能是由于每个图像使用单个等级，不同数据或不同的未描述的超参数设置引起的。这项研究显示了复制深度学习的挑战，以及需要更多的复制研究来验证深度学习方法，尤其是医学图像分析。
 我们的源代码和说明位于：https：//github.com/mikevoets/jama16-retina-replication

##### URL
[http://arxiv.org/abs/1803.04337](http://arxiv.org/abs/1803.04337)

##### PDF
[http://arxiv.org/pdf/1803.04337](http://arxiv.org/pdf/1803.04337)

