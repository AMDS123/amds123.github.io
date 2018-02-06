---
layout: post
title: "Learning the Synthesizability of Dynamic Texture Samples"
date: 2018-02-03 09:22:29
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Feng Yang, Gui-Song Xia, Dengxin Dai, Liangpei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
A dynamic texture (DT) refers to a sequence of images that exhibit temporal regularities and has many applications in computer vision and graphics. Given an exemplar of dynamic texture, it is a dynamic but challenging task to generate new samples with high quality that are perceptually similar to the input exemplar, which is known to be {\em example-based dynamic texture synthesis (EDTS)}. Numerous approaches have been devoted to this problem, in the past decades, but none them are able to tackle all kinds of dynamic textures equally well. In this paper, we investigate the synthesizability of dynamic texture samples: {\em given a dynamic texture sample, how synthesizable it is by using EDTS, and which EDTS method is the most suitable to synthesize it?} To this end, we propose to learn regression models to connect dynamic texture samples with synthesizability scores, with the help of a compiled dynamic texture dataset annotated in terms of synthesizability. More precisely, we first define the synthesizability of DT samples and characterize them by a set of spatiotemporal features. Based on these features and an annotated dynamic texture dataset, we then train regression models to predict the synthesizability scores of texture samples and learn classifiers to select the most suitable EDTS methods. We further complete the selection, partition and synthesizability prediction of dynamic texture samples in a hierarchical scheme. We finally apply the learned synthesizability to detecting synthesizable regions in videos. The experiments demonstrate that our method can effectively learn and predict the synthesizability of DT samples.

##### Abstract (translated by Google)
动态纹理（DT）指的是一系列图像，表现出时间规律性，并在计算机视觉和图形中有许多应用。给定一个动态纹理的示例，生成具有感知上类似于输入示例的高质量的新样本是动态的但是具有挑战性的任务，其已知是基于示例的动态纹理合成（EDTS）}。在过去的几十年中，已经有许多方法来解决这个问题，但是没有一个能够同样很好地处理各种动态纹理。在本文中，我们研究了动态纹理样本的合成性：给定一个动态纹理样本，如何使用EDTS进行合成，以及哪种EDTS方法最适合合成它？为此，我们建议学习回归模型，将动态纹理样本与可合成性分数连接起来，借助编辑后的动态纹理数据集对可合成性进行注释。更确切地说，我们首先定义DT样本的可合成性，并用一组时空特征来表征它们。基于这些特征和注释的动态纹理数据集，然后训练回归模型来预测纹理样本的合成性得分，并学习分类器以选择最合适的EDTS方法。我们进一步完成动态纹理样本的选择，分割和合成性预测的分层方案。我们最终将学习的合成性应用于视频中可检测的可合成区域。实验证明，该方法可以有效地学习和预测DT样本的合成性。

##### URL
[http://arxiv.org/abs/1802.00941](http://arxiv.org/abs/1802.00941)

##### PDF
[http://arxiv.org/pdf/1802.00941](http://arxiv.org/pdf/1802.00941)

