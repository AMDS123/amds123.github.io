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


##### URL
[https://arxiv.org/abs/1708.06742](https://arxiv.org/abs/1708.06742)

##### PDF
[https://arxiv.org/pdf/1708.06742](https://arxiv.org/pdf/1708.06742)

