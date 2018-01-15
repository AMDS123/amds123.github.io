---
layout: post
title: "Twin Networks: Matching the Future for Sequence Generation"
date: 2018-01-11 22:09:36
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Caption Inference RNN Recognition
author: Dmitriy Serdyuk, Nan Rosemary Ke, Alessandro Sordoni, Adam Trischler, Chris Pal, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a simple technique for encouraging generative RNNs to plan ahead. We train a "backward" recurrent network to generate a given sequence in reverse order, and we encourage states of the forward model to predict cotemporal states of the backward model. The backward network is used only during training, and plays no role during sampling or inference. We hypothesize that our approach eases modeling of long-term dependencies by implicitly forcing the forward states to hold information about the longer-term future (as contained in the backward states). We show empirically that our approach achieves 9% relative improvement for a speech recognition task, and achieves significant improvement on a COCO caption generation task.

##### Abstract (translated by Google)
我们提出一个简单的技术来鼓励生成的RNN提前计划。我们训练一个“后向”循环网络，以相反的顺序产生一个给定的序列，我们鼓励正演模型的状态来预测后向模型的时间状态。后向网络仅在训练期间使用，在采样或推理期间不起作用。我们假设我们的方法通过隐含地迫使前面的状态持有关于长期未来（包含在落后状态中）的信息来简化长期依赖性的建模。我们经验地显示，我们的方法在语音识别任务方面实现了9％的相对改进，并且在COCO字幕生成任务上实现了显着的改进。

##### URL
[https://arxiv.org/abs/1708.06742](https://arxiv.org/abs/1708.06742)

##### PDF
[https://arxiv.org/pdf/1708.06742](https://arxiv.org/pdf/1708.06742)

