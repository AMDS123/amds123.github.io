---
layout: post
title: "Pulsar Candidate Identification with Artificial Intelligence Techniques"
date: 2017-11-27 05:14:19
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Inference
author: Ping Guo (1,2), Fuqing Duan (2), Pei Wang (3), Yao Yao (2), Xin Xin (2) ((1) Image Processing and Pattern Recognition Laboratory, Beijing Normal University, (2) School of Computer Science, Beijing Institute of Technology, (3) National Astronomical Observatories, Chinese Academy of Sciences)
mathjax: true
---

* content
{:toc}

##### Abstract
Discovering pulsars is a significant and meaningful research topic in the field of radio astronomy. With the advent of astronomical instruments such as he Five-hundred-meter Aperture Spherical Telescope (FAST) in China, data volumes and data rates are exponentially growing. This fact necessitates a focus on artificial intelligence (AI) technologies that can perform the automatic pulsar candidate identification to mine large astronomical data sets. Automatic pulsar candidate identification can be considered as a task of determining potential candidates for further investigation and eliminating noises of radio frequency interferences or other non-pulsar signals. It is very hard to raise the performance of DCNN-based pulsar identification because the limited training samples restrict network structure to be designed deep enough for learning good features as well as the crucial class imbalance problem due to very limited number of real pulsar samples. To address these problems, we proposed a framework which combines deep convolution generative adversarial network (DCGAN) with support vector machine (SVM) to deal with imbalance class problem and to improve pulsar identification accuracy. DCGAN is used as sample generation and feature learning model, and SVM is adopted as the classifier for predicting candidate's labels in the inference stage. The proposed framework is a novel technique which not only can solve imbalance class problem but also can learn discriminative feature representations of pulsar candidates instead of computing hand-crafted features in preprocessing steps too, which makes it more accurate for automatic pulsar candidate selection. Experiments on two pulsar datasets verify the effectiveness and efficiency of our proposed method.

##### Abstract (translated by Google)
发现脉冲星是射电天文学领域一个重要而有意义的研究课题。随着中国五百米孔径球面望远镜（FAST）等天文仪器的出现，数据量和数据速率呈指数级增长。这个事实需要专注于人工智能（AI）技术，它可以执行自动脉冲星候选人识别来挖掘大型天文数据集。自动脉冲星候选者识别可以被认为是确定潜在候选者进一步调查并消除无线电频率干扰或其他非脉冲星信号的噪声的任务。由于有限的训练样本限制网络结构设计得足够深，以便学习良好的特征以及由于实际脉冲星样本数量非常有限而导致的关键类别不平衡问题，所以提高基于DCNN的脉冲星识别的性能是非常困难的。针对这些问题，提出了一种将深度卷积生成对抗网络（DCGAN）与支持向量机（SVM）结合起来处理不平衡类问题，提高脉冲星识别精度的框架。将DCGAN用作样本生成和特征学习模型，采用支持向量机作为预测候选者标签的分类器。该算法不仅可以解决不平衡类问题，而且可以学习脉冲星候选者的判别性特征表示，而不需要在预处理步骤中计算手工特征，从而使自动脉冲星候选选择更为准确。两个脉冲星数据集上的实验验证了我们提出的方法的有效性和有效性。

##### URL
[https://arxiv.org/abs/1711.10339](https://arxiv.org/abs/1711.10339)

##### PDF
[https://arxiv.org/pdf/1711.10339](https://arxiv.org/pdf/1711.10339)

