---
layout: post
title: "Replication study: Development and validation of deep learning algorithm for detection of diabetic retinopathy in retinal fundus photographs"
date: 2018-03-12 16:04:28
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Detection
author: Mike Voets, Kajsa Møllersen, Lars Ailo Bongo
mathjax: true
---

* content
{:toc}

##### Abstract
We have replicated some experiments in 'Development and validation of a deep learning algorithm for detection of diabetic retinopathy in retinal fundus photographs' that was published in JAMA 2016; 316(22). We re-implemented the methods since the source code is not available. The original study used fundus images from EyePACS and three hospitals in India for training their detection algorithm. We used a different EyePACS data set that was made available in a Kaggle competition. For evaluating the algorithm's performance the benchmark data set Messidor-2 was used. We used the similar Messidor-Original data set to evaluate our algorithm's performance. In the original study licensed ophthalmologists re-graded all their obtained images for diabetic retinopathy, macular edema, and image gradability. Our challenge was to re-implement the methods with publicly available data sets and one diabetic retinopathy grade per image, find the hyper-parameter settings for training and validation that were not described in the original study, and make an assessment on the impact of training with ungradable images. We were not able to reproduce the performance as reported in the original study. We believe our model did not learn to recognize lesions in fundus images, since we only had a singular grade for diabetic retinopathy per image, instead of multiple grades per images. Furthermore, the original study missed details regarding hyper-parameter settings for training and validation. The original study may also have used image quality grades as input for training the network. We believe that deep learning algorithms should be easily replicated, and that ideally source code should be published so that other researchers can confirm the results of the experiments. Our source code and instructions for running the replication are available at: this https URL

##### Abstract (translated by Google)
我们复制了一些实验，发表于2016年美国医学会杂志上的“用于检测视网膜眼底照片中的糖尿病视网膜病变的深度学习算法的开发和验证”; 316（22）。由于源代码不可用，我们重新实施了这些方法。最初的研究使用EyePACS和印度三家医院的眼底图像来训练他们的检测算法。我们使用了在Kaggle竞赛中提供的不同EyePACS数据集。为了评估算法的性能，使用了基准数据集Messidor-2。我们使用了类似的Messidor-Original数据集来评估我们的算法的性能。在最初的研究中，持照眼科医生将所有获得的图像重新分级为糖尿病性视网膜病变，黄斑水肿和图像渐变性。我们的挑战是重新实施公开可用的数据集和每个图像一个糖尿病视网膜病变级别的方法，找到原始研究中未描述的用于训练和验证的超参数设置，并对培训的影响进行评估与不可穿越的图像。我们无法重现原始研究报告中的表现。我们相信我们的模型没有学会识别眼底图像中的病变，因为我们每个图像只有糖尿病视网膜病变的单独分级，而不是每个图像的多个分级。此外，最初的研究漏掉了关于训练和验证的超参数设置的细节。原始研究也可能使用图像质量等级作为训练网络的输入。我们相信深度学习算法应该很容易被复制，理想的源代码应该被发布，以便其他研究人员可以确认实验的结果。我们的源代码和运行复制的说明可在以下网址获得：https网址

##### URL
[https://arxiv.org/abs/1803.04337](https://arxiv.org/abs/1803.04337)

##### PDF
[https://arxiv.org/pdf/1803.04337](https://arxiv.org/pdf/1803.04337)

