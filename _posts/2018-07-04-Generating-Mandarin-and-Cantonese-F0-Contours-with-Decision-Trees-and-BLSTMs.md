---
layout: post
title: "Generating Mandarin and Cantonese F0 Contours with Decision Trees and BLSTMs"
date: 2018-07-04 17:04:14
categories: arXiv_CL
tags: arXiv_CL Regularization RNN Relation
author: Weidong Yuan, Alan W Black
mathjax: true
---

* content
{:toc}

##### Abstract
This paper models the fundamental frequency contours on both Mandarin and Cantonese speech with decision trees and DNNs (deep neural networks). Different kinds of f0 representations and model architectures are tested for decision trees and DNNs. A new model called Additive-BLSTM (additive bidirectional long short term memory) that predicts a base f0 contour and a residual f0 contour with two BLSTMs is proposed. With respect to objective measures of RMSE and correlation, applying tone-dependent trees together with sample normalization and delta feature regularization within decision tree framework performs best. While the new Additive-BLSTM model with delta feature regularization performs even better. Subjective listening tests on both Mandarin and Cantonese comparing Random Forest model (multiple decision trees) and the Additive-BLSTM model were also held and confirmed the advantage of the new model according to the listeners' preference.

##### Abstract (translated by Google)
本文利用决策树和DNN（深度神经网络）对普通话和广东话语音的基频轮廓进行建模。针对决策树和DNN测试不同种类的f0表示和模型体系结构。提出了一种名为Additive-BLSTM（加性双向长短期记忆）的新模型，该模型用两个BLSTM预测基本f0轮廓和残余f0轮廓。关于RMSE和相关性的客观测量，在决策树框架内应用与音调相关的树以及样本归一化和delta特征正则化表现最佳。虽然具有delta功能正则化的新Additive-BLSTM模型表现更好。普通话和广东话比较随机森林模型（多决策树）和Additive-BLSTM模型的主观听力测试也得到了保证，并根据听众的偏好确认了新模型的优势。

##### URL
[http://arxiv.org/abs/1807.01682](http://arxiv.org/abs/1807.01682)

##### PDF
[http://arxiv.org/pdf/1807.01682](http://arxiv.org/pdf/1807.01682)

