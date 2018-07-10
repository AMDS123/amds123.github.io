---
layout: post
title: "Convolutional Recurrent Neural Networks for Blood Glucose Prediction"
date: 2018-07-09 11:12:16
categories: arXiv_CV
tags: arXiv_CV CNN RNN Prediction Relation
author: Kezhi Li, John Daniels, Pau Herrero-vi&#xf1;as, Chengyuan Liu, Pantelis Georgiou
mathjax: true
---

* content
{:toc}

##### Abstract
The main purpose of the artificial pancreas (AP) or any diabetes therapy for subjects with type 1 diabetes (T1D) is to maintain the subjects' plasma glucose level within the euglycemic range, which means below the threshold of hyperglycemia and above the threshold of hypoglycemia. The development of modern continuous glucose monitor (CGM) makes this feasible. Its continuous monitoring enables people to take actions before the hypo/hyperglycemia episodes. For this reason, an accurate blood glucose (BG) prediction is essential. It raises alarms before the real hypo/hyperglycemia scenarios and stays silent for non-hypo/non-hyperglycemia episodes. Data driven approaches have recently been widely used in statistical modelling in healthcare and medical researches, in particular deep neural network techniques. In this paper, the glucose prediction is seen as a probabilistically generative problem, and a hybrid deep neural network is proposed to combine the advantages of convolutional neural networks (CNN) and recurrent neural networks (RNN). Specifically, a multi-layer CNN is implemented as a feature extraction component, followed by a multi-layer modified long short term memory (LSTM) model to capture the probabilistic correlations between the future BG and historical BG level, meal information and insulin. The model is adaptive for the individual subject with T1D, and dropout layers are leveraged to avoid overfitting. The model is easily implemented using Tensorflow, and can be embedded to portable devices with limited computation resources. Experiments verify and evaluate the effectiveness of the proposed method using the simulated and clinical data.

##### Abstract (translated by Google)
人工胰腺（AP）或1型糖尿病（T1D）受试者的任何糖尿病治疗的主要目的是将受试者的血浆葡萄糖水平维持在正常血糖范围内，这意味着低于高血糖阈值并高于低血糖阈值。现代连续血糖监测仪（CGM）的发展使这成为可能。它的持续监测使人们能够在低血糖/高血糖发作前采取行动。因此，准确的血糖（BG）预测是必不可少的。它在真正的低血糖/高血糖情景之前发出警报，并且对于非低血症/非高血糖发作保持沉默。数据驱动方法最近已广泛用于医疗保健和医学研究中的统计建模，特别是深度神经网络技术。在本文中，葡萄糖预测被视为概率生成问题，并且提出了混合深度神经网络来结合卷积神经网络（CNN）和递归神经网络（RNN）的优点。具体地，将多层CNN实现为特征提取组件，接着是多层修改的长期短期记忆（LSTM）模型，以捕获未来BG与历史BG水平，膳食信息和胰岛素之间的概率相关性。该模型适用于具有T1D的个体受试者，并且利用辍学层来避免过度拟合。该模型可以使用Tensorflow轻松实现，并且可以嵌入到计算资源有限的便携式设备中。实验使用模拟和临床数据验证和评估所提出方法的有效性。

##### URL
[http://arxiv.org/abs/1807.03043](http://arxiv.org/abs/1807.03043)

##### PDF
[http://arxiv.org/pdf/1807.03043](http://arxiv.org/pdf/1807.03043)

