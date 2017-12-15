---
layout: post
title: "Apparent Age Estimation Using Ensemble of Deep Learning Models"
date: 2016-06-09 11:00:21
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Deep_Learning
author: Refik Can Malli, Mehmet Aygun, Hazim Kemal Ekenel
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of apparent age estimation. Different from estimating the real age of individuals, in which each face image has a single age label, in this problem, face images have multiple age labels, corresponding to the ages perceived by the annotators, when they look at these images. This provides an intriguing computer vision problem, since in generic image or object classification tasks, it is typical to have a single ground truth label per class. To account for multiple labels per image, instead of using average age of the annotated face image as the class label, we have grouped the face images that are within a specified age range. Using these age groups and their age-shifted groupings, we have trained an ensemble of deep learning models. Before feeding an input face image to a deep learning model, five facial landmark points are detected and used for 2-D alignment. We have employed and fine tuned convolutional neural networks (CNNs) that are based on VGG-16 [24] architecture and pretrained on the IMDB-WIKI dataset [22]. The outputs of these deep learning models are then combined to produce the final estimation. Proposed method achieves 0.3668 error in the final ChaLearn LAP 2016 challenge test set [5].

##### Abstract (translated by Google)
在本文中，我们解决了明显的年龄估计问题。与估计每个人脸图像具有单一年龄标签的个人真实年龄不同，在这个问题中，人脸图像具有多个年龄标签，对应于注释者在看这些图像时感知的年龄。这提供了一个有趣的计算机视觉问题，因为在通用图像或对象分类任务中，每个类别具有单一的地面实况标签是典型的。为了考虑每个图像的多个标签，而不是使用带注释的人脸图像的平均年龄作为类别标签，我们已经将在特定年龄范围内的人脸图像分组。利用这些年龄组和他们年龄转移的分组，我们训练了一套深度学习模式。在将输入面部图像馈送到深度学习模型之前，检测五个面部标志点并将其用于二维对准。我们采用了基于VGG-16 [24]架构并在IMDB-WIKI数据集上预训练的微调卷积神经网络（CNN）[22]。然后将这些深度学习模型的输出结合起来以产生最终估计。提出的方法在最终的ChaLearn LAP 2016挑战测试集中实现了0.3668的错误[5]。

##### URL
[https://arxiv.org/abs/1606.02909](https://arxiv.org/abs/1606.02909)

##### PDF
[https://arxiv.org/pdf/1606.02909](https://arxiv.org/pdf/1606.02909)

