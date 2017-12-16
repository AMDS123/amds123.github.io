---
layout: post
title: "A Deep Learning Approach for Population Estimation from Satellite Imagery"
date: 2017-08-30 02:05:16
categories: arXiv_CV
tags: arXiv_CV Survey CNN Deep_Learning Prediction Quantitative
author: Caleb Robinson, Fred Hohman, Bistra Dilkina
mathjax: true
---

* content
{:toc}

##### Abstract
Knowing where people live is a fundamental component of many decision making processes such as urban development, infectious disease containment, evacuation planning, risk management, conservation planning, and more. While bottom-up, survey driven censuses can provide a comprehensive view into the population landscape of a country, they are expensive to realize, are infrequently performed, and only provide population counts over broad areas. Population disaggregation techniques and population projection methods individually address these shortcomings, but also have shortcomings of their own. To jointly answer the questions of "where do people live" and "how many people live there," we propose a deep learning model for creating high-resolution population estimations from satellite imagery. Specifically, we train convolutional neural networks to predict population in the USA at a $0.01^{\circ} \times 0.01^{\circ}$ resolution grid from 1-year composite Landsat imagery. We validate these models in two ways: quantitatively, by comparing our model's grid cell estimates aggregated at a county-level to several US Census county-level population projections, and qualitatively, by directly interpreting the model's predictions in terms of the satellite image inputs. We find that aggregating our model's estimates gives comparable results to the Census county-level population projections and that the predictions made by our model can be directly interpreted, which give it advantages over traditional population disaggregation methods. In general, our model is an example of how machine learning techniques can be an effective tool for extracting information from inherently unstructured, remotely sensed data to provide effective solutions to social problems.

##### Abstract (translated by Google)
了解人们居住的地方是许多决策过程的基本组成部分，如城市发展，传染病控制，疏散规划，风险管理，保护规划等等。自下而上的调查驱动的人口普查可以全面地反映一个国家的人口状况，但实现起来很昂贵，而且很少进行，只能提供广泛的人口数量。人口分解技术和人口预测方法分别解决了这些缺点，但也有其自身的缺陷。为了共同回答“人在哪里”和“有多少人住在这里”的问题，我们提出了一个深度学习模型，用于从卫星图像创建高分辨率的人口估计。具体来说，我们训练卷积神经网络来预测美国的人口，从1年的综合Landsat图像中以0.01美元/圈的分辨率网格进行预测。我们通过两种方法来验证这些模型：定量地将我们模型的县级网格单元估算与美国几个人口普查县级人口预测进行比较，然后通过直接解释模型对卫星图像输入的预测来定性地进行验证。我们发现，将我们模型的估计值进行汇总，可以得出类似于普查县级人口预测的结果，并且可以直接解释我们模型的预测结果，这比传统的人口分类方法更具优势。一般来说，我们的模型是机器学习技术如何成为从固有的非结构化，遥感数据中提取信息，为社会问题提供有效解决方案的有效工具。

##### URL
[https://arxiv.org/abs/1708.09086](https://arxiv.org/abs/1708.09086)

##### PDF
[https://arxiv.org/pdf/1708.09086](https://arxiv.org/pdf/1708.09086)

