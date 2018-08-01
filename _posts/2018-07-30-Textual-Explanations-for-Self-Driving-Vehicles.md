---
layout: post
title: "Textual Explanations for Self-Driving Vehicles"
date: 2018-07-30 19:38:24
categories: arXiv_CV
tags: arXiv_CV Attention CNN
author: Jinkyu Kim, Anna Rohrbach, Trevor Darrell, John Canny, Zeynep Akata
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural perception and control networks have become key components of self-driving vehicles. User acceptance is likely to benefit from easy-to-interpret textual explanations which allow end-users to understand what triggered a particular behavior. Explanations may be triggered by the neural controller, namely introspective explanations, or informed by the neural controller's output, namely rationalizations. We propose a new approach to introspective explanations which consists of two parts. First, we use a visual (spatial) attention model to train a convolutional network end-to-end from images to the vehicle control commands, i.e., acceleration and change of course. The controller's attention identifies image regions that potentially influence the network's output. Second, we use an attention-based video-to-text model to produce textual explanations of model actions. The attention maps of controller and explanation model are aligned so that explanations are grounded in the parts of the scene that mattered to the controller. We explore two approaches to attention alignment, strong- and weak-alignment. Finally, we explore a version of our model that generates rationalizations, and compare with introspective explanations on the same video segments. We evaluate these models on a novel driving dataset with ground-truth human explanations, the Berkeley DeepDrive eXplanation (BDD-X) dataset. Code is available at https://github.com/JinkyuKimUCB/explainable-deep-driving.

##### Abstract (translated by Google)
深度神经感知和控制网络已成为自动驾驶车辆的关键部件。用户接受可能会受益于易于理解的文本解释，这些解释允许最终用户了解触发特定行为的原因。解释可以由神经控制器触发，即内省解释，或者由神经控制器的输出，即合理化来提供。我们提出了一种内省解释的新方法，它由两部分组成。首先，我们使用视觉（空间）注意模型来训练从图像到车辆控制命令的端到端卷积网络，即加速和改变当然。控制器注意识别可能影响网络输出的图像区域。其次，我们使用基于注意力的视频到文本模型来生成模型动作的文本解释。控制器和解释模型的注意图是对齐的，因此解释基于对控制器很重要的场景部分。我们探讨了注意力对齐的两种方法，即强对齐和弱对齐。最后，我们探索了一个生成合理化的模型版本，并与同一视频片段的内省解释进行比较。我们在一个新颖的驾驶数据集上评估这些模型，其中包括真实的人类解释，Berkeley DeepDrive eXplanation（BDD-X）数据集。代码可在https://github.com/JinkyuKimUCB/explainable-deep-driving获得。

##### URL
[http://arxiv.org/abs/1807.11546](http://arxiv.org/abs/1807.11546)

##### PDF
[http://arxiv.org/pdf/1807.11546](http://arxiv.org/pdf/1807.11546)

