---
layout: post
title: "Attention to Refine through Multi-Scales for Semantic Segmentation"
date: 2018-07-09 02:31:44
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Semantic_Segmentation Prediction
author: Shiqi Yang, Gang Peng
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel attention model for semantic segmentation, which aggregates multi-scale and context features to refine prediction. Specifically, the skeleton convolutional neural network framework takes in multiple different scales inputs, by which means the CNN can get representations in different scales. The proposed attention model will handle the features from different scale streams respectively and integrate them. Then location attention branch of the model learns to softly weight the multi-scale features at each pixel location. Moreover, we add an recalibrating branch, parallel to where location attention comes out, to recalibrate the score map per class. We achieve quite competitive results on PASCAL VOC 2012 and ADE20K datasets, which surpass baseline and related works.

##### Abstract (translated by Google)
本文提出了一种新的语义分割注意模型，该模型聚合了多尺度和上下文特征来优化预测。具体来说，骨架卷积神经网络框架采用多种不同的尺度输入，这意味着CNN可以获得不同尺度的表示。建议的注意模型将分别处理来自不同比例流的特征并将它们集成。然后，模型的位置关注分支学习对每个像素位置处的多尺度特征进行柔和加权。此外，我们添加一个重新校准分支，与注意位置的位置平行，以重新校准每个类的分数图。我们在PASCAL VOC 2012和ADE20K数据集上取得了极具竞争力的成果，超过了基线和相关工作。

##### URL
[http://arxiv.org/abs/1807.02917](http://arxiv.org/abs/1807.02917)

##### PDF
[http://arxiv.org/pdf/1807.02917](http://arxiv.org/pdf/1807.02917)

