---
layout: post
title: "The Secret Sharer: Measuring Unintended Neural Network Memorization & Extracting Secrets"
date: 2019-03-05 18:13:03
categories: arXiv_AI
tags: arXiv_AI Quantitative
author: Nicholas Carlini, Chang Liu, Jernej Kos, &#xda;lfar Erlingsson, Dawn Song
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a testing methodology for quantitatively assessing the risk of unintended memorization of rare or unique sequences in generative sequence models---a common type of neural network. Such models are sometimes trained on sensitive data (e.g., the text of users' private messages); our methodology allows deep-learning practitioners to choose configurations that minimize memorization during training, thereby benefiting privacy. 
 In experiments, we show that unintended memorization is a persistent, hard-to-avoid issue that can have serious consequences. Specifically, if not addressed during training, we show that new, efficient procedures can allow extracting unique, secret sequences such as credit card numbers from trained models. We also show that our testing strategy is practical and easy-to-apply, e.g., by describing its use for quantitatively preventing data exposure in Smart Compose, a production, commercial neural network trained on millions of users' email messages.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.08232](http://arxiv.org/abs/1802.08232)

##### PDF
[http://arxiv.org/pdf/1802.08232](http://arxiv.org/pdf/1802.08232)

