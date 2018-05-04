---
layout: post
title: "Multi-label Learning Based Deep Transfer Neural Network for Facial Attribute Classification"
date: 2018-05-03 13:13:50
categories: arXiv_CV
tags: arXiv_CV Face CNN Transfer_Learning Classification Detection Face_Detection Relation
author: Ni Zhuang, Yan Yan, Si Chen, Hanzi Wang, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Network (DNN) has recently achieved outstanding performance in a variety of computer vision tasks, including facial attribute classification. The great success of classifying facial attributes with DNN often relies on a massive amount of labelled data. However, in real-world applications, labelled data are only provided for some commonly used attributes (such as age, gender); whereas, unlabelled data are available for other attributes (such as attraction, hairline). To address the above problem, we propose a novel deep transfer neural network method based on multi-label learning for facial attribute classification, termed FMTNet, which consists of three sub-networks: the Face detection Network (FNet), the Multi-label learning Network (MNet) and the Transfer learning Network (TNet). Firstly, based on the Faster Region-based Convolutional Neural Network (Faster R-CNN), FNet is fine-tuned for face detection. Then, MNet is fine-tuned by FNet to predict multiple attributes with labelled data, where an effective loss weight scheme is developed to explicitly exploit the correlation between facial attributes based on attribute grouping. Finally, based on MNet, TNet is trained by taking advantage of unsupervised domain adaptation for unlabelled facial attribute classification. The three sub-networks are tightly coupled to perform effective facial attribute classification. A distinguishing characteristic of the proposed FMTNet method is that the three sub-networks (FNet, MNet and TNet) are constructed in a similar network structure. Extensive experimental results on challenging face datasets demonstrate the effectiveness of our proposed method compared with several state-of-the-art methods.

##### Abstract (translated by Google)
深度神经网络（DNN）最近在各种计算机视觉任务中取得了出色的表现，包括面部属性分类。使用DNN对面部属性进行分类的巨大成功通常依赖于大量的标记数据。但是，在实际应用中，标签数据仅提供一些常用属性（如年龄，性别）;而未标记的数据可用于其他属性（例如吸引力，发际线）。为解决上述问题，我们提出了一种基于多标签学习的面部属性分类的深度传递神经网络方法，称为FMTNet，它由三个子网络组成：人脸检测网络（FNet），多标签学习网络（MNet）和传输学习网络（TNet）。首先，基于更快的基于区域的卷积神经网络（更快的R-CNN），FNet被精细调整用于人脸检测。然后，由FNet对MNet进行微调，以预测具有标记数据的多个属性，其中开发有效的丢失权重方案以明确利用基于属性分组的面部属性之间的相关性。最后，基于MNet，TNet利用无监督域自适应对未标记的面部属性分类进行训练。三个子网紧密耦合以执行有效的面部属性分类。所提出的FMTNet方法的一个显着特征是三个子网络（FNet，MNet和TNet）以类似的网络结构构建。对具有挑战性的人脸数据集的广泛的实验结果证明了我们提出的方法与几种最先进的方法相比的有效性。

##### URL
[http://arxiv.org/abs/1805.01282](http://arxiv.org/abs/1805.01282)

##### PDF
[http://arxiv.org/pdf/1805.01282](http://arxiv.org/pdf/1805.01282)

