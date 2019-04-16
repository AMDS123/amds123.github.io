---
layout: post
title: "Inductive Visual Localisation: Factorised Training for Superior Generalisation"
date: 2018-07-21 17:09:16
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Recognition
author: Ankush Gupta, Andrea Vedaldi, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end trained Recurrent Neural Networks (RNNs) have been successfully applied to numerous problems that require processing sequences, such as image captioning, machine translation, and text recognition. However, RNNs often struggle to generalise to sequences longer than the ones encountered during training. In this work, we propose to optimise neural networks explicitly for induction. The idea is to first decompose the problem in a sequence of inductive steps and then to explicitly train the RNN to reproduce such steps. Generalisation is achieved as the RNN is not allowed to learn an arbitrary internal state; instead, it is tasked with mimicking the evolution of a valid state. In particular, the state is restricted to a spatial memory map that tracks parts of the input image which have been accounted for in previous steps. The RNN is trained for single inductive steps, where it produces updates to the memory in addition to the desired output. We evaluate our method on two different visual recognition problems involving visual sequences: (1) text spotting, i.e. joint localisation and reading of text in images containing multiple lines (or a block) of text, and (2) sequential counting of objects in aerial images. We show that inductive training of recurrent models enhances their generalisation ability on challenging image datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.08179](https://arxiv.org/abs/1807.08179)

##### PDF
[https://arxiv.org/pdf/1807.08179](https://arxiv.org/pdf/1807.08179)

