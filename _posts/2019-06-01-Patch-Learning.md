---
layout: post
title: "Patch Learning"
date: 2019-06-01 06:11:06
categories: arXiv_AI
tags: arXiv_AI Knowledge Prediction
author: Dongrui Wu, Jerry M. Mendel
mathjax: true
---

* content
{:toc}

##### Abstract
There have been different strategies to improve the performance of a machine learning model, e.g., increasing the depth, width, and/or nonlinearity of the model, and using ensemble learning to aggregate multiple base/weak learners in parallel or in series. This paper proposes a novel strategy called patch learning (PL) for this problem. It consists of three steps: 1) train an initial global model using all training data; 2) identify from the initial global model the patches which contribute the most to the learning error, and train a (local) patch model for each such patch; and, 3) update the global model using training data that do not fall into any patch. To use a PL model, we first determine if the input falls into any patch. If yes, then the corresponding patch model is used to compute the output. Otherwise, the global model is used. We explain in detail how PL can be implemented using fuzzy systems. Five regression problems on 1D/2D/3D curve fitting, nonlinear system identification, and chaotic time-series prediction, verified its effectiveness. To our knowledge, the PL idea has not appeared in the literature before, and it opens up a promising new line of research in machine learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00158](http://arxiv.org/abs/1906.00158)

##### PDF
[http://arxiv.org/pdf/1906.00158](http://arxiv.org/pdf/1906.00158)

