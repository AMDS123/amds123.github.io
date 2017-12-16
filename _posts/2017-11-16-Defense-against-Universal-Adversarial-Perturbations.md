---
layout: post
title: "Defense against Universal Adversarial Perturbations"
date: 2017-11-16 05:08:49
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Deep_Learning Prediction Detection
author: Naveed Akhtar, Jian Liu, Ajmal Mian
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in Deep Learning show the existence of image-agnostic quasi-imperceptible perturbations that when applied to `any' image can fool a state-of-the-art network classifier to change its prediction about the image label. These `Universal Adversarial Perturbations' pose a serious threat to the success of Deep Learning in practice. We present the first dedicated framework to effectively defend the networks against such perturbations. Our approach learns a Perturbation Rectifying Network (PRN) as `pre-input' layers to a targeted model, such that the targeted model needs no modification. The PRN is learned from real and synthetic image-agnostic perturbations, where an efficient method to compute the latter is also proposed. A perturbation detector is separately trained on the Discrete Cosine Transform of the input-output difference of the PRN. A query image is first passed through the PRN and verified by the detector. If a perturbation is detected, the output of the PRN is used for label prediction instead of the actual image. A rigorous evaluation shows that our framework can defend the network classifiers against unseen adversarial perturbations in the real-world scenarios with up to 97.5% success rate. The PRN also generalizes well in the sense that training for one targeted network defends another network with a comparable success rate.

##### Abstract (translated by Google)
深度学习的最新进展表明，存在图像不可知的准不可察觉的干扰，当应用于“任何”图像可以欺骗一个最先进的网络分类器来改变其对图像标签的预测。这些“普遍敌对扰动”对深度学习的实践成功构成严重威胁。我们提出了第一个专门的框架来有效地防御这些扰动的网络。我们的方法学习一个微扰整流网络（PRN）作为预输入层到目标模型，使得目标模型不需要修改。 PRN是从真实的和合成的图像不可知的摄动中学习的，其中还提出了计算后者的有效方法。扰动检测器分别在PRN的输入 - 输出差异的离散余弦变换上训练。查询图像首先通过PRN并由检测器验证。如果检测到扰动，则PRN的输出被用于标签预测而不是实际图像。严格的评估表明，我们的框架可以防御网络分类器，防止在现实世界的场景中看不见的敌对扰动，成功率高达97.5％。 PRN也得到了很好的推广，即对一个有针对性的网络进行的训练能够以相当的成功率来保护另一个网络。

##### URL
[https://arxiv.org/abs/1711.05929](https://arxiv.org/abs/1711.05929)

##### PDF
[https://arxiv.org/pdf/1711.05929](https://arxiv.org/pdf/1711.05929)

