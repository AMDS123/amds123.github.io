---
layout: post
title: "Multi-View Dynamic Facial Action Unit Detection"
date: 2018-08-20 13:05:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Classification Detection Recognition
author: Andres Romero, Juan Leon, Pablo Arbelaez
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel convolutional neural network approach to address the fine-grained recognition problem of multi-view dynamic facial action unit detection. We leverage recent gains in large-scale object recognition by formulating the task of predicting the presence or absence of a specific action unit in a still image of a human face as holistic classification. We then explore the design space of our approach by considering both shared and independent representations for separate action units, and also different CNN architectures for combining color and motion information. We then move to the novel setup of the FERA 2017 Challenge, in which we propose a multi-view extension of our approach that operates by first predicting the viewpoint from which the video was taken, and then evaluating an ensemble of action unit detectors that were trained for that specific viewpoint. Our approach is holistic, efficient, and modular, since new action units can be easily included in the overall system. Our approach significantly outperforms the baseline of the FERA 2017 Challenge, with an absolute improvement of 14% on the F1-metric. Additionally, it compares favorably against the winner of the FERA 2017 challenge. Code source is available at https://github.com/BCV-Uniandes/AUNets.

##### Abstract (translated by Google)
我们提出了一种新颖的卷积神经网络方法来解决多视图动态面部动作单元检测的细粒度识别问题。我们通过制定预测人脸静止图像中特定动作单元的存在或不存在作为整体分类的任务来利用近期在大规模物体识别中的增益。然后，我们通过考虑单独的动作单元的共享和独立表示以及用于组合颜色和运动信息的不同CNN架构来探索我们的方法的设计空间。然后我们转到2017年FERA挑战赛的新颖设置，其中我们提出了一种多视图扩展我们的方法，首先预测视频拍摄的视点，然后评估一组动作单元探测器。针对该特定观点进行培训。我们的方法是整体的，高效的和模块化的，因为新的动作单元可以很容易地包含在整个系统中。我们的方法明显优于FERA 2017 Challenge的基线，F1指标的绝对改善率为14％。此外，它与2017年口交挑战赛的获胜者相比毫不逊色。代码源位于https://github.com/BCV-Uniandes/AUNets。

##### URL
[http://arxiv.org/abs/1704.07863](http://arxiv.org/abs/1704.07863)

##### PDF
[http://arxiv.org/pdf/1704.07863](http://arxiv.org/pdf/1704.07863)

