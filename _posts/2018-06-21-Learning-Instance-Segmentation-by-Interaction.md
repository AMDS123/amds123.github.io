---
layout: post
title: "Learning Instance Segmentation by Interaction"
date: 2018-06-21 17:59:09
categories: arXiv_AI
tags: arXiv_AI Segmentation
author: Deepak Pathak, Yide Shentu, Dian Chen, Pulkit Agrawal, Trevor Darrell, Sergey Levine, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach for building an active agent that learns to segment its visual observations into individual objects by interacting with its environment in a completely self-supervised manner. The agent uses its current segmentation model to infer pixels that constitute objects and refines the segmentation model by interacting with these pixels. The model learned from over 50K interactions generalizes to novel objects and backgrounds. To deal with noisy training signal for segmenting objects obtained by self-supervised interactions, we propose robust set loss. A dataset of robot's interactions along-with a few human labeled examples is provided as a benchmark for future research. We test the utility of the learned segmentation model by providing results on a downstream vision-based control task of rearranging multiple objects into target configurations from visual inputs alone. Videos, code, and robotic interaction dataset are available at https://pathak22.github.io/seg-by-interaction/

##### Abstract (translated by Google)
我们提出了一种建立活动代理的方法，该活动代理通过以完全自我监督的方式与其环境交互来学习将其视觉观察分割成单个对象。该代理使用其当前的分段模型来推断构成对象的像素，并通过与这些像素交互来细化分割模型。从超过50K的交互中学习的模型概括为新的对象和背景。为了处理通过自监督交互获得的分割对象的噪声训练信号，我们提出了鲁棒的集合损失。机器人相互作用的数据集 - 与一些人为标记的例子一起提供作为未来研究的基准。我们通过在下游基于视觉的控制任务上提供结果来测试学习的分割模型的效用，该控制任务将多个对象从单独的视觉输入重新排列为目标配置。视频，代码和机器人交互数据集可在https://pathak22.github.io/seg-by-interaction/上获得

##### URL
[http://arxiv.org/abs/1806.08354](http://arxiv.org/abs/1806.08354)

##### PDF
[http://arxiv.org/pdf/1806.08354](http://arxiv.org/pdf/1806.08354)

