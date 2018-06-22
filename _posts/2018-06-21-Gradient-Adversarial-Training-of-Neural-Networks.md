---
layout: post
title: "Gradient Adversarial Training of Neural Networks"
date: 2018-06-21 00:54:07
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Classification Deep_Learning
author: Ayan Sinha, Zhao Chen, Vijay Badrinarayanan, Andrew Rabinovich
mathjax: true
---

* content
{:toc}

##### Abstract
We propose gradient adversarial training, an auxiliary deep learning framework applicable to different machine learning problems. In gradient adversarial training, we leverage a prior belief that in many contexts, simultaneous gradient updates should be statistically indistinguishable from each other. We enforce this consistency using an auxiliary network that classifies the origin of the gradient tensor, and the main network serves as an adversary to the auxiliary network in addition to performing standard task-based training. We demonstrate gradient adversarial training for three different scenarios: (1) as a defense to adversarial examples we classify gradient tensors and tune them to be agnostic to the class of their corresponding example, (2) for knowledge distillation, we do binary classification of gradient tensors derived from the student or teacher network and tune the student gradient tensor to mimic the teacher's gradient tensor; and (3) for multi-task learning we classify the gradient tensors derived from different task loss functions and tune them to be statistically indistinguishable. For each of the three scenarios we show the potential of gradient adversarial training procedure. Specifically, gradient adversarial training increases the robustness of a network to adversarial attacks, is able to better distill the knowledge from a teacher network to a student network compared to soft targets, and boosts multi-task learning by aligning the gradient tensors derived from the task specific loss functions. Overall, our experiments demonstrate that gradient tensors contain latent information about whatever tasks are being trained, and can support diverse machine learning problems when intelligently guided through adversarialization using a auxiliary network.

##### Abstract (translated by Google)
我们提出梯度对抗训练，适用于不同机器学习问题的辅助深度学习框架。在梯度对抗训练中，我们利用先前的观点，即在许多情况下，同时渐变更新应该在统计上彼此不可区分。我们使用对梯度张量的起源进行分类的辅助网络来执行此一致性，除了执行基于标准任务的训练之外，主网络还充当辅助网络的对手。我们展示了三种不同情景下的梯度对抗训练：（1）作为对抗性例子的辩护，我们对梯度张量进行分类，并将它们调整为与它们相应的例子的类别无关，（2）对于知识蒸馏，我们进行梯度二元分类张量来自学生或教师网络并调整学生梯度张量以模拟教师的梯度张量; （3）对于多任务学习，我们对从不同任务损失函数导出的梯度张量进行分类，并将它们调整为统计上不可区分的。对于三种场景中的每一种，我们都会展示梯度对抗训练过程的潜力。具体来说，梯度对抗训练增加了网络对敌对攻击的鲁棒性，与软目标相比，能够更好地从教师网络向学生网络提取知识，并通过对齐从任务派生的梯度张量来促进多任务学习具体的损失函数。总体而言，我们的实验表明，梯度张量包含有关任何正在训练的任务的潜在信息，并且可以支持各种机器学习问题，这些问题在使用辅助网络进行智能化对抗时能够得到智能指导。

##### URL
[http://arxiv.org/abs/1806.08028](http://arxiv.org/abs/1806.08028)

##### PDF
[http://arxiv.org/pdf/1806.08028](http://arxiv.org/pdf/1806.08028)

