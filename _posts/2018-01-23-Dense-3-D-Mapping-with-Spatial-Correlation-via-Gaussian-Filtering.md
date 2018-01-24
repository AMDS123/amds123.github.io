---
layout: post
title: "Dense 3-D Mapping with Spatial Correlation via Gaussian Filtering"
date: 2018-01-23 02:59:07
categories: arXiv_RO
tags: arXiv_RO Classification Relation
author: Ke Sun, Kelsey Saulnier, Nikolay Atanasov, George J. Pappas, Vijay Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
Constructing an occupancy representation of the environment is a fundamental problem for robot autonomy. Many accurate and efficient methods exist that address this problem but most assume that the occupancy states of different elements in the map representation are statistically independent. The focus of this paper is to provide a model that captures correlation of the occupancy of map elements. Correlation is important not only for improved accuracy but also for quantifying uncertainty in the map and for planning autonomous mapping trajectories based on the correlation among known and unknown areas. Recent work proposes Gaussian Process (GP) regression to capture covariance information and enable resolution-free occupancy estimation. The drawback of techniques based on GP regression (or classification) is that the computation complexity scales cubically with the length of the measurement history. Our main contribution is a new approach for occupancy mapping that models the binary nature of occupancy measurements precisely, via a Bernoulli distribution, and provides an efficient approximation of GP classification with complexity that does not scale with time. We prove that the error between the estimates provided by our method and those provided by GP classification is negligible. The proposed method is evaluated using both simulated data and real data collected using a Velodyne Puck 3-D range sensor.

##### Abstract (translated by Google)
构建环境占用表示是机器人自主性的一个基本问题。存在许多准确和有效的方法来解决这个问题，但是大多数假定地图表示中的不同元素的占用状态在统计上是独立的。本文的重点是提供一个捕捉地图元素占有率相关性的模型。相关性不仅对于提高准确性非常重要，而且对于量化地图中的不确定性以及基于已知和未知地区之间的相关性来规划自主映射轨迹而言也是重要的。最近的工作提出了高斯过程（GP）回归来捕获协方差信息并实现无分辨率占用估计。基于GP回归（或分类）的技术的缺点是计算复杂性与测量历史的长度立方成比例。我们的主要贡献是通过伯努利（Bernoulli）分布精确地模拟占用测量的二进制特性，并提供GP分类的高效近似，其中复杂度不随时间缩放。我们证明了我们的方法提供的估计与GP分类提供的估计之间的误差是可以忽略的。所提出的方法使用模拟数据和使用Velodyne Puck 3-D距离传感器收集的实际数据进行评估。

##### URL
[http://arxiv.org/abs/1801.07380](http://arxiv.org/abs/1801.07380)

##### PDF
[http://arxiv.org/pdf/1801.07380](http://arxiv.org/pdf/1801.07380)

