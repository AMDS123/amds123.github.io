---
layout: post
title: "Transfer Learning for Domain Adaptation in MRI: Application in Brain Lesion Segmentation"
date: 2017-02-25 07:04:25
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Transfer_Learning
author: Mohsen Ghafoorian, Alireza Mehrtash, Tina Kapur, Nico Karssemeijer, Elena Marchiori, Mehran Pesteie, Charles R. G. Guttmann, Frank-Erik de Leeuw, Clare M. Tempany, Bram van Ginneken, Andriy Fedorov, Purang Abolmaesumi, Bram Platel, William M. Wells III
mathjax: true
---

* content
{:toc}

##### Abstract
Magnetic Resonance Imaging (MRI) is widely used in routine clinical diagnosis and treatment. However, variations in MRI acquisition protocols result in different appearances of normal and diseased tissue in the images. Convolutional neural networks (CNNs), which have shown to be successful in many medical image analysis tasks, are typically sensitive to the variations in imaging protocols. Therefore, in many cases, networks trained on data acquired with one MRI protocol, do not perform satisfactorily on data acquired with different protocols. This limits the use of models trained with large annotated legacy datasets on a new dataset with a different domain which is often a recurring situation in clinical settings. In this study, we aim to answer the following central questions regarding domain adaptation in medical image analysis: Given a fitted legacy model, 1) How much data from the new domain is required for a decent adaptation of the original network?; and, 2) What portion of the pre-trained model parameters should be retrained given a certain number of the new domain training samples? To address these questions, we conducted extensive experiments in white matter hyperintensity segmentation task. We trained a CNN on legacy MR images of brain and evaluated the performance of the domain-adapted network on the same task with images from a different domain. We then compared the performance of the model to the surrogate scenarios where either the same trained network is used or a new network is trained from scratch on the new dataset.The domain-adapted network tuned only by two training examples achieved a Dice score of 0.63 substantially outperforming a similar network trained on the same set of examples from scratch.

##### Abstract (translated by Google)
磁共振成像（MRI）广泛用于常规临床诊断和治疗。然而，MRI采集方案的变化导致图像中正常和患病组织的不同外观。已经显示在许多医学图像分析任务中成功的卷积神经网络（CNN）通常对成像协议的变化敏感。因此，在许多情况下，对使用一种MRI协议获取的数据进行训练的网络对使用不同协议获取的数据不能令人满意地执行。这限制了在具有不同域的新数据集上使用用大量注释的遗留数据集进行训练的模型，这在临床环境中经常是反复出现的情况。在这项研究中，我们的目标是回答以下关于医学图像分析中的领域适应的中心问题：给定一个适合的遗传模型，1）需要多少来自新领域的数据才能适应原始网络？和2）在给定一定数量的新领域训练样本的情况下，应该重新训练预先训练的模型参数的哪一部分？为了解决这些问题，我们在白质高信号分割任务中进行了广泛的实验。我们在大脑遗留的MR图像上训练CNN，并对来自不同域的图像进行相同任务的域适应网络的性能进行评估。然后，我们将模型的性能与代理场景的性能进行比较，在这些场景中使用相同的训练网络，或者在新的数据集上从头开始训练新的网络。仅通过两个训练实例调谐的域适应性网络达到了0.63的骰子评分基本上胜过从头开始对同一套示例进行培训的类似网络。

##### URL
[https://arxiv.org/abs/1702.07841](https://arxiv.org/abs/1702.07841)

##### PDF
[https://arxiv.org/pdf/1702.07841](https://arxiv.org/pdf/1702.07841)

