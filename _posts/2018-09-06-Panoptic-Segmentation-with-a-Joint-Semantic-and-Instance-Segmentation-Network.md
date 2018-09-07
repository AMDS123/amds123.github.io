---
layout: post
title: "Panoptic Segmentation with a Joint Semantic and Instance Segmentation Network"
date: 2018-09-06 17:35:39
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Prediction Recognition
author: Daan de Geus, Panagiotis Meletis, Gijs Dubbelman
mathjax: true
---

* content
{:toc}

##### Abstract
We present an end-to-end method for the task of panoptic segmentation. The method makes instance segmentation and semantic segmentation predictions in a single network, and combines these outputs using heuristics to create a single panoptic segmentation output. The architecture consists of a ResNet-50 feature extractor shared by the semantic segmentation and instance segmentation branch. For instance segmentation, a Mask R-CNN type of architecture is used, while the semantic segmentation branch is augmented with a Pyramid Pooling Module. Results for this method are submitted to the COCO and Mapillary Joint Recognition Challenge 2018. Our approach achieves a PQ score of 17.6 on the Mapillary Vistas validation set and 27.2 on the COCO test-dev set.

##### Abstract (translated by Google)
我们提出了一种用于全景分割任务的端到端方法。该方法在单个网络中进行实例分割和语义分割预测，并使用启发法将这些输出组合以创建单个全景分割输出。该体系结构由语义分段和实例分段分支共享的ResNet-50特征提取器组成。例如，使用Mask R-CNN类型的体系结构，而使用金字塔池模块来增强语义分割分支。该方法的结果提交给COCO和Mapillary Joint Recognition Challenge 2018.我们的方法在Mapillary Vistas验证集上获得了17.6的PQ得分，在COCO测试开发集上得到了27.2。

##### URL
[http://arxiv.org/abs/1809.02110](http://arxiv.org/abs/1809.02110)

##### PDF
[http://arxiv.org/pdf/1809.02110](http://arxiv.org/pdf/1809.02110)

