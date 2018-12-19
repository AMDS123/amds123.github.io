---
layout: post
title: "BandNet: A Neural Network-based, Multi-Instrument Beatles-Style MIDI Music Composition Machine"
date: 2018-12-18 01:26:13
categories: arXiv_AI
tags: arXiv_AI Knowledge RNN Prediction
author: Yichao Zhou, Wei Chu, Sam Young, Xin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a recurrent neural network (RNN)-based MIDI music composition machine that is able to learn musical knowledge from existing Beatles' songs and generate music in the style of the Beatles with little human intervention. In the learning stage, a sequence of stylistically uniform, multiple-channel music samples was modeled by a RNN. In the composition stage, a short clip of randomly-generated music was used as a seed for the RNN to start music score prediction. To form structured music, segments of generated music from different seeds were concatenated together. To improve the quality and structure of the generated music, we integrated music theory knowledge into the model, such as controlling the spacing of gaps in the vocal melody, normalizing the timing of chord changes, and requiring notes to be related to the song's key (C major, for example). This integration improved the quality of the generated music as verified by a professional composer. We also conducted a subjective listening test that showed our generated music was close to original music by the Beatles in terms of style similarity, professional quality, and interestingness. Generated music samples are at https://goo.gl/uaLXoB.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07126](http://arxiv.org/abs/1812.07126)

##### PDF
[http://arxiv.org/pdf/1812.07126](http://arxiv.org/pdf/1812.07126)

