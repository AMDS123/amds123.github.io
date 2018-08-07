---
layout: post
title: "Twin Networks: Matching the Future for Sequence Generation"
date: 2018-02-23 19:54:36
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
我们提出了一种简单的技术来鼓励生成性RNN提前计划。我们训练“后向”循环网络以相反的顺序生成给定序列，并且我们鼓励前向模型的状态来预测后向模型的时空状态。后向网络仅在训练期间使用，并且在采样或推理期间不起作用。我们假设我们的方法通过隐式强制前向状态来保存有关长期未来的信息（包含在后向状态中），从而简化了长期依赖关系的建模。我们凭经验证明，我们的方法在语音识别任务中实现了9％的相对改进，并在COCO字幕生成任务上实现了显着改进。

##### URL
[https://arxiv.org/abs/1708.06742](https://arxiv.org/abs/1708.06742)

##### PDF
[https://arxiv.org/pdf/1708.06742](https://arxiv.org/pdf/1708.06742)

