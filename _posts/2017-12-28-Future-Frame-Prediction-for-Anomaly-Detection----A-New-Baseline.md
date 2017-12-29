---
layout: post
title: "Future Frame Prediction for Anomaly Detection -- A New Baseline"
date: 2017-12-28 14:04:52
categories: arXiv_CV
tags: arXiv_CV Knowledge Prediction Detection
author: Wen Liu, Weixin Luo, Dongze Lian, Shenghua Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Anomaly detection in videos refers to the identification of events that do not conform to expected behavior. However, almost all existing methods tackle the problem by minimizing the reconstruction errors of training data, which cannot guarantee a larger reconstruction error for an abnormal event. In this paper, we propose to tackle the anomaly detection problem within a video prediction framework. To the best of our knowledge, this is the first work that leverages the difference between a predicted future frame and its ground truth to detect an abnormal event. To predict a future frame with higher quality for normal events, other than the commonly used appearance (spatial) constraints on intensity and gradient, we also introduce a motion (temporal) constraint in video prediction by enforcing the optical flow between predicted frames and ground truth frames to be consistent, and this is the first work that introduces a temporal constraint into the video prediction task. Such spatial and motion constraints facilitate the future frame prediction for normal events, and consequently facilitate to identify those abnormal events that do not conform the expectation. Extensive experiments on both a toy dataset and some publicly available datasets validate the effectiveness of our method in terms of robustness to the uncertainty in normal events and the sensitivity to abnormal events

##### Abstract (translated by Google)
视频中的异常检测是指识别不符合预期行为的事件。但是，现有的几乎所有的方法都是通过最小化训练数据的重构误差来解决这个问题，这对于一个异常事件来说不能保证较大的重构误差。在本文中，我们建议在视频预测框架内解决异常检测问题。就我们所知，这是利用预测的未来框架与其基本事实之间的差异来检测异常事件的第一项工作。为了预测对于正常事件具有更高质量的未来帧，除了对强度和梯度的常用外观（空间）限制之外，还通过强化预测帧与地面真实之间的光流来在视频预测中引入运动（时间）约束帧是一致的，这是第一个将时间约束引入到视频预测任务中的工作。这样的空间和运动约束促进了正常事件的未来帧预测，并因此有助于识别那些不符合期望的异常事件。在玩具数据集和一些公开可用的数据集上的大量实验验证了我们的方法在正常事件的不确定性的鲁棒性和对异常事件的敏感性方面的有效性

##### URL
[http://arxiv.org/abs/1712.09867](http://arxiv.org/abs/1712.09867)

##### PDF
[http://arxiv.org/pdf/1712.09867](http://arxiv.org/pdf/1712.09867)

