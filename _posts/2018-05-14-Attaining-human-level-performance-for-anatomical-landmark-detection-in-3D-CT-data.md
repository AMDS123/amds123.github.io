---
layout: post
title: "Attaining human-level performance for anatomical landmark detection in 3D CT data"
date: 2018-05-14 09:12:03
categories: arXiv_CV
tags: arXiv_CV Prediction Detection
author: Alison Q O'Neil, Antanas Kascenas, Joseph Henry, Daniel Wyeth, Matthew Shepherd, Erin Beveridge, Lauren Clunie, Carrie Sansom, Evelina Šeduikytė, Keith Muir, Ian Poole
mathjax: true
---

* content
{:toc}

##### Abstract
We present an efficient neural network approach for locating anatomical landmarks, using a two-pass, two-resolution cascaded approach which leverages a mechanism we term atlas location autocontext. Location predictions are made by regression to Gaussian heatmaps, one heatmap per landmark. This system allows patchwise application of a shallow network, thus enabling the prediction of multiple volumetric heatmaps in a unified system, without prohibitive GPU memory requirements. Evaluation is performed for 22 landmarks defined on a range of structures in head CT scans and the neural network model is benchmarked against a previously reported decision forest model trained with the same cascaded system. Models are trained and validated on 201 scans. Over the final test set of 20 scans which was independently annotated by 2 observers, we show that the neural network reaches an accuracy which matches the annotator variability.

##### Abstract (translated by Google)
我们提出了一种有效的神经网络方法来定位解剖标志，使用双通，双分辨率级联方法，该方法利用了我们称为Atlas位置自动置换的机制。位置预测是通过高斯热场地图回归得出的，每个地标一个热图。该系统允许浅层网络的拼接应用，从而能够在统一系统中预测多个体积热图，而不会造成GPU的内存需求过高。针对在头部CT扫描中的一系列结构上定义的22个界标执行评估，并且将神经网络模型与之前报告的使用相同级联系统训练的决策森林模型进行基准比较。模型经过201次扫描的训练和验证。在由2名观察者独立注释的20次扫描的最终测试集中，我们显示神经网络达到与注释器变化相匹配的准确度。

##### URL
[https://arxiv.org/abs/1805.08687](https://arxiv.org/abs/1805.08687)

##### PDF
[https://arxiv.org/pdf/1805.08687](https://arxiv.org/pdf/1805.08687)

