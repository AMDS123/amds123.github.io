---
layout: post
title: "An Interpretable Deep Hierarchical Semantic Convolutional Neural Network for Lung Nodule Malignancy Classification"
date: 2018-06-02 22:41:28
categories: arXiv_AI
tags: arXiv_AI Knowledge CNN Classification Deep_Learning Prediction
author: Shiwen Shen, Simon X. Han, Denise R. Aberle, Alex A.T. Bui, Willliam Hsu
mathjax: true
---

* content
{:toc}

##### Abstract
While deep learning methods are increasingly being applied to tasks such as computer-aided diagnosis, these models are difficult to interpret, do not incorporate prior domain knowledge, and are often considered as a "black-box." The lack of model interpretability hinders them from being fully understood by target users such as radiologists. In this paper, we present a novel interpretable deep hierarchical semantic convolutional neural network (HSCNN) to predict whether a given pulmonary nodule observed on a computed tomography (CT) scan is malignant. Our network provides two levels of output: 1) low-level radiologist semantic features, and 2) a high-level malignancy prediction score. The low-level semantic outputs quantify the diagnostic features used by radiologists and serve to explain how the model interprets the images in an expert-driven manner. The information from these low-level tasks, along with the representations learned by the convolutional layers, are then combined and used to infer the high-level task of predicting nodule malignancy. This unified architecture is trained by optimizing a global loss function including both low- and high-level tasks, thereby learning all the parameters within a joint framework. Our experimental results using the Lung Image Database Consortium (LIDC) show that the proposed method not only produces interpretable lung cancer predictions but also achieves significantly better results compared to common 3D CNN approaches.

##### Abstract (translated by Google)
虽然深度学习方法越来越多地应用于诸如计算机辅助诊断等任务，但这些模型很难解释，没有纳入以前的领域知识，并且通常被认为是“黑盒子”。模型可解释性的缺乏阻碍了他们被诸如放射科医师等目标用户完全理解。在本文中，我们提出了一种新型的可解释的深层次语义卷积神经网络（HSCNN）来预测在计算机断层扫描（CT）扫描中观察到的给定肺结节是否是恶性的。我们的网络提供两级输出：1）低级放射科医师语义特征，2）高级恶性肿瘤预测评分。低级语义输出量化放射科医师使用的诊断特征，并用于解释模型如何以专家驱动的方式解释图像。来自这些低级别任务的信息以及卷积层学到的表示被结合起来用于推断预测结节恶性肿瘤的高级任务。这种统一架构通过优化包括低级和高级任务在内的全局损失函数进行训练，从而了解联合框架内的所有参数。我们使用肺图像数据库联盟（LIDC）的实验结果表明，与常用3D CNN方法相比，所提出的方法不仅产生可解释的肺癌预测，而且获得显着更好的结果。

##### URL
[http://arxiv.org/abs/1806.00712](http://arxiv.org/abs/1806.00712)

##### PDF
[http://arxiv.org/pdf/1806.00712](http://arxiv.org/pdf/1806.00712)

