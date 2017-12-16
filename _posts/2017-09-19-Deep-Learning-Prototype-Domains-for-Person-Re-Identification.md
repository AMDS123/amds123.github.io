---
layout: post
title: "Deep Learning Prototype Domains for Person Re-Identification"
date: 2017-09-19 14:00:50
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Deep_Learning
author: Arne Schumann, Shaogang Gong, Tobias Schuchert
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (re-id) is the task of matching multiple occurrences of the same person from different cameras, poses, lighting conditions, and a multitude of other factors which alter the visual appearance. Typically, this is achieved by learning either optimal features or matching metrics which are adapted to specific pairs of camera views dictated by the pairwise labelled training datasets. In this work, we formulate a deep learning based novel approach to automatic prototype-domain discovery for domain perceptive (adaptive) person re-id (rather than camera pair specific learning) for any camera views scalable to new unseen scenes without training data. We learn a separate re-id model for each of the discovered prototype-domains and during model deployment, use the person probe image to select automatically the model of the closest prototype domain. Our approach requires neither supervised nor unsupervised domain adaptation learning, i.e. no data available from the target domains. We evaluate extensively our model under realistic re-id conditions using automatically detected bounding boxes with low-resolution and partial occlusion. We show that our approach outperforms most of the state-of-the-art supervised and unsupervised methods on the latest CUHK-SYSU and PRW benchmarks.

##### Abstract (translated by Google)
人物重新识别（re-id）是将来自不同相机，姿势，照明条件以及改变视觉外观的众多其他因素的多个同一人物匹配的任务。典型地，这是通过学习最佳特征或匹配度量来实现的，这些特征或匹配度量适应于成对标记的训练数据集规定的特定的摄像机视图对。在这项工作中，我们制定了一个基于深度学习的新颖的方法来自动原型领域发现领域感知（自适应）人员re-id（而不是相机对特定的学习）的任何相机视图可扩展到新的未见的场景，没有训练数据。我们为每个发现的原型域学习单独的re-id模型，并在模型部署过程中，使用人体探测图像自动选择最接近原型域的模型。我们的方法既不需要监督也不需要无监督的领域适应性学习，即目标领域没有数据可用。我们使用自动检测的低分辨率和部分遮挡的边界框，在现实的重建条件下广泛评估我们的模型。我们表明，我们的方法比最新的CUHK-SYSU和PRW基准测试中的大多数最新的监督和无监督方法要好。

##### URL
[https://arxiv.org/abs/1610.05047](https://arxiv.org/abs/1610.05047)

##### PDF
[https://arxiv.org/pdf/1610.05047](https://arxiv.org/pdf/1610.05047)

