---
layout: post
title: "Adversarial Attacks on Face Detectors using Neural Net based Constrained Optimization"
date: 2018-05-31 03:18:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Face Image_Classification Optimization Classification Detection
author: Avishek Joey Bose, Parham Aarabi
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial attacks involve adding, small, often imperceptible, perturbations to inputs with the goal of getting a machine learning model to misclassifying them. While many different adversarial attack strategies have been proposed on image classification models, object detection pipelines have been much harder to break. In this paper, we propose a novel strategy to craft adversarial examples by solving a constrained optimization problem using an adversarial generator network. Our approach is fast and scalable, requiring only a forward pass through our trained generator network to craft an adversarial sample. Unlike in many attack strategies, we show that the same trained generator is capable of attacking new images without explicitly optimizing on them. We evaluate our attack on a trained Faster R-CNN face detector on the cropped 300-W face dataset where we manage to reduce the number of detected faces to $0.5\%$ of all originally detected faces. In a different experiment, also on 300-W, we demonstrate the robustness of our attack to a JPEG compression based defense typical JPEG compression level of $75\%$ reduces the effectiveness of our attack from only $0.5\%$ of detected faces to a modest $5.0\%$.

##### Abstract (translated by Google)
敌对攻击涉及到对输入添加小的，往往难以察觉的扰动，目的是让机器学习模型对它们进行错误分类。尽管在图像分类模型上已经提出了许多不同的对抗攻击策略，但物体检测管线已经难以打破。在本文中，我们提出了一种新颖的策略，通过使用敌对生成器网络解决约束优化问题来制作敌对案例。我们的方法是快速和可扩展的，只需要通过我们训练的发电机网络的正向通路来制作对抗性样本。与许多攻击策略不同，我们表明，相同的训练过的发生器能够攻击新图像而不明确优化它们。我们在裁剪后的300-W人脸数据集上评估我们对受过训练的Faster R-CNN人脸检测器的攻击，我们设法将检测到的人脸数量减少到原来检测到的所有人脸的$ 0.5 \％$。在一个不同的实验中，也是在300-W上，我们证明了我们的攻击对基于JPEG压缩的防御的鲁棒性，典型的JPEG压缩级别为75美元/％$，将我们攻击的有效性从检测到的面孔的0.5％\％$减少到适度$ 5.0 \％$。

##### URL
[http://arxiv.org/abs/1805.12302](http://arxiv.org/abs/1805.12302)

##### PDF
[http://arxiv.org/pdf/1805.12302](http://arxiv.org/pdf/1805.12302)

