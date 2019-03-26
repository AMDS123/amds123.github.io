---
layout: post
title: "Automated pulmonary nodule detection using 3D deep convolutional neural networks"
date: 2019-03-23 20:20:15
categories: arXiv_AI
tags: arXiv_AI Object_Detection Attention CNN Prediction Detection
author: Hao Tang, Daniel R. Kim, Xiaohui Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Early detection of pulmonary nodules in computed tomography (CT) images is essential for successful outcomes among lung cancer patients. Much attention has been given to deep convolutional neural network (DCNN)-based approaches to this task, but models have relied at least partly on 2D or 2.5D components for inherently 3D data. In this paper, we introduce a novel DCNN approach, consisting of two stages, that is fully three-dimensional end-to-end and utilizes the state-of-the-art in object detection. First, nodule candidates are identified with a U-Net-inspired 3D Faster R-CNN trained using online hard negative mining. Second, false positive reduction is performed by 3D DCNN classifiers trained on difficult examples produced during candidate screening. Finally, we introduce a method to ensemble models from both stages via consensus to give the final predictions. By using this framework, we ranked first of 2887 teams in Season One of Alibaba's 2017 TianChi AI Competition for Healthcare.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09876](http://arxiv.org/abs/1903.09876)

##### PDF
[http://arxiv.org/pdf/1903.09876](http://arxiv.org/pdf/1903.09876)

