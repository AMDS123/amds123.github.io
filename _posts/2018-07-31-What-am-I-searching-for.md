---
layout: post
title: "What am I searching for?"
date: 2018-07-31 17:15:11
categories: arXiv_AI
tags: arXiv_AI CNN Inference
author: Mengmi Zhang, Jiashi Feng, Joo Hwee Lim, Qi Zhao, Gabriel Kreiman
mathjax: true
---

* content
{:toc}

##### Abstract
Can we infer intentions and goals from a person's actions? As an example of this family of problems, we consider here whether it is possible to decipher what a person is searching for by decoding their eye movement behavior. We conducted two human psychophysics experiments on object arrays and natural images where we monitored subjects' eye movements while they were looking for a target object. Using as input the pattern of "error" fixations on non-target objects before the target was found, we developed a model (InferNet) whose goal was to infer what the target was. "Error" fixations share similar features with the sought target. The Infernet model uses a pre-trained 2D convolutional architecture to extract features from the error fixations and computes a 2D similarity map between the error fixation and all locations across the search image by modulating the search image via convolution across layers. InferNet consolidates the modulated response maps across layers via max pooling to keep track of the sub-patterns highly similar to features at error fixations and integrates these maps across all error fixations. InferNet successfully identifies the subject's goal and outperforms all the competitive null models, even without any object-specific training on the inference task.

##### Abstract (translated by Google)
我们可以从一个人的行为中推断出意图和目标吗？作为这一系列问题的一个例子，我们在这里考虑是否有可能通过解码他们的眼动行为来破译一个人正在寻找的东西。我们在物体阵列和自然图像上进行了两次人体心理物理学实验，我们在寻找目标物体时监测受试者的眼球运动。在找到目标之前，使用非目标对象上的“错误”注视模式作为输入，我们开发了一个模型（InferNet），其目标是推断目标是什么。 “错误”注视与所寻求的目标具有相似的特征。 Infernet模型使用预先训练的2D卷积体系结构从错误定位中提取特征，并通过跨层的卷积调制搜索图像来计算错误固定与搜索图像上的所有位置之间的2D相似性图。 InferNet通过最大池整合跨层的调制响应图，以跟踪与错误修复中的特征高度相似的子模式，并在所有错误修复中集成这些映射。即使没有对推理任务进行任何特定于对象的培训，InferNet也能成功识别主题的目标，并且优于所有竞争性的空模型。

##### URL
[http://arxiv.org/abs/1807.11926](http://arxiv.org/abs/1807.11926)

##### PDF
[http://arxiv.org/pdf/1807.11926](http://arxiv.org/pdf/1807.11926)

