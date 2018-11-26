---
layout: post
title: "AutoSense Model for Word Sense Induction"
date: 2018-11-22 17:19:31
categories: arXiv_CL
tags: arXiv_CL Detection
author: Reinald Kim Amplayo, Seung-won Hwang, Min Song
mathjax: true
---

* content
{:toc}

##### Abstract
Word sense induction (WSI), or the task of automatically discovering multiple senses or meanings of a word, has three main challenges: domain adaptability, novel sense detection, and sense granularity flexibility. While current latent variable models are known to solve the first two challenges, they are not flexible to different word sense granularities, which differ very much among words, from aardvark with one sense, to play with over 50 senses. Current models either require hyperparameter tuning or nonparametric induction of the number of senses, which we find both to be ineffective. Thus, we aim to eliminate these requirements and solve the sense granularity problem by proposing AutoSense, a latent variable model based on two observations: (1) senses are represented as a distribution over topics, and (2) senses generate pairings between the target word and its neighboring word. These observations alleviate the problem by (a) throwing garbage senses and (b) additionally inducing fine-grained word senses. Results show great improvements over the state-of-the-art models on popular WSI datasets. We also show that AutoSense is able to learn the appropriate sense granularity of a word. Finally, we apply AutoSense to the unsupervised author name disambiguation task where the sense granularity problem is more evident and show that AutoSense is evidently better than competing models. We share our data and code here: https://github.com/rktamplayo/AutoSense.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09242](http://arxiv.org/abs/1811.09242)

##### PDF
[http://arxiv.org/pdf/1811.09242](http://arxiv.org/pdf/1811.09242)

