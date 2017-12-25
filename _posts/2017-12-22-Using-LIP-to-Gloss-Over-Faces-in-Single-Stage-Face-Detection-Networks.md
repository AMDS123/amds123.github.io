---
layout: post
title: "Using LIP to Gloss Over Faces in Single-Stage Face Detection Networks"
date: 2017-12-22 00:42:42
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Face Detection Face_Detection Relation
author: Siqi Yang, Arnold Wiliem, Shaokang Chen, Brian C. Lovell
mathjax: true
---

* content
{:toc}

##### Abstract
This work shows that it is possible to fool/attack recent state-of-the-art face detectors which are based on the single-stage networks. Successfully attacking face detectors could be a serious malware vulnerability when deploying a smart surveillance system utilizing face detectors. We show that existing adversarial perturbation methods are not effective to perform such an attack, especially when there are multiple faces in the input image. This is because the adversarial perturbation specifically generated for one face may disrupt the adversarial perturbation for another face. In this paper, we call this problem the Instance Perturbation Interference (IPI) problem. This IPI problem is addressed by studying the relationship between the deep neural network receptive field and the adversarial perturbation. As such, we propose the Localized Instance Perturbation (LIP) that uses adversarial perturbation constrained to the Effective Receptive Field (ERF) of a target to perform the attack. Experiment results show the LIP method massively outperforms existing adversarial perturbation generation methods -- often by a factor of 2 to 10.

##### Abstract (translated by Google)
这项工作表明，有可能愚弄/攻击基于单级网络的最新的最先进的面部检测器。在部署使用人脸检测器的智能监控系统时，成功攻击人脸检测器可能是一个严重的恶意软件漏洞。我们表明，现有的敌对扰动方法不能有效地执行这种攻击，特别是当输入图像中有多个面时。这是因为专门针对一个脸部产生的对抗性扰动可能扰乱另一张脸的对抗性扰动。在本文中，我们把这个问题称为实例摄动干扰（IPI）问题。通过研究深度神经网络接受场与对抗性扰动之间的关系来解决IPI问题。因此，我们提出了使用限制于目标的有效接受场（ERF）的敌对扰动来执行攻击的本地化实例摄动（LIP）。实验结果表明，LIP方法大大优于现有的对抗扰动生成方法 - 通常是2到10倍。

##### URL
[https://arxiv.org/abs/1712.08263](https://arxiv.org/abs/1712.08263)

##### PDF
[https://arxiv.org/pdf/1712.08263](https://arxiv.org/pdf/1712.08263)

