---
layout: post
title: "Scalable language model adaptation for spoken dialogue systems"
date: 2018-12-11 19:02:05
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Optimization Language_Model Recognition
author: Ankur Gandhe, Ariya Rastrow, Bjorn Hoffmeister
mathjax: true
---

* content
{:toc}

##### Abstract
Language models (LM) for interactive speech recognition systems are trained on large amounts of data and the model parameters are optimized on past user data. New application intents and interaction types are released for these systems over time, imposing challenges to adapt the LMs since the existing training data is no longer sufficient to model the future user interactions. It is unclear how to adapt LMs to new application intents without degrading the performance on existing applications. In this paper, we propose a solution to (a) estimate n-gram counts directly from the hand-written grammar for training LMs and (b) use constrained optimization to optimize the system parameters for future use cases, while not degrading the performance on past usage. We evaluated our approach on new applications intents for a personal assistant system and find that the adaptation improves the word error rate by up to 15% on new applications even when there is no adaptation data available for an application.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04647](http://arxiv.org/abs/1812.04647)

##### PDF
[http://arxiv.org/pdf/1812.04647](http://arxiv.org/pdf/1812.04647)

