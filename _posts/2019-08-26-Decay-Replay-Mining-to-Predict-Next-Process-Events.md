---
layout: post
title: "Decay Replay Mining to Predict Next Process Events"
date: 2019-08-26 20:54:32
categories: arXiv_AI
tags: arXiv_AI RNN Deep_Learning Prediction
author: Julian Theis, Houshang Darabi
mathjax: true
---

* content
{:toc}

##### Abstract
In complex processes, various events can happen in different sequences. The prediction of the next event given an a-priori process state is of importance in such processes. Recent methods have proposed deep learning techniques such as recurrent neural networks, developed on raw event logs, to predict the next event from a process state. However, such deep learning models by themselves lack a clear representation of the process states. At the same time, recent methods have neglected the time feature of event instances. In this paper, we take advantage of Petri nets as a powerful tool in modeling complex process behaviors considering time as an elemental variable. We propose an approach which starts from a Petri net process model constructed by a process mining algorithm. We enhance the Petri net model with time decay functions to create continuous process state samples. Finally, we use these samples in combination with discrete token movement counters and Petri net markings to train a deep learning model that predicts the next event. We demonstrate significant performance improvements and outperform the state-of-the-art methods on nine real-world benchmark event logs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05084](http://arxiv.org/abs/1903.05084)

##### PDF
[http://arxiv.org/pdf/1903.05084](http://arxiv.org/pdf/1903.05084)

