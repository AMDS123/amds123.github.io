---
layout: post
title: "Combo Loss: Handling Input and Output Imbalance in Multi-Organ Segmentation"
date: 2018-05-08 01:39:59
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Inference Deep_Learning
author: Saeid Asgari Taghanaki, Yefeng Zheng, S. Kevin Zhou, Bogdan Georgescu, Puneet Sharma, Daguang Xu, Dorin Comaniciu, Ghassan Hamarneh
mathjax: true
---

* content
{:toc}

##### Abstract
Simultaneous segmentation of multiple organs from different medical imaging modalities is a crucial task as it can be utilized for computer-aided diagnosis, computer-assisted surgery, and therapy planning. Thanks to the recent advances in deep learning, several deep neural networks for medical image segmentation have been introduced successfully for this purpose. In this paper, we focus on learning a deep multi-organ segmentation network that labels voxels. In particular, we examine the critical choice of a loss function in order to handle the notorious imbalance problem that plagues both the input and output of a learning model. The input imbalance refers to the class-imbalance in the input training samples (i.e. small foreground objects embedded in an abundance of background voxels, as well as organs of varying sizes). The output imbalance refers to the imbalance between the false positives and false negatives of the inference model. We introduce a loss function that integrates a weighted cross-entropy with a Dice similarity coefficient to tackle both types of imbalance during training and inference. We evaluated the proposed loss function on three datasets of whole body PET scans with 5 target organs, MRI prostate scans, and ultrasound echocardigraphy images with a single target organ. We show that a simple network architecture with the proposed integrative loss function can outperform state-of-the-art methods and results of the competing methods can be improved when our proposed loss is used.

##### Abstract (translated by Google)
由于它可以用于计算机辅助诊断，计算机辅助手术和治疗计划，因此从不同的医学成像模式同时分割多个器官是一项至关重要的任务。由于深度学习的最新进展，为此目的已经成功引入了几种用于医学图像分割的深度神经网络。在本文中，我们专注于学习标记体素的深层多器官分割网络。特别是，我们研究了损失函数的关键选择，以处理臭名昭着的不平衡问题，这个问题困扰着学习模型的输入和输出。输入不平衡是指输入训练样本（即嵌入大量背景体素的小前景对象以及不同大小的器官）中的类不平衡。输出失衡是指推理模型的假阳性和假阴性之间的不平衡。我们引入一个损失函数，将加权交叉熵与Dice相似系数相结合，以解决训练和推理过程中的两种不平衡问题。我们评估了对5个靶器官，MRI前列腺扫描和单个靶器官的超声心动图像进行全身PET扫描的三个数据集上提出的损失函数。我们表明，具有所提出的集成损失函数的简单网络架构可以胜过最先进的方法，并且在使用我们提出的损失时可以改进竞争方法的结果。

##### URL
[https://arxiv.org/abs/1805.02798](https://arxiv.org/abs/1805.02798)

##### PDF
[https://arxiv.org/pdf/1805.02798](https://arxiv.org/pdf/1805.02798)

