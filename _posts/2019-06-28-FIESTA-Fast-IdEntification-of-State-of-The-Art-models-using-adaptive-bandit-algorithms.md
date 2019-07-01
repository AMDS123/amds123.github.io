---
layout: post
title: "FIESTA: Fast IdEntification of State-of-The-Art models using adaptive bandit algorithms"
date: 2019-06-28 14:11:13
categories: arXiv_CL
tags: arXiv_CL Sentiment
author: Henry B. Moss, Andrew Moore, David S. Leslie, Paul Rayson
mathjax: true
---

* content
{:toc}

##### Abstract
We present FIESTA, a model selection approach that significantly reduces the computational resources required to reliably identify state-of-the-art performance from large collections of candidate models. Despite being known to produce unreliable comparisons, it is still common practice to compare model evaluations based on single choices of random seeds. We show that reliable model selection also requires evaluations based on multiple train-test splits (contrary to common practice in many shared tasks). Using bandit theory from the statistics literature, we are able to adaptively determine appropriate numbers of data splits and random seeds used to evaluate each model, focusing computational resources on the evaluation of promising models whilst avoiding wasting evaluations on models with lower performance. Furthermore, our user-friendly Python implementation produces confidence guarantees of correctly selecting the optimal model. We evaluate our algorithms by selecting between 8 target-dependent sentiment analysis methods using dramatically fewer model evaluations than current model selection approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.12230](http://arxiv.org/abs/1906.12230)

##### PDF
[http://arxiv.org/pdf/1906.12230](http://arxiv.org/pdf/1906.12230)

