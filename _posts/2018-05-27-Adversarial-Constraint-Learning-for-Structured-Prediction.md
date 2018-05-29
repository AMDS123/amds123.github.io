---
layout: post
title: "Adversarial Constraint Learning for Structured Prediction"
date: 2018-05-27 01:27:28
categories: arXiv_CV
tags: arXiv_CV Adversarial Pose_Estimation Tracking Prediction Relation
author: Hongyu Ren, Russell Stewart, Jiaming Song, Volodymyr Kuleshov, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
Constraint-based learning reduces the burden of collecting labels by having users specify general properties of structured outputs, such as constraints imposed by physical laws. We propose a novel framework for simultaneously learning these constraints and using them for supervision, bypassing the difficulty of using domain expertise to manually specify constraints. Learning requires a black-box simulator of structured outputs, which generates valid labels, but need not model their corresponding inputs or the input-label relationship. At training time, we constrain the model to produce outputs that cannot be distinguished from simulated labels by adversarial training. Providing our framework with a small number of labeled inputs gives rise to a new semi-supervised structured prediction model; we evaluate this model on multiple tasks --- tracking, pose estimation and time series prediction --- and find that it achieves high accuracy with only a small number of labeled inputs. In some cases, no labels are required at all.

##### Abstract (translated by Google)
基于约束的学习通过让用户指定结构化输出的一般属性（例如由物理法则施加的约束）来减轻收集标签的负担。我们提出了一种新颖的框架，用于同时学习这些约束条件并将其用于监督，绕过使用领域专业知识来手动指定约束的困难。学习需要一个结构化输出的黑盒模拟器，它可以生成有效的标签，但不需要对相应的输入或输入标签关系进行建模。在训练时，我们限制模型产生无法通过对抗训练与模拟标签区分的输出。为我们的框架提供少量标记的输入可以产生一个新的半监督结构化预测模型;我们评估这个模型的多任务---跟踪，姿态估计和时间序列预测---并发现它只用少量的标记输入即可实现高精度。在某些情况下，根本不需要标签。

##### URL
[http://arxiv.org/abs/1805.10561](http://arxiv.org/abs/1805.10561)

##### PDF
[http://arxiv.org/pdf/1805.10561](http://arxiv.org/pdf/1805.10561)

