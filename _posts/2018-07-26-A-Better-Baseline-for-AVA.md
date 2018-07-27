---
layout: post
title: "A Better Baseline for AVA"
date: 2018-07-26 11:11:25
categories: arXiv_CV
tags: arXiv_CV Detection
author: Rohit Girdhar, Jo&#xe3;o Carreira, Carl Doersch, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a simple baseline for action localization on the AVA dataset. The model builds upon the Faster R-CNN bounding box detection framework, adapted to operate on pure spatiotemporal features - in our case produced exclusively by an I3D model pretrained on Kinetics. This model obtains 21.9% average AP on the validation set of AVA v2.1, up from 14.5% for the best RGB spatiotemporal model used in the original AVA paper (which was pretrained on Kinetics and ImageNet), and up from 11.3 of the publicly available baseline using a ResNet101 image feature extractor, that was pretrained on ImageNet. Our final model obtains 22.8%/21.9% mAP on the val/test sets and outperforms all submissions to the AVA challenge at CVPR 2018.

##### Abstract (translated by Google)
我们在AVA数据集上引入了一个简单的动作本地化基线。该模型建立在更快的R-CNN边界框检测框架之上，适用于纯时空特征 - 在我们的案例中，仅由在动力学上预先训练的I3D模型生成。该模型在AVA v2.1验证集上获得21.9％的平均AP，而原始AVA论文（在Kinetics和ImageNet上预先训练）中使用的最佳RGB时空模型的平均AP为14.5％，而公开的11.3使用在ImageNet上预训练的ResNet101图像特征提取器的可用基线。我们的最终模型在val /测试集上获得了22.8％/ 21.9％mAP，并且优于在CVPR 2018中对AVA挑战的所有提交。

##### URL
[http://arxiv.org/abs/1807.10066](http://arxiv.org/abs/1807.10066)

##### PDF
[http://arxiv.org/pdf/1807.10066](http://arxiv.org/pdf/1807.10066)

