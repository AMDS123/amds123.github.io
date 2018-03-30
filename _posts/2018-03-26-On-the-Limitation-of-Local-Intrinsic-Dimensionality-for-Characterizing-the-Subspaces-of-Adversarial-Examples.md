---
layout: post
title: "On the Limitation of Local Intrinsic Dimensionality for Characterizing the Subspaces of Adversarial Examples"
date: 2018-03-26 14:56:28
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Pei-Hsuan Lu, Pin-Yu Chen, Chia-Mu Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding and characterizing the subspaces of adversarial examples aid in studying the robustness of deep neural networks (DNNs) to adversarial perturbations. Very recently, Ma et al. (ICLR 2018) proposed to use local intrinsic dimensionality (LID) in layer-wise hidden representations of DNNs to study adversarial subspaces. It was demonstrated that LID can be used to characterize the adversarial subspaces associated with different attack methods, e.g., the Carlini and Wagner's (C&W) attack and the fast gradient sign attack. In this paper, we use MNIST and CIFAR-10 to conduct two new sets of experiments that are absent in existing LID analysis and report the limitation of LID in characterizing the corresponding adversarial subspaces, which are (i) oblivious attacks and LID analysis using adversarial examples with different confidence levels; and (ii) black-box transfer attacks. For (i), we find that the performance of LID is very sensitive to the confidence parameter deployed by an attack, and the LID learned from ensembles of adversarial examples with varying confidence levels surprisingly gives poor performance. For (ii), we find that when adversarial examples are crafted from another DNN model, LID is ineffective in characterizing their adversarial subspaces. These two findings together suggest the limited capability of LID in characterizing the subspaces of adversarial examples.

##### Abstract (translated by Google)
理解和表征对抗性例子的子空间有助于研究深度神经网络（DNNs）对敌对扰动的鲁棒性。最近，马等人。 （ICLR 2018）提出使用局部内在维度（LID）在DNN的层次隐藏表示中研究敌对子空间。已经证明LID可用于表征与不同攻击方法相关的对抗子空间，例如Carlini和Wagner（C＆W）攻击和快速梯度符号攻击。在本文中，我们使用MNIST和CIFAR-10来进行两组新的实验，这些实验在现有的LID分析中不存在，并报告了LID在表征相应的对抗子空间方面的局限性，这些子空间是（i）利用对抗的不经意攻击和LID分析具有不同置信度的例子;和（ii）黑盒传输攻击。对于（i），我们发现LID的表现对于攻击所部署的置信度参数非常敏感，并且LID从具有不同置信水平的敌对示例集合中学习，令人惊讶地表现出糟糕的表现。对于（ii），我们发现，当敌对的例子是从另一个DNN模型制作的时候，LID在表征它们的敌对子空间方面是无效的。这两个发现一起表明LID在表征对抗事例子空间方面的能力有限。

##### URL
[https://arxiv.org/abs/1803.09638](https://arxiv.org/abs/1803.09638)

##### PDF
[https://arxiv.org/pdf/1803.09638](https://arxiv.org/pdf/1803.09638)

