---
layout: post
title: "Conversational Networks for Automatic Online Moderation"
date: 2019-01-31 09:23:57
categories: arXiv_CL
tags: arXiv_CL Detection
author: Etienne Papegnies (LIA), Vincent Labatut (LIA), Richard Dufour (LIA), Georges Linares (LIA)
mathjax: true
---

* content
{:toc}

##### Abstract
Moderation of user-generated content in an online community is a challenge that has great socio-economical ramifications. However, the costs incurred by delegating this work to human agents are high. For this reason, an automatic system able to detect abuse in user-generated content is of great interest. There are a number of ways to tackle this problem, but the most commonly seen in practice are word filtering or regular expression matching. The main limitations are their vulnerability to intentional obfuscation on the part of the users, and their context-insensitive nature. Moreover, they are language-dependent and may require appropriate corpora for training. In this paper, we propose a system for automatic abuse detection that completely disregards message content. We first extract a conversational network from raw chat logs and characterize it through topological measures. We then use these as features to train a classifier on our abuse detection task. We thoroughly assess our system on a dataset of user comments originating from a French Massively Multiplayer Online Game. We identify the most appropriate network extraction parameters and discuss the discriminative power of our features, relatively to their topological and temporal nature. Our method reaches an F-measure of 83.89 when using the full feature set, improving on existing approaches. With a selection of the most discriminative features, we dramatically cut computing time while retaining most of the performance (82.65).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11281](http://arxiv.org/abs/1901.11281)

##### PDF
[http://arxiv.org/pdf/1901.11281](http://arxiv.org/pdf/1901.11281)

