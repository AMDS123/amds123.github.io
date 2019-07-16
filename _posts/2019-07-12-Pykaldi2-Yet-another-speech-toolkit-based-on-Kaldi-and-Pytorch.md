---
layout: post
title: "Pykaldi2: Yet another speech toolkit based on Kaldi and Pytorch"
date: 2019-07-12 20:54:59
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Liang Lu, Xiong Xiao, Zhuo Chen, Yifan Gong
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce PyKaldi2 speech recognition toolkit implemented based on Kaldi and PyTorch. While similar toolkits are available built on top of the two, a key feature of PyKaldi2 is sequence training with criteria such as MMI, sMBR and MPE. In particular, we implemented the sequence training module with on-the-fly lattice generation during model training in order to simplify the training pipeline. To address the challenging acoustic environments in real applications, PyKaldi2 also supports on-the-fly noise and reverberation simulation to improve the model robustness. With this feature, it is possible to backpropogate the gradients from the sequence-level loss to the front-end feature extraction module, which, hopefully, can foster more research in the direction of joint front-end and backend learning. We performed benchmark experiments on Librispeech, and show that PyKaldi2 can achieve reasonable recognition accuracy. The toolkit is released under the MIT license.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05955](http://arxiv.org/abs/1907.05955)

##### PDF
[http://arxiv.org/pdf/1907.05955](http://arxiv.org/pdf/1907.05955)

