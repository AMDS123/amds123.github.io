---
layout: post
title: "Learning and Fusing Multimodal Features from and for Multi-task Facial Computing"
date: 2016-10-14 04:17:13
categories: arXiv_CV
tags: arXiv_CV Face Classification Deep_Learning Detection Recognition Face_Recognition
author: Wei Li, Zhigang Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep learning-based feature fusion approach for facial computing including face recognition as well as gender, race and age detection. Instead of training a single classifier on face images to classify them based on the features of the person whose face appears in the image, we first train four different classifiers for classifying face images based on race, age, gender and identification (ID). Multi-task features are then extracted from the trained models and cross-task-feature training is conducted which shows the value of fusing multimodal features extracted from multi-tasks. We have found that features trained for one task can be used for other related tasks. More interestingly, the features trained for a task with more classes (e.g. ID) and then used in another task with fewer classes (e.g. race) outperforms the features trained for the other task itself. The final feature fusion is performed by combining the four types of features extracted from the images by the four classifiers. The feature fusion approach improves the classifications accuracy by a 7.2%, 20.1%, 22.2%, 21.8% margin, respectively, for ID, age, race and gender recognition, over the results of single classifiers trained only on their individual features. The proposed method can be applied to applications in which different types of data or features can be extracted.

##### Abstract (translated by Google)
我们提出了一种基于深度学习的特征融合方法，包括人脸识别以及性别，种族和年龄检测。我们首先训练四个不同的分类器，根据种族，年龄，性别和身份（ID）对人脸图像进行分类，而不是在人脸图像上训练单个分类器来对其进行分类。然后从训练好的模型中提取出多任务特征，并进行交叉任务特征训练，表明融合多任务提取多模态特征的价值。我们发现为一个任务训练的特征可以用于其他相关的任务。更有趣的是，针对具有更多类别（例如ID）的任务训练的特征然后用于具有更少类别（例如比赛）的另一任务的特征优于针对其他任务本身训练的特征。最后的特征融合是通过组合从四个分类器从图像中提取的四种特征来执行的。特征融合方法提高分类准确率分别为7.2％，20.1％，22.2％，21.8％的边际，身份证，年龄，种族和性别识别，单一分类器的结果只训练其个人特征。所提出的方法可以应用于可以提取不同类型的数据或特征的应用中。

##### URL
[https://arxiv.org/abs/1610.04322](https://arxiv.org/abs/1610.04322)

##### PDF
[https://arxiv.org/pdf/1610.04322](https://arxiv.org/pdf/1610.04322)

