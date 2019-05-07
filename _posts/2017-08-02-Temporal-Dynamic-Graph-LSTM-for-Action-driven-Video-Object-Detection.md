---
layout: post
title: "Temporal Dynamic Graph LSTM for Action-driven Video Object Detection"
date: 2017-08-02 09:38:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge RNN Detection Relation Recognition
author: Yuan Yuan, Xiaodan Liang, Xiaolong Wang, Dit-Yan Yeung, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we investigate a weakly-supervised object detection framework. Most existing frameworks focus on using static images to learn object detectors. However, these detectors often fail to generalize to videos because of the existing domain shift. Therefore, we investigate learning these detectors directly from boring videos of daily activities. Instead of using bounding boxes, we explore the use of action descriptions as supervision since they are relatively easy to gather. A common issue, however, is that objects of interest that are not involved in human actions are often absent in global action descriptions known as "missing label". To tackle this problem, we propose a novel temporal dynamic graph Long Short-Term Memory network (TD-Graph LSTM). TD-Graph LSTM enables global temporal reasoning by constructing a dynamic graph that is based on temporal correlations of object proposals and spans the entire video. The missing label issue for each individual frame can thus be significantly alleviated by transferring knowledge across correlated objects proposals in the whole video. Extensive evaluations on a large-scale daily-life action dataset (i.e., Charades) demonstrates the superiority of our proposed method. We also release object bounding-box annotations for more than 5,000 frames in Charades. We believe this annotated data can also benefit other research on video-based object recognition in the future.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.00666](https://arxiv.org/abs/1708.00666)

##### PDF
[https://arxiv.org/pdf/1708.00666](https://arxiv.org/pdf/1708.00666)

