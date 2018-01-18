---
layout: post
title: "Faster gaze prediction with dense networks and Fisher pruning"
date: 2018-01-17 18:34:33
categories: arXiv_CV
tags: arXiv_CV Salient Knowledge Prediction Recognition
author: Lucas Theis, Iryna Korshunova, Alykhan Tejani, Ferenc Husz&#xe1;r
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting human fixations from images has recently seen large improvements by leveraging deep representations which were pretrained for object recognition. However, as we show in this paper, these networks are highly overparameterized for the task of fixation prediction. We first present a simple yet principled greedy pruning method which we call Fisher pruning. Through a combination of knowledge distillation and Fisher pruning, we obtain much more runtime-efficient architectures for saliency prediction, achieving a 10x speedup for the same AUC performance as a state of the art network on the CAT2000 dataset. Speeding up single-image gaze prediction is important for many real-world applications, but it is also a crucial step in the development of video saliency models, where the amount of data to be processed is substantially larger.

##### Abstract (translated by Google)
从图像中预测人类的注意力最近已经通过利用深度表示来预测人类的注意力，这些深度表示被预训练用于对象识别。然而，正如我们在本文中所展示的，这些网络对于固定预测的任务是高度超参数化的。我们首先提出一个简单而有原则的贪婪修剪方法，我们称之为修剪。通过结合知识蒸馏和费舍尔修剪，我们获得了更多的运行时效率显着性预测体系结构，实现了与CAT2000数据集上最先进的网络相同的AUC性能，速度提高了10倍。加速单幅图像凝视预测对于许多真实世界的应用程序是非常重要的，但它也是开发视频显着性模型的关键步骤，其中要处理的数据量要大得多。

##### URL
[http://arxiv.org/abs/1801.05787](http://arxiv.org/abs/1801.05787)

##### PDF
[http://arxiv.org/pdf/1801.05787](http://arxiv.org/pdf/1801.05787)

