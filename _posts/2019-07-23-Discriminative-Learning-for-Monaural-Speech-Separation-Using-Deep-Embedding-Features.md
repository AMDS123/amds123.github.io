---
layout: post
title: "Discriminative Learning for Monaural Speech Separation Using Deep Embedding Features"
date: 2019-07-23 14:00:06
categories: arXiv_SD
tags: arXiv_SD Embedding
author: Cunhang Fan, Bin Liu, Jianhua Tao, Jiangyan Yi, Zhengqi Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep clustering (DC) and utterance-level permutation invariant training (uPIT) have been demonstrated promising for speaker-independent speech separation. DC is usually formulated as two-step processes: embedding learning and embedding clustering, which results in complex separation pipelines and a huge obstacle in directly optimizing the actual separation objectives. As for uPIT, it only minimizes the chosen permutation with the lowest mean square error, doesn't discriminate it with other permutations. In this paper, we propose a discriminative learning method for speaker-independent speech separation using deep embedding features. Firstly, a DC network is trained to extract deep embedding features, which contain each source's information and have an advantage in discriminating each target speakers. Then these features are used as the input for uPIT to directly separate the different sources. Finally, uPIT and DC are jointly trained, which directly optimizes the actual separation objectives. Moreover, in order to maximize the distance of each permutation, the discriminative learning is applied to fine tuning the whole model. Our experiments are conducted on WSJ0-2mix dataset. Experimental results show that the proposed models achieve better performances than DC and uPIT for speaker-independent speech separation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09884](http://arxiv.org/abs/1907.09884)

##### PDF
[http://arxiv.org/pdf/1907.09884](http://arxiv.org/pdf/1907.09884)

