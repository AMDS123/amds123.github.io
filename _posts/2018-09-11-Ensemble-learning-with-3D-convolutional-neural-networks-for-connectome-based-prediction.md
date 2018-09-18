---
layout: post
title: "Ensemble learning with 3D convolutional neural networks for connectome-based prediction"
date: 2018-09-11 17:55:10
categories: arXiv_CV
tags: arXiv_CV CNN Classification Prediction
author: Meenakshi Khosla, Keith Jamison, Amy Kuceyeski, Mert R. Sabuncu
mathjax: true
---

* content
{:toc}

##### Abstract
The specificty and sensitivity of resting state functional MRI (rs-fMRI) measurements depend on pre-processing choices, such as the parcellation scheme used to define regions of interest (ROIs). In this study, we critically evaluate the effect of brain parcellations on machine learning models applied to rs-fMRI data. Our experiments reveal a remarkable trend: On average, models with stochastic parcellations consistently perform as well as models with widely used atlases at the same spatial scale. We thus propose an ensemble learning strategy to combine the predictions from models trained on connectivity data extracted using different (e.g., stochastic) parcellations. We further present an implementation of our ensemble learning strategy with a novel 3D Convolutional Neural Network (CNN) approach. The proposed CNN approach takes advantage of the full-resolution 3D spatial structure of rs-fMRI data and fits non-linear predictive models. Our ensemble CNN framework overcomes the limitations of traditional machine learning models for connectomes that often rely on region-based summary statistics and/or linear models. We showcase our approach on a classification (autism patients versus healthy controls) and a regression problem (prediction of subject's age), and report promising results.

##### Abstract (translated by Google)
静息状态功能MRI（rs-fMRI）测量的特异性和灵敏度取决于预处理选择，例如用于定义感兴趣区域（ROI）的分组方案。在这项研究中，我们批判性地评估了大脑包裹对应用于rs-fMRI数据的机器学习模型的影响。我们的实验揭示了一个显着的趋势：平均而言，具有随机分组的模型与在相同空间尺度上广泛使用的地图集的模型一致地表现。因此，我们提出了一种集合学习策略，以组合来自使用不同（例如，随机）分组提取的连通性数据训练的模型的预测。我们进一步介绍了我们的集成学习策略的实现与新的3D卷积神经网络（CNN）方法。所提出的CNN方法利用rs-fMRI数据的全分辨率3D空间结构并且适合非线性预测模型。我们的集合CNN框架克服了传统机器学习模型对于通常依赖基于区域的汇总统计和/或线性模型的连接组的局限性。我们展示了我们对分类（自闭症患者与健康对照）和回归问题（预测受试者年龄）的方法，并报告了有希望的结果。

##### URL
[http://arxiv.org/abs/1809.06219](http://arxiv.org/abs/1809.06219)

##### PDF
[http://arxiv.org/pdf/1809.06219](http://arxiv.org/pdf/1809.06219)

