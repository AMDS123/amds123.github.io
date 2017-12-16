---
layout: post
title: "Encoder Based Lifelong Learning"
date: 2017-04-06 16:37:15
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Image_Classification Classification
author: Amal Rannen Triki, Rahaf Aljundi, Mathew B. Blaschko, Tinne Tuytelaars
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a new lifelong learning solution where a single model is trained for a sequence of tasks. The main challenge that vision systems face in this context is catastrophic forgetting: as they tend to adapt to the most recently seen task, they lose performance on the tasks that were learned previously. Our method aims at preserving the knowledge of the previous tasks while learning a new one by using autoencoders. For each task, an under-complete autoencoder is learned, capturing the features that are crucial for its achievement. When a new task is presented to the system, we prevent the reconstructions of the features with these autoencoders from changing, which has the effect of preserving the information on which the previous tasks are mainly relying. At the same time, the features are given space to adjust to the most recent environment as only their projection into a low dimension submanifold is controlled. The proposed system is evaluated on image classification tasks and shows a reduction of forgetting over the state-of-the-art

##### Abstract (translated by Google)
本文介绍了一种新的终身学习解决方案，其中单个模型被训练用于一系列任务。视觉系统面临的主要挑战是灾难性遗忘：由于他们倾向于适应最近看到的任务，他们在以前学到的任务上失去了表现。我们的方法旨在通过使用自动编码器来保存以前任务的知识，同时学习新的任务。对于每个任务，都会学习一个不完整的自动编码器，捕获对其成就至关重要的功能。当一个新的任务被提交给系统时，我们阻止了这些自编码器的特征的重构改变，这具有保留先前任务主要依赖的信息的效果。与此同时，这些特征被赋予空间以适应最近的环境，因为只有它们投影到低维子流形被控制。所提出的系统在图像分类任务上进行评估，并显示减少对现有技术的遗忘

##### URL
[https://arxiv.org/abs/1704.01920](https://arxiv.org/abs/1704.01920)

##### PDF
[https://arxiv.org/pdf/1704.01920](https://arxiv.org/pdf/1704.01920)

