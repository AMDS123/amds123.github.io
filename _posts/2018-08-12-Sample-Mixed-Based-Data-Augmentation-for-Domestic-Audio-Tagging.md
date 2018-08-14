---
layout: post
title: "Sample Mixed-Based Data Augmentation for Domestic Audio Tagging"
date: 2018-08-12 02:34:55
categories: arXiv_SD
tags: arXiv_SD Attention CNN RNN Deep_Learning
author: Shengyun Wei, Kele Xu, Dezhi Wang, Feifan Liao, Huaimin Wang, Qiuqiang Kong
mathjax: true
---

* content
{:toc}

##### Abstract
Audio tagging has attracted increasing attention since last decade and has various potential applications in many fields. The objective of audio tagging is to predict the labels of an audio clip. Recently deep learning methods have been applied to audio tagging and have achieved state-of-the-art performance, which provides a poor generalization ability on new data. However due to the limited size of audio tagging data such as DCASE data, the trained models tend to result in overfitting of the network. Previous data augmentation methods such as pitch shifting, time stretching and adding background noise do not show much improvement in audio tagging. In this paper, we explore the sample mixed data augmentation for the domestic audio tagging task, including mixup, SamplePairing and extrapolation. We apply a convolutional recurrent neural network (CRNN) with attention module with log-scaled mel spectrum as a baseline system. In our experiments, we achieve an state-of-the-art of equal error rate (EER) of 0.10 on DCASE 2016 task4 dataset with mixup approach, outperforming the baseline system without data augmentation.

##### Abstract (translated by Google)
自上个十年以来，音频标签引起了越来越多的关注，并且在许多领域具有各种潜在的应音频标记的目的是预测音频剪辑的标签。最近，深度学习方法已经应用于音频标记并且已经实现了最新的性能，这提供了对新数据的差的泛化能力。然而，由于诸如DCASE数据的音频标记数据的大小有限，训练的模型倾向于导致网络的过度拟合。先前的数据增强方法，例如音高变换，时间延长和添加背景噪声，在音频标记方面没有显示出太大的改进。在本文中，我们探讨了国内音频标记任务的样本混合数据增强，包括混合，SamplePairing和外推。我们应用卷积递归神经网络（CRNN）与注意模块与对数标度梅尔谱作为基线系统。在我们的实验中，我们使用混合方法在DCASE 2016 task4数据集上实现了0.10的等同错误率（EER）的最新技术，在没有数据增加的情况下优于基线系统。

##### URL
[http://arxiv.org/abs/1808.03883](http://arxiv.org/abs/1808.03883)

##### PDF
[http://arxiv.org/pdf/1808.03883](http://arxiv.org/pdf/1808.03883)

