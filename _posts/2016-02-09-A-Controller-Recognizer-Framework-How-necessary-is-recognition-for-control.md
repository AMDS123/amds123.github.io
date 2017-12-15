---
layout: post
title: "A Controller-Recognizer Framework: How necessary is recognition for control?"
date: 2016-02-09 20:58:21
categories: arXiv_CV
tags: arXiv_CV Attention Face Recognition
author: Marcin Moczulski, Kelvin Xu, Aaron Courville, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
Recently there has been growing interest in building active visual object recognizers, as opposed to the usual passive recognizers which classifies a given static image into a predefined set of object categories. In this paper we propose to generalize these recently proposed end-to-end active visual recognizers into a controller-recognizer framework. A model in the controller-recognizer framework consists of a controller, which interfaces with an external manipulator, and a recognizer which classifies the visual input adjusted by the manipulator. We describe two most recently proposed controller-recognizer models: recurrent attention model and spatial transformer network as representative examples of controller-recognizer models. Based on this description we observe that most existing end-to-end controller-recognizers tightly, or completely, couple a controller and recognizer. We ask a question whether this tight coupling is necessary, and try to answer this empirically by building a controller-recognizer model with a decoupled controller and recognizer. Our experiments revealed that it is not always necessary to tightly couple them and that by decoupling a controller and recognizer, there is a possibility of building a generic controller that is pretrained and works together with any subsequent recognizer.

##### Abstract (translated by Google)
最近，人们越来越关注构建主动视觉对象识别器，而不是将通常的被动识别器将给定的静态图像分类为预定义的对象类别集合。在本文中，我们建议将这些最近提出的端到端主动视觉识别器推广到控制器识别器框架中。控制器识别器框架中的模型由与外部操纵器接口的控制器和分类由操纵器调整的视觉输入的识别器组成。我们描述两个最近提出的控制器识别器模型：经常性关注模型和空间变换器网络作为控制器识别器模型的代表性例子。根据这一描述，我们观察到大多数现有的端到端控制器识别器紧密地或完全地耦合了一个控制器和识别器。我们问一个问题：这种紧密耦合是否是必要的，并试图通过建立一个带有解耦控制器和识别器的控制器 - 识别器模型来经验地回答这个问题。我们的实验显示，将它们紧密结合并不总是必要的，通过将控制器和识别器分离，有可能建立一个经过预训练并与任何后续识别器一起工作的通用控制器。

##### URL
[https://arxiv.org/abs/1511.06428](https://arxiv.org/abs/1511.06428)

##### PDF
[https://arxiv.org/pdf/1511.06428](https://arxiv.org/pdf/1511.06428)

