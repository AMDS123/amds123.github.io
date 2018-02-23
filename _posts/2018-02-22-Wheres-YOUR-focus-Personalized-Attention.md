---
layout: post
title: "Where's YOUR focus: Personalized Attention"
date: 2018-02-22 07:58:18
categories: arXiv_CV
tags: arXiv_CV Salient Attention CNN Prediction Detection
author: Sikun Lin, Pan Hui
mathjax: true
---

* content
{:toc}

##### Abstract
Human visual attention is subjective and biased according to the personal preference of the viewer, however, current works of saliency detection are general and objective, without counting the factor of the observer. This will make the attention prediction for a particular person not accurate enough. In this work, we present the novel idea of personalized attention prediction and develop Personalized Attention Network (PANet), a convolutional network that predicts saliency in images with personal preference. The model consists of two streams which share common feature extraction layers, and one stream is responsible for saliency prediction, while the other is adapted from the detection model and used to fit user preference. We automatically collect user preference from their albums and leaves them freedom to define what and how many categories their preferences are divided into. To train PANet, we dynamically generate ground truth saliency maps upon existing detection labels and saliency labels, and the generation parameters are based upon our collected datasets consists of 1k images. We evaluate the model with saliency prediction metrics and test the trained model on different preference vectors. The results have shown that our system is much better than general models in personalized saliency prediction and is efficient to use for different preferences.

##### Abstract (translated by Google)
人的视觉注意力是主观的，并且根据观众的个人偏好而有偏差，然而，目前的显着性检测工作是一般而客观的，没有计算观察者的因素。这将使得对特定人的关注度预测不够准确。在这项工作中，我们提出了个性化关注预测的新思路，并开发了个性化注意网络（PANet），一种可以预测个人喜好图像显着性的卷积网络。该模型由两个共享共同特征提取层的流组成，一个流负责显着性预测，另一个根据检测模型进行调整并用于适应用户偏好。我们会自动从他们的相册中收集用户偏好，并让他们自由定义他们的偏好分为多少种类。为了训练PANet，我们根据现有的检测标签和显着性标签动态生成地面真实显着图，并且生成参数基于我们收集的包含1k图像的数据集。我们用显着性预测度量来评估模型，并在不同的偏好向量上测试训练好的模型。结果表明，我们的系统在个性化显着性预测方面比一般模型好得多，并且可以有效地用于不同的偏好。

##### URL
[http://arxiv.org/abs/1802.07931](http://arxiv.org/abs/1802.07931)

##### PDF
[http://arxiv.org/pdf/1802.07931](http://arxiv.org/pdf/1802.07931)

