---
layout: post
title: "Joint Learning of Motion Estimation and Segmentation for Cardiac MR Image Sequences"
date: 2018-06-11 15:45:47
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning Quantitative
author: Chen Qin, Wenjia Bai, Jo Schlemper, Steffen E. Petersen, Stefan K. Piechnik, Stefan Neubauer, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiac motion estimation and segmentation play important roles in quantitatively assessing cardiac function and diagnosing cardiovascular diseases. In this paper, we propose a novel deep learning method for joint estimation of motion and segmentation from cardiac MR image sequences. The proposed network consists of two branches: a cardiac motion estimation branch which is built on a novel unsupervised Siamese style recurrent spatial transformer network, and a cardiac segmentation branch that is based on a fully convolutional network. In particular, a joint multi-scale feature encoder is learned by optimizing the segmentation branch and the motion estimation branch simultaneously. This enables the weakly-supervised segmentation by taking advantage of features that are unsupervisedly learned in the motion estimation branch from a large amount of unannotated data. Experimental results using cardiac MRI images from 220 subjects show that the joint learning of both tasks is complementary and the proposed models outperform the competing methods significantly in terms of accuracy and speed.

##### Abstract (translated by Google)
心脏运动估计和分割在量化评估心脏功能和诊断心血管疾病方面起着重要作用。在本文中，我们提出了一种新的深层学习方法，用于联合估计来自心脏MR图像序列的运动和分割。所提出的网络由两个分支组成：一个建立在新型无监督连体风格循环空间转换网络上的心脏运动估计分支，以及一个基于完全卷积网络的心脏分割分支。特别地，通过同时优化分割分支和运动估计分支来学习联合多尺度特征编码器。这通过利用运动估计分支中无监督地从大量未注解数据中学习的特征来实现弱监督分割。使用来自220个受试者的心脏MRI图像的实验结果表明，两个任务的联合学习是互补的，并且所提出的模型在准确性和速度方面显着优于竞争方法。

##### URL
[http://arxiv.org/abs/1806.04066](http://arxiv.org/abs/1806.04066)

##### PDF
[http://arxiv.org/pdf/1806.04066](http://arxiv.org/pdf/1806.04066)

