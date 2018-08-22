---
layout: post
title: "Text-to-image Synthesis via Symmetrical Distillation Networks"
date: 2018-08-21 08:54:23
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Mingkuan Yuan, Yuxin Peng
mathjax: true
---

* content
{:toc}

##### Abstract
Text-to-image synthesis aims to automatically generate images according to text descriptions given by users, which is a highly challenging task. The main issues of text-to-image synthesis lie in two gaps: the heterogeneous and homogeneous gaps. The heterogeneous gap is between the high-level concepts of text descriptions and the pixel-level contents of images, while the homogeneous gap exists between synthetic image distributions and real image distributions. For addressing these problems, we exploit the excellent capability of generic discriminative models (e.g. VGG19), which can guide the training process of a new generative model on multiple levels to bridge the two gaps. The high-level representations can teach the generative model to extract necessary visual information from text descriptions, which can bridge the heterogeneous gap. The mid-level and low-level representations can lead it to learn structures and details of images respectively, which relieves the homogeneous gap. Therefore, we propose Symmetrical Distillation Networks (SDN) composed of a source discriminative model as "teacher" and a target generative model as "student". The target generative model has a symmetrical structure with the source discriminative model, in order to transfer hierarchical knowledge accessibly. Moreover, we decompose the training process into two stages with different distillation paradigms for promoting the performance of the target generative model. Experiments on two widely-used datasets are conducted to verify the effectiveness of our proposed SDN.

##### Abstract (translated by Google)
文本到图像合成旨在根据用户给出的文本描述自动生成图像，这是一项极具挑战性的任务。文本到图像合成的主要问题在于两个差距：异质和均匀的差距。异构差距介于文本描述的高级概念和图像的像素级内容之间，而合成图像分布与实际图像分布之间存在同质差距。为了解决这些问题，我们利用通用判别模型（例如VGG19）的出色能力，可以在多个层面上指导新生成模型的训练过程，以弥合这两个空白。高级表示可以教导生成模型从文本描述中提取必要的视觉信息，这可以弥合异质性差距。中级和低级表示可以使其分别学习图像的结构和细节，从而减轻了均匀的差距。因此，我们提出了对称蒸馏网络（SDN），其由作为“教师”的源判别模型和作为“学生”的目标生成模型组成。目标生成模型具有源对称模型的对称结构，以便可访问地传递分层知识。此外，我们将训练过程分解为两个阶段，使用不同的蒸馏范例来提升目标生成模型的性能。对两个广泛使用的数据集进行了实验，以验证我们提出的SDN的有效性。

##### URL
[http://arxiv.org/abs/1808.06801](http://arxiv.org/abs/1808.06801)

##### PDF
[http://arxiv.org/pdf/1808.06801](http://arxiv.org/pdf/1808.06801)

