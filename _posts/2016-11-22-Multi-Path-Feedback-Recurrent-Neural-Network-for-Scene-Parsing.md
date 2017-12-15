---
layout: post
title: "Multi-Path Feedback Recurrent Neural Network for Scene Parsing"
date: 2016-11-22 11:44:06
categories: arXiv_CV
tags: arXiv_CV RNN
author: Xiaojie Jin, Yunpeng Chen, Jiashi Feng, Zequn Jie, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider the scene parsing problem and propose a novel Multi-Path Feedback recurrent neural network (MPF-RNN) for parsing scene images. MPF-RNN can enhance the capability of RNNs in modeling long-range context information at multiple levels and better distinguish pixels that are easy to confuse. Different from feedforward CNNs and RNNs with only single feedback, MPF-RNN propagates the contextual features learned at top layer through \textit{multiple} weighted recurrent connections to learn bottom features. For better training MPF-RNN, we propose a new strategy that considers accumulative loss at multiple recurrent steps to improve performance of the MPF-RNN on parsing small objects. With these two novel components, MPF-RNN has achieved significant improvement over strong baselines (VGG16 and Res101) on five challenging scene parsing benchmarks, including traditional SiftFlow, Barcelona, CamVid, Stanford Background as well as the recently released large-scale ADE20K.

##### Abstract (translated by Google)
本文考虑场景解析问题，提出了一种新的多路径反馈递归神经网络（MPF-RNN）来解析场景图像。 MPF-RNN可以提高RNN在多个层面建立远程环境信息的能力，更好地区分容易混淆的像素。与前馈CNNs和RNNs不同，MPF-RNN通过\ textit {多}加权循环连接传播顶层学习到的上下文特征来学习底层特征。为了更好地训练MPF-RNN，我们提出了一种新的策略，考虑多次重复步骤中的累积损失，以提高MPF-RNN解析小对象的性能。有了这两个新颖的组件，MPF-RNN在五个具有挑战性的场景解析基准（包括传统的SiftFlow，巴塞罗那，CamVid，斯坦福大学背景以及最近发布的大规模ADE20K）上，在强基线（VGG16和Res101）

##### URL
[https://arxiv.org/abs/1608.07706](https://arxiv.org/abs/1608.07706)

##### PDF
[https://arxiv.org/pdf/1608.07706](https://arxiv.org/pdf/1608.07706)

