---
layout: post
title: "The Secret Sharer: Evaluating and Testing Unintended Memorization in Neural Networks"
date: 2019-07-16 17:05:32
categories: arXiv_AI
tags: arXiv_AI Quantitative
author: Nicholas Carlini, Chang Liu, &#xda;lfar Erlingsson, Jernej Kos, Dawn Song
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a testing methodology for quantitatively assessing the risk that rare or unique training-data sequences are unintentionally memorized by generative sequence models---a common type of machine-learning model. Because such models are sometimes trained on sensitive data (e.g., the text of users' private messages), this methodology can benefit privacy by allowing deep-learning practitioners to select means of training that minimize such memorization. 
 In experiments, we show that unintended memorization is a persistent, hard-to-avoid issue that can have serious consequences. Specifically, for models trained without consideration of memorization, we describe new, efficient procedures that can extract unique, secret sequences, such as credit card numbers. We show that our testing strategy is a practical and easy-to-use first line of defense, e.g., by describing its application to quantitatively limit data exposure in Google's Smart Compose, a commercial text-completion neural network trained on millions of users' email messages.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.08232](http://arxiv.org/abs/1802.08232)

##### PDF
[http://arxiv.org/pdf/1802.08232](http://arxiv.org/pdf/1802.08232)

