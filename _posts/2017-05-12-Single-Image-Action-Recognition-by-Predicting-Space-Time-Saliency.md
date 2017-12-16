---
layout: post
title: "Single Image Action Recognition by Predicting Space-Time Saliency"
date: 2017-05-12 16:03:33
categories: arXiv_CV
tags: arXiv_CV Salient Action_Recognition CNN Transfer_Learning Classification Recognition
author: Marjaneh Safaei, Hassan Foroosh
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel approach based on deep Convolutional Neural Networks (CNN) to recognize human actions in still images by predicting the future motion, and detecting the shape and location of the salient parts of the image. We make the following major contributions to this important area of research: (i) We use the predicted future motion in the static image (Walker et al., 2015) as a means of compensating for the missing temporal information, while using the saliency map to represent the the spatial information in the form of location and shape of what is predicted as significant. (ii) We cast action classification in static images as a domain adaptation problem by transfer learning. We first map the input static image to a new domain that we refer to as the Predicted Optical Flow-Saliency Map domain (POF-SM), and then fine-tune the layers of a deep CNN model trained on classifying the ImageNet dataset to perform action classification in the POF-SM domain. (iii) We tested our method on the popular Willow dataset. But unlike existing methods, we also tested on a more realistic and challenging dataset of over 2M still images that we collected and labeled by taking random frames from the UCF-101 video dataset. We call our dataset the UCF Still Image dataset or UCFSI-101 in short. Our results outperform the state of the art.

##### Abstract (translated by Google)
我们提出了一种基于深度卷积神经网络（CNN）的新方法，通过预测未来的运动，并检测图像中显着部分的形状和位置，来识别静止图像中的人类行为。我们对这个重要的研究领域做出以下主要贡献：（i）我们使用静态图像中的预测未来运动（Walker等，2015）作为补偿缺失时间信息的手段，同时使用显着图以预测为显着的位置和形状来表示空间信息。 （ii）通过转移学习，将静态图像中的动作分类作为领域适应问题。我们首先将输入的静态图像映射到一个新的领域，我们称之为预测的光学流 - 显着图领域（POF-SM），然后微调一个深层的CNN模型的层次，对分类ImageNet数据集进行训练行动分类在POF-SM领域。 （iii）我们在受欢迎的Willow数据集上测试了我们的方法。但是与现有的方法不同，我们也测试了一个更加真实和具有挑战性的数据集，其中包含了我们从UCF-101视频数据集中采集和标记的超过2M静态图像。我们称之为我们的数据集UCF静止图像数据集或简称UCFSI-101。我们的结果胜过最先进的技术。

##### URL
[https://arxiv.org/abs/1705.04641](https://arxiv.org/abs/1705.04641)

##### PDF
[https://arxiv.org/pdf/1705.04641](https://arxiv.org/pdf/1705.04641)

