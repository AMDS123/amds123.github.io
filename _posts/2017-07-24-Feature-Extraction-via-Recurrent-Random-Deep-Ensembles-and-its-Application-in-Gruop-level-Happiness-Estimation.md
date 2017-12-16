---
layout: post
title: "Feature Extraction via Recurrent Random Deep Ensembles and its Application in Gruop-level Happiness Estimation"
date: 2017-07-24 08:16:43
categories: arXiv_CV
tags: arXiv_CV Face CNN RNN Prediction
author: Shitao Tang, Yichen Pan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel ensemble framework to extract highly discriminative feature representation of image and its application for group-level happpiness intensity prediction in wild. In order to generate enough diversity of decisions, n convolutional neural networks are trained by bootstrapping the training set and extract n features for each image from them. A recurrent neural network (RNN) is then used to remember which network extracts better feature and generate the final feature representation for one individual image. Several group emotion models (GEM) are used to aggregate face fea- tures in a group and use parameter-optimized support vector regressor (SVR) to get the final results. Through extensive experiments, the great effectiveness of the proposed recurrent random deep ensembles (RRDE) is demonstrated in both structural and decisional ways. The best result yields a 0.55 root-mean-square error (RMSE) on validation set of HAPPEI dataset, significantly better than the baseline of 0.78.

##### Abstract (translated by Google)
本文提出了一种新的集成框架来提取图像的高判别性特征表示及其在野外群组级别发情强度预测中的应用。为了产生足够多样的决策，n卷积神经网络通过引导训练集并从它们提取每个图像的n个特征来训练。然后使用递归神经网络（RNN）来记忆哪个网络提取更好的特征并且生成一个单独图像的最终特征表示。使用多组情感模型（GEM）来聚合一组中的人脸特征，并使用参数优化的支持向量回归（SVR）来获得最终结果。通过广泛的实验，所提出的经常性随机深层合奏（RRDE）的有效性在结构和决策方面都得到了证明。最好的结果是在HAPPEI数据集的验证集合上产生0.55均方根误差（RMSE），明显好于基线0.78。

##### URL
[https://arxiv.org/abs/1707.09871](https://arxiv.org/abs/1707.09871)

##### PDF
[https://arxiv.org/pdf/1707.09871](https://arxiv.org/pdf/1707.09871)

