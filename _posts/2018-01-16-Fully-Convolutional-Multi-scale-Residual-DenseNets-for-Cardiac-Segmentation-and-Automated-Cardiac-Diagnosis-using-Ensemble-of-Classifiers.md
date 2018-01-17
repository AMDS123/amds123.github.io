---
layout: post
title: "Fully Convolutional Multi-scale Residual DenseNets for Cardiac Segmentation and Automated Cardiac Diagnosis using Ensemble of Classifiers"
date: 2018-01-16 09:32:32
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification
author: Mahendra Khened, Varghese Alex Kollerathu, Ganapathy Krishnamurthi
mathjax: true
---

* content
{:toc}

##### Abstract
Deep fully convolutional neural network (FCN) based architectures have shown great potential in medical image segmentation. However, such architectures usually have millions of parameters and inadequate number of training samples leading to over-fitting and poor generalization. In this paper, we present a novel highly parameter and memory efficient FCN based architecture for medical image analysis. We propose a novel up-sampling path which incorporates long skip and short-cut connections to overcome the feature map explosion in FCN like architectures. In order to processes the input images at multiple scales and view points simultaneously, we propose to incorporate Inception module's parallel structures. We also propose a novel dual loss function whose weighting scheme allows to combine advantages of cross-entropy and dice loss. We have validated our proposed network architecture on two publicly available datasets, namely: (i) Automated Cardiac Disease Diagnosis Challenge (ACDC-2017), (ii) Left Ventricular Segmentation Challenge (LV-2011). Our approach in ACDC-2017 challenge stands second place for segmentation and first place in automated cardiac disease diagnosis tasks with an accuracy of 100%. In the LV-2011 challenge our approach attained 0.74 Jaccard index, which is so far the highest published result in fully automated algorithms. From the segmentation we extracted clinically relevant cardiac parameters and hand-crafted features which reflected the clinical diagnostic analysis to train an ensemble system for cardiac disease classification. Our approach combined both cardiac segmentation and disease diagnosis into a fully automated framework which is computational efficient and hence has the potential to be incorporated in computer-aided diagnosis (CAD) tools for clinical application.

##### Abstract (translated by Google)
基于深度完全卷积神经网络（FCN）的医学图像分割技术显示出巨大的潜力。然而，这样的架构通常具有数百万个参数，并且训练样本数量不足导致过度拟合和差异泛化。在本文中，我们提出了一种新的高参数和高效的基于FCN的医学图像分析结构。我们提出了一种新颖的上采样路径，该路径包含长跳过和快捷连接，以克服像FCN一样的架构中的特征映射爆炸。为了同时处理多个尺度和视点上的输入图像，我们建议将Inception模块的并行结构合并。我们还提出了一种新的双损失函数，其加权方案允许结合交叉熵和骰子损失的优点。我们已经在两个公开可用的数据集上验证了我们提出的网络架构，即：（i）自动心脏疾病诊断挑战（ACDC-2017），（ii）左心室分割挑战（LV-2011）。在ACDC-2017挑战中，我们的方法成为第二位，在自动化心脏疾病诊断任务中处于第一位，准确率达到100％。在LV-2011的挑战中，我们的方法达到了0.74的Jaccard指数，这是迄今为止全自动算法公布的最高结果。从分割中，我们提取了临床相关的心脏参数和手工特征，反映了临床诊断分析，以训练用于心脏疾病分类的整体系统。我们的方法将心脏分割和疾病诊断结合到一个完全自动化的框架中，该框架计算效率高，因此有可能被纳入用于临床应用的计算机辅助诊断（CAD）工具中。

##### URL
[http://arxiv.org/abs/1801.05173](http://arxiv.org/abs/1801.05173)

##### PDF
[http://arxiv.org/pdf/1801.05173](http://arxiv.org/pdf/1801.05173)

