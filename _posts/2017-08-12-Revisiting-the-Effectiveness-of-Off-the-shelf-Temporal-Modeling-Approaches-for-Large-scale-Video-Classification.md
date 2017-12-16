---
layout: post
title: "Revisiting the Effectiveness of Off-the-shelf Temporal Modeling Approaches for Large-scale Video Classification"
date: 2017-08-12 18:38:19
categories: arXiv_CV
tags: arXiv_CV Attention Video_Classification Classification Recognition
author: Yunlong Bian, Chuang Gan, Xiao Liu, Fu Li, Xiang Long, Yandong Li, Heng Qi, Jie Zhou, Shilei Wen, Yuanqing Lin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes our solution for the video recognition task of ActivityNet Kinetics challenge that ranked the 1st place. Most of existing state-of-the-art video recognition approaches are in favor of an end-to-end pipeline. One exception is the framework of DevNet. The merit of DevNet is that they first use the video data to learn a network (i.e. fine-tuning or training from scratch). Instead of directly using the end-to-end classification scores (e.g. softmax scores), they extract the features from the learned network and then fed them into the off-the-shelf machine learning models to conduct video classification. However, the effectiveness of this line work has long-term been ignored and underestimated. In this submission, we extensively use this strategy. Particularly, we investigate four temporal modeling approaches using the learned features: Multi-group Shifting Attention Network, Temporal Xception Network, Multi-stream sequence Model and Fast-Forward Sequence Model. Experiment results on the challenging Kinetics dataset demonstrate that our proposed temporal modeling approaches can significantly improve existing approaches in the large-scale video recognition tasks. Most remarkably, our best single Multi-group Shifting Attention Network can achieve 77.7% in term of top-1 accuracy and 93.2% in term of top-5 accuracy on the validation set.

##### Abstract (translated by Google)
本文介绍了我们针对排名第一的ActivityNet Kinetics挑战视频识别任务的解决方案。大多数现有的最先进的视频识别方法都支持端到端的流水线。 DevNet的一个例外是框架。 DevNet的优点是他们首先使用视频数据来学习网络（即从头开始进行微调或训练）。他们不是直接使用端到端的分类分数（例如softmax分数），而是从学习网络中提取特征，然后将它们馈送到现成的机器学习模型中进行视频分类。但是，这项工作的成效长期以来被忽视和低估。在这个提交中，我们广泛地使用这个策略。特别是，我们研究了四个时间建模方法使用学习功能：多组移动注意网络，时间Xception网络，多流序列模型和快速序列模型。在具有挑战性的动力学数据集上的实验结果表明，我们提出的时间建模方法可以显着改善大规模视频识别任务中的现有方法。最显着的是，我们最好的单组移动注意力网络可以达到前77％的准确率和93.2％的准确率。

##### URL
[https://arxiv.org/abs/1708.03805](https://arxiv.org/abs/1708.03805)

##### PDF
[https://arxiv.org/pdf/1708.03805](https://arxiv.org/pdf/1708.03805)

