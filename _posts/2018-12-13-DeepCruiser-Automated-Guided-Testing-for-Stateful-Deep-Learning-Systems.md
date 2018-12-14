---
layout: post
title: "DeepCruiser: Automated Guided Testing for Stateful Deep Learning Systems"
date: 2018-12-13 09:49:58
categories: arXiv_AI
tags: arXiv_AI RNN Deep_Learning
author: Xiaoning Du, Xiaofei Xie, Yi Li, Lei Ma, Jianjun Zhao, Yang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning (DL) defines a data-driven programming paradigm that automatically composes the system decision logic from the training data. In company with the data explosion and hardware acceleration during the past decade, DL achieves tremendous success in many cutting-edge applications. However, even the state-of-the-art DL systems still suffer from quality and reliability issues. It was only until recently that some preliminary progress was made in testing feed-forward DL systems. In contrast to feed-forward DL systems, recurrent neural networks (RNN) follow a very different architectural design, implementing temporal behaviors and memory with loops and internal states. Such stateful nature of RNN contributes to its success in handling sequential inputs such as audio, natural languages and video processing, but also poses new challenges for quality assurance. 
 In this paper, we initiate the very first step towards testing RNN-based stateful DL systems. We model RNN as an abstract state transition system, based on which we define a set of test coverage criteria specialized for stateful DL systems. Moreover, we propose an automated testing framework, DeepCruiser, which systematically generates tests in large scale to uncover defects of stateful DL systems with coverage guidance. Our in-depth evaluation on a state-of-the-art speech-to-text DL system demonstrates the effectiveness of our technique in improving quality and reliability of stateful DL systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05339](http://arxiv.org/abs/1812.05339)

##### PDF
[http://arxiv.org/pdf/1812.05339](http://arxiv.org/pdf/1812.05339)

