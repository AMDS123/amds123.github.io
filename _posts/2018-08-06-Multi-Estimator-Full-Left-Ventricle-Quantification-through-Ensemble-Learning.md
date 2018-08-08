---
layout: post
title: "Multi-Estimator Full Left Ventricle Quantification through Ensemble Learning"
date: 2018-08-06 18:25:46
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Jiasha Liu, Xiang Li, Hui Ren, Quanzheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiovascular disease accounts for 1 in every 4 deaths in United States. Accurate estimation of structural and functional cardiac parameters is crucial for both diagnosis and disease management. In this work, we develop an ensemble learning framework for more accurate and robust left ventricle (LV) quantification. The framework combines two 1st-level modules: direct estimation module and a segmentation module. The direct estimation module utilizes Convolutional Neural Network (CNN) to achieve end-to-end quantification. The CNN is trained by taking 2D cardiac images as input and cardiac parameters as output. The segmentation module utilizes a U-Net architecture for obtaining pixel-wise prediction of the epicardium and endocardium of LV from the background. The binary U-Net output is then analyzed by a separate CNN for estimating the cardiac parameters. We then employ linear regression between the 1st-level predictor and ground truth to learn a 2nd-level predictor that ensembles the results from 1st-level modules for the final estimation. Preliminary results by testing the proposed framework on the LVQuan18 dataset show superior performance of the ensemble learning model over the two base modules.

##### Abstract (translated by Google)
在美国，心血管疾病占每4例死亡中的1例。准确估计结构和功能性心脏参数对于诊断和疾病管理都至关重要。在这项工作中，我们开发了一个集成学习框架，用于更准确和稳健的左心室（LV）量化。该框架结合了两个第一级模块：直接估计模块和分段模块。直接估计模块利用卷积神经网络（CNN）来实现端到端量化。通过将2D心脏图像作为输入并且将心脏参数作为输出来训练CNN。分割模块利用U-Net架构从背景获得LV的心外膜和心内膜的像素预测。然后由单独的CNN分析二进制U-Net输出以估计心脏参数。然后，我们在第一级预测器和基础事实之间采用线性回归来学习第二级预测器，该预测器将最终估计的第一级模块的结果集合在一起。通过在LVQuan18数据集上测试所提出的框架的初步结果显示了集成学习模型相对于两个基本模块的优越性能。

##### URL
[http://arxiv.org/abs/1808.02056](http://arxiv.org/abs/1808.02056)

##### PDF
[http://arxiv.org/pdf/1808.02056](http://arxiv.org/pdf/1808.02056)

