---
layout: post
title: "Assessing a mobile-based deep learning model for plant disease surveillance"
date: 2018-05-04 15:07:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection
author: Amanda Ramcharan, Peter McCloskey, Kelsee Baranowski, Neema Mbilinyi, Latifa Mrisho, Mathias Ndalahwa, James Legg, David Hughes
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural network models (CNNs) have made major advances in computer vision tasks in the last five years. Given the challenge in collecting real world datasets, most studies report performance metrics based on available research datasets. In scenarios where CNNs are to be deployed on images or videos from mobile devices, models are presented with new challenges due to lighting, angle, and camera specifications, which are not accounted for in research datasets. It is essential for assessment to also be conducted on real world datasets if such models are to be reliably integrated with products and services in society. Plant disease datasets can be used to test CNNs in real time and gain insight into real world performance. We train a CNN object detection model to identify foliar symptoms of diseases (or lack thereof) in cassava (Manihot esculenta Crantz). We then deploy the model on a mobile app and test its performance on mobile images and video of 720 diseased leaflets in an agricultural field in Tanzania. Within each disease category we test two levels of severity of symptoms - mild and pronounced, to assess the model performance for early detection of symptoms. In both severities we see a decrease in the F-1 score for real world images and video. The F-1 score dropped by 32% for pronounced symptoms in real world images (the closest data to the training data) due to a drop in model recall. If the potential of smartphone CNNs are to be realized our data suggest it is crucial to consider tuning precision and recall performance in order to achieve the desired performance in real world settings. In addition, the varied performance related to different input data (image or video) is an important consideration for the design of CNNs in real world applications.

##### Abstract (translated by Google)
卷积神经网络模型（CNN）在过去五年中在计算机视觉任务方面取得了重大进展。鉴于收集真实世界数据集的挑战，大多数研究报告基于可用研究数据集的性能指标。在需要将CNN部署在移动设备的图像或视频中的情况下，由于照明，角度和摄像机规格，模型呈现出新的挑战，这在研究数据集中没有考虑到。如果要将这些模型与社会中的产品和服务可靠地结合起来，对真实世界的数据集进行评估也是至关重要的。植物病害数据集可用于实时测试CNN并深入了解真实世界的性能。我们训练一个CNN物体检测模型，以确定木薯（Manihot esculenta Crantz）的叶片症状（或缺乏）。然后，我们将该模型部署在移动应用程序上，并在坦桑尼亚农业领域的720个患病传单的移动图像和视频上测试其性能。在每个疾病类别中，我们测试症状的两个严重程度级别 - 轻度和明显的，以评估模型性能以及早发现症状。在两种严重程度中，我们都看到真实世界图像和视频的F-1分数下降。由于模型召回下降，F-1得分在真实世界图像（与训练数据最接近的数据）显着症状下降了32％。如果要实现智能手机CNN的潜力，我们的数据显示，考虑调谐精度和调用性能至关重要，以便在现实世界中实现理想的性能。此外，与不同输入数据（图像或视频）相关的各种性能是实际应用中CNN设计的重要考虑因素。

##### URL
[https://arxiv.org/abs/1805.08692](https://arxiv.org/abs/1805.08692)

##### PDF
[https://arxiv.org/pdf/1805.08692](https://arxiv.org/pdf/1805.08692)

