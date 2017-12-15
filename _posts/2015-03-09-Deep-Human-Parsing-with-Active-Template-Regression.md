---
layout: post
title: "Deep Human Parsing with Active Template Regression"
date: 2015-03-09 08:14:12
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Xiaodan Liang, Si Liu, Xiaohui Shen, Jianchao Yang, Luoqi Liu, Jian Dong, Liang Lin, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, the human parsing task, namely decomposing a human image into semantic fashion/body regions, is formulated as an Active Template Regression (ATR) problem, where the normalized mask of each fashion/body item is expressed as the linear combination of the learned mask templates, and then morphed to a more precise mask with the active shape parameters, including position, scale and visibility of each semantic region. The mask template coefficients and the active shape parameters together can generate the human parsing results, and are thus called the structure outputs for human parsing. The deep Convolutional Neural Network (CNN) is utilized to build the end-to-end relation between the input human image and the structure outputs for human parsing. More specifically, the structure outputs are predicted by two separate networks. The first CNN network is with max-pooling, and designed to predict the template coefficients for each label mask, while the second CNN network is without max-pooling to preserve sensitivity to label mask position and accurately predict the active shape parameters. For a new image, the structure outputs of the two networks are fused to generate the probability of each label for each pixel, and super-pixel smoothing is finally used to refine the human parsing result. Comprehensive evaluations on a large dataset well demonstrate the significant superiority of the ATR framework over other state-of-the-arts for human parsing. In particular, the F1-score reaches $64.38\%$ by our ATR framework, significantly higher than $44.76\%$ based on the state-of-the-art algorithm.

##### Abstract (translated by Google)
在这项工作中，人的解析任务，即分解一个人的形象为语义时尚/身体地区，被制定为活动模板回归（ATR）的问题，其中每个时尚/身体项目的规范化的面具表示为线性组合学习的蒙版模板，然后变形为具有活动形状参数（包括每个语义区域的位置，比例和可见度）的更精确的蒙版。蒙版模板系数和活动形状参数一起可以生成人体解析结果，因此称为人体解析的结构输出。利用深度卷积神经网络（CNN）建立输入人体图像与人体解析结构输出之间的端到端关系。更具体地说，结构输出由两个独立的网络预测。第一个CNN网络具有最大池，用于预测每个标签掩模的模板系数，而第二个CNN网络没有最大池，以保持对标签掩模位置的敏感性并准确预测活动的形状参数。对于一个新的图像，将两个网络的结构输出进行融合，生成每个像素的每个标签的概率，最后使用超像素平滑来优化人的解析结果。对大型数据集的综合评估充分证明了ATR框架比其他艺术级人类解析的显着优势。特别的，我们的ATR框架的F1分数达到$ 64.38 \％$，比现有算法高出$ 44.76 \％$。

##### URL
[https://arxiv.org/abs/1503.02391](https://arxiv.org/abs/1503.02391)

##### PDF
[https://arxiv.org/pdf/1503.02391](https://arxiv.org/pdf/1503.02391)

