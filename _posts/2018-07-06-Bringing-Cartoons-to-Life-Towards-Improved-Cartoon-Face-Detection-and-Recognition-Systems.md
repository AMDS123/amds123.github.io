---
layout: post
title: "Bringing Cartoons to Life: Towards Improved Cartoon Face Detection and Recognition Systems"
date: 2018-07-06 10:00:23
categories: arXiv_CV
tags: arXiv_CV Face CNN Transfer_Learning Deep_Learning Detection Face_Detection Recognition Face_Recognition
author: Saurav Jha, Nikhil Agarwal, Suneeta Agarwal
mathjax: true
---

* content
{:toc}

##### Abstract
Given the recent deep learning advancements in face detection and recognition techniques for human faces, this paper answers the question "how well would they work for cartoons'?" - a domain that remains largely unexplored until recently, mainly due to the unavailability of large scale datasets and the failure of traditional methods on these. Our work studies and extends multiple frameworks for the aforementioned tasks. For face detection, we incorporate the Multi-task Cascaded Convolutional Network (MTCNN) architecture and contrast it with conventional methods. For face recognition, our two-fold contributions include: (i) an inductive transfer learning approach combining the feature learning capability of the Inception v3 network and the feature recognizing capability of Support Vector Machines (SVMs), (ii) a proposed Hybrid Convolutional Neural Network (HCNN) framework trained over a fusion of pixel values and 15 manually located facial keypoints. All the methods are evaluated on the Cartoon Faces in the Wild (IIIT-CFW) database. We demonstrate that the HCNN model offers stability superior to that of Inception+SVM over larger input variations, and explore the plausible architectural principles. We show that the Inception+SVM model establishes a state-of-the-art F1 score on the task of gender recognition of cartoon faces. Further, we introduce a small database hosting location coordinates of 15 points on the cartoon faces belonging to 50 public figures of the IIIT-CFW database.

##### Abstract (translated by Google)
鉴于最近人脸检测和识别技术的深入学习进展，本文回答了“它们对卡通的效果如何？”的问题。 - 直到最近仍未进行大量未开发的领域，主要是由于大规模数据集不可用以及传统方法在这些方面的失败。我们的工作研究并扩展了上述任务的多个框架。对于人脸检测，我们采用了多任务级联卷积网络（MTCNN）架构，并将其与传统方法进行对比。对于人脸识别，我们的双重贡献包括：（i）归纳转移学习方法，结合了初始v3网络的特征学习能力和支持向量机（SVM）的特征识别能力，（ii）提出的混合卷积神经网络网络（HCNN）框架通过像素值和15个手动定位的面部关键点的融合进行训练。所有方法都在漫画中的Cartoon Faces（IIIT-CFW）数据库中进行评估。我们证明了HCNN模型在较大的输入变量上提供了优于Inception + SVM的稳定性，并探索了合理的架构原则。我们展示了Inception + SVM模型在卡通人物的性别识别任务中建立了最先进的F1分数。此外，我们在属于IIIT-CFW数据库的50名公众人物的卡通脸上引入了一个小型数据库，其中包含15个点的位置坐标。

##### URL
[http://arxiv.org/abs/1804.01753](http://arxiv.org/abs/1804.01753)

##### PDF
[http://arxiv.org/pdf/1804.01753](http://arxiv.org/pdf/1804.01753)

