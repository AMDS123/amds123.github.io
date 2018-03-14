---
layout: post
title: "Multi-Sensor Conflict Measurement and Information Fusion"
date: 2018-03-12 22:10:14
categories: arXiv_AI
tags: arXiv_AI
author: Pan Wei, John E. Ball, Derek T. Anderson
mathjax: true
---

* content
{:toc}

##### Abstract
In sensing applications where multiple sensors observe the same scene, fusing sensor outputs can provide improved results. However, if some of the sensors are providing lower quality outputs, the fused results can be degraded. In this work, a multi-sensor conflict measure is proposed which estimates multi-sensor conflict by representing each sensor output as interval-valued information and examines the sensor output overlaps on all possible n-tuple sensor combinations. The conflict is based on the sizes of the intervals and how many sensors output values lie in these intervals. In this work, conflict is defined in terms of how little the output from multiple sensors overlap. That is, high degrees of overlap mean low sensor conflict, while low degrees of overlap mean high conflict. This work is a preliminary step towards a robust conflict and sensor fusion framework. In addition, a sensor fusion algorithm is proposed based on a weighted sum of sensor outputs, where the weights for each sensor diminish as the conflict measure increases. The proposed methods can be utilized to (1) assess a measure of multi-sensor conflict, and (2) improve sensor output fusion by lessening weighting for sensors with high conflict. Using this measure, a simulated example is given to explain the mechanics of calculating the conflict measure, and stereo camera 3D outputs are analyzed and fused. In the stereo camera case, the sensor output is corrupted by additive impulse noise, DC offset, and Gaussian noise. Impulse noise is common in sensors due to intermittent interference, a DC offset a sensor bias or registration error, and Gaussian noise represents a sensor output with low SNR. The results show that sensor output fusion based on the conflict measure shows improved accuracy over a simple averaging fusion strategy.

##### Abstract (translated by Google)
在多个传感器观察相同场景的传感应用中，定影传感器输出可以提供更好的结果。但是，如果某些传感器提供较低质量的输出，则融合结果可能会降低。在这项工作中，提出了一种多传感器冲突测量方法，它通过将每个传感器输出表示为区间值信息并检查所有可能的n元组传感器组合上的传感器输出重叠来估计多传感器冲突。冲突基于时间间隔的大小以及这些时间间隔内有多少个传感器输出值。在这项工作中，冲突是根据多个传感器输出重叠的程度来定义的。也就是说，高度重叠意味着低传感器冲突，而低度重叠意味着高冲突。这项工作是迈向强大的冲突和传感器融合框架的初步步骤。另外，基于传感器输出的加权和提出传感器融合算法，其中每个传感器的权重随着冲突度量的增加而减小。所提出的方法可以用来（1）评估多传感器冲突的度量，以及（2）通过减小具有高冲突的传感器的加权来改进传感器输出融合。使用这个测量，给出了一个模拟的例子来解释计算冲突测量的机制，并且立体相机3D输出被分析和融合。在立体相机的情况下，传感器输出受到加性脉冲噪声，直流偏移和高斯噪声的影响。由于间歇性干扰，直流偏移，传感器偏差或配准误差，脉冲噪声在传感器中很常见，高斯噪声代表低信噪比的传感器输出。结果表明，基于冲突测量的传感器输出融合在简单的平均融合策略上表现出提高的准确性。

##### URL
[http://arxiv.org/abs/1803.04551](http://arxiv.org/abs/1803.04551)

##### PDF
[http://arxiv.org/pdf/1803.04551](http://arxiv.org/pdf/1803.04551)

