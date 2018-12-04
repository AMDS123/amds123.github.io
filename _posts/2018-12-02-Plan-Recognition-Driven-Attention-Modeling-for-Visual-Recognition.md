---
layout: post
title: "Plan-Recognition-Driven Attention Modeling for Visual Recognition"
date: 2018-12-02 02:07:06
categories: arXiv_AI
tags: arXiv_AI Attention CNN Recognition
author: Yantian Zha, Yikang Li, Tianshu Yu, Subbarao Kambhampati, Baoxin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Human visual recognition of activities or external agents involves an interplay between high-level plan recognition and low-level perception. Given that, a natural question to ask is: can low-level perception be improved by high-level plan recognition? We formulate the problem of leveraging recognized plans to generate better top-down attention maps \cite{gazzaniga2009,baluch2011} to improve the perception performance. We call these top-down attention maps specifically as plan-recognition-driven attention maps. To address this problem, we introduce the Pixel Dynamics Network. Pixel Dynamics Network serves as an observation model, which predicts next states of object points at each pixel location given observation of pixels and pixel-level action feature. This is like internally learning a pixel-level dynamics model. Pixel Dynamics Network is a kind of Convolutional Neural Network (ConvNet), with specially-designed architecture. Therefore, Pixel Dynamics Network could take the advantage of parallel computation of ConvNets, while learning the pixel-level dynamics model. We further prove the equivalence between Pixel Dynamics Network as an observation model, and the belief update in partially observable Markov decision process (POMDP) framework. We evaluate our Pixel Dynamics Network in event recognition tasks. We build an event recognition system, ER-PRN, which takes Pixel Dynamics Network as a subroutine, to recognize events based on observations augmented by plan-recognition-driven attention.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00301](http://arxiv.org/abs/1812.00301)

##### PDF
[http://arxiv.org/pdf/1812.00301](http://arxiv.org/pdf/1812.00301)

