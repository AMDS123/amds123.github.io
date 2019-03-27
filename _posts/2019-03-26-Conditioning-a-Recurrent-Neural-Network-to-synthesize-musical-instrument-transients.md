---
layout: post
title: "Conditioning a Recurrent Neural Network to synthesize musical instrument transients"
date: 2019-03-26 06:33:35
categories: arXiv_SD
tags: arXiv_SD RNN
author: Lonce Wyse, Muhammad Huzaifah
mathjax: true
---

* content
{:toc}

##### Abstract
A recurrent Neural Network (RNN) is trained to predict sound samples based on audio input augmented by control parameter information for pitch, volume, and instrument identification. During the generative phase following training, audio input is taken from the output of the previous time step, and the parameters are externally controlled allowing the network to be played as a musical instrument. Building on an architecture developed in previous work, we focus on the learning and synthesis of transients - the temporal response of the network during the short time (tens of milliseconds) following the onset and offset of a control signal. We find that the network learns the particular transient characteristics of two different synthetic instruments, and furthermore shows some ability to interpolate between the characteristics of the instruments used in training in response to novel parameter settings. We also study the behaviour of the units in hidden layers of the RNN using various visualisation techniques and find a variety of volume-specific response characteristics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10703](http://arxiv.org/abs/1903.10703)

##### PDF
[http://arxiv.org/pdf/1903.10703](http://arxiv.org/pdf/1903.10703)

