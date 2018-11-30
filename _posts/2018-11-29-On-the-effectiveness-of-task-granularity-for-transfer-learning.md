---
layout: post
title: "On the effectiveness of task granularity for transfer learning"
date: 2018-11-29 03:59:19
categories: arXiv_CV
tags: arXiv_CV Caption Transfer_Learning Video_Classification Classification
author: Farzaneh Mahdisoltani, Guillaume Berger, Waseem Gharbieh, David Fleet, Roland Memisevic
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a DNN for video classification and captioning, trained end-to-end, with shared features, to solve tasks at different levels of granularity, exploring the link between granularity in a source task and the quality of learned features for transfer learning. For solving the new task domain in transfer learning, we freeze the trained encoder and fine-tune a neural net on the target domain. We train on the Something-Something dataset with over 220, 000 videos, and multiple levels of target granularity, including 50 action groups, 174 fine-grained action categories and captions. Classification and captioning with Something-Something are challenging because of the subtle differences between actions, applied to thousands of different object classes, and the diversity of captions penned by crowd actors. Our model performs better than existing classification baselines for SomethingSomething, with impressive fine-grained results. And it yields a strong baseline on the new Something-Something captioning task. Experiments reveal that training with more fine-grained tasks tends to produce better features for transfer learning.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.09235](https://arxiv.org/abs/1804.09235)

##### PDF
[https://arxiv.org/pdf/1804.09235](https://arxiv.org/pdf/1804.09235)

