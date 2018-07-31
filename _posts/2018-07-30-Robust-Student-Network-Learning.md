---
layout: post
title: "Robust Student Network Learning"
date: 2018-07-30 03:27:04
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Tianyu Guo, Chang Xu, Shiyi He, Boxin Shi, Chao Xu, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks bring in impressive accuracy in various applications, but the success often relies on the heavy network architecture. Taking well-trained heavy networks as teachers, classical teacher-student learning paradigm aims to learn a student network that is lightweight yet accurate. In this way, a portable student network with significantly fewer parameters can achieve a considerable accuracy which is comparable to that of teacher network. However, beyond accuracy, robustness of the learned student network against perturbation is also essential for practical uses. Existing teacher-student learning frameworks mainly focus on accuracy and compression ratios, but ignore the robustness. In this paper, we make the student network produce more confident predictions with the help of the teacher network, and analyze the lower bound of the perturbation that will destroy the confidence of the student network. Two important objectives regarding prediction scores and gradients of examples are developed to maximize this lower bound, so as to enhance the robustness of the student network without sacrificing the performance. Experiments on benchmark datasets demonstrate the efficiency of the proposed approach to learn robust student networks which have satisfying accuracy and compact sizes.

##### Abstract (translated by Google)
深度神经网络在各种应用中带来了令人印象深刻的准确性，但成功通常依赖于繁重的网络架构。以训练有素的重型网络为教师，经典的师生学习范式旨在学习轻量且准确的学生网络。通过这种方式，具有显着较少参数的便携式学生网络可以实现与教师网络相当的相当高的准确度。然而，除了准确性之外，学习网络对抗扰动的鲁棒性对于实际应用也是必不可少的。现有的师生学习框架主要关注准确性和压缩比，但忽略了鲁棒性。在本文中，我们使学生网络在教师网络的帮助下产生更自信的预测，并分析扰乱的下限，这将破坏学生网络的信心。开发了关于预测分数和示例梯度的两个重要目标，以最大化该下限，从而在不牺牲性能的情况下增强学生网络的鲁棒性。基准数据集上的实验证明了所提出的方法学习具有令人满意的准确性和紧凑尺寸的健壮学生网络的效率。

##### URL
[http://arxiv.org/abs/1807.11158](http://arxiv.org/abs/1807.11158)

##### PDF
[http://arxiv.org/pdf/1807.11158](http://arxiv.org/pdf/1807.11158)

