---
layout: post
title: "Visual-Inertial Object Detection and Mapping"
date: 2018-06-22 05:29:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Detection
author: Xiaohan Fei, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to populate an unknown environment with models of previously seen objects, placed in a Euclidean reference frame that is inferred causally and on-line using monocular video along with inertial sensors. The system we implement returns a sparse point cloud for the regions of the scene that are visible but not recognized as a previously seen object, and a detailed object model and its pose in the Euclidean frame otherwise. The system includes bottom-up and top-down components, whereby deep networks trained for detection provide likelihood scores for object hypotheses provided by a nonlinear filter, whose state serves as memory. Additional networks provide likelihood scores for edges, which complements detection networks trained to be invariant to small deformations. We test our algorithm on existing datasets, and also introduce the VISMA dataset, that provides ground truth pose, point-cloud map, and object models, along with time-stamped inertial measurements.

##### Abstract (translated by Google)
我们提出一种方法，用先前看到的物体的模型填充未知环境，放置在欧几里德参考框架中，该参考框架使用单眼视频与惯性传感器一起在因果上和在线上推断。我们实现的系统返回一个稀疏点云，用于场景中可见但未被识别为先前看到的对象的区域，以及详细的对象模型及其在欧几里得帧中的姿态。该系统包括自下而上和自上而下的组件，由此经过训练用于检测的深度网络提供由非线性滤波器（其状态用作存储器）提供的对象假设的似然分数。额外的网络为边缘提供了可能性分数，这补充了被训练成对小变形不变的检测网络。我们在现有数据集上测试我们的算法，并介绍VISMA数据集，该数据集提供了地面实况姿势，点云图和对象模型，以及时间戳惯性测量。

##### URL
[http://arxiv.org/abs/1806.08498](http://arxiv.org/abs/1806.08498)

##### PDF
[http://arxiv.org/pdf/1806.08498](http://arxiv.org/pdf/1806.08498)

