---
layout: post
title: "Massively Parallel Hyperparameter Tuning"
date: 2019-01-23 02:15:22
categories: arXiv_CV
tags: arXiv_CV RNN
author: Liam Li, Kevin Jamieson, Afshin Rostamizadeh, Ekaterina Gonina, Moritz Hardt, Benjamin Recht, Ameet Talwalkar
mathjax: true
---

* content
{:toc}

##### Abstract
Modern learning models are characterized by large hyperparameter spaces. In order to adequately explore these large spaces, we must evaluate a large number of configurations, typically orders of magnitude more configurations than available parallel workers. Given the growing costs of model training, we would ideally like to perform this search in roughly the same wall-clock time needed to train a single model. In this work, we tackle this challenge by introducing ASHA, a simple and robust hyperparameter tuning algorithm with solid theoretical underpinnings that exploits parallelism and aggressive early-stopping. Our extensive empirical results show that ASHA outperforms state-of-the hyperparameter tuning methods; scales linearly with the number of workers in distributed settings; converges to a high quality configuration in half the time taken by Vizier (Google's internal hyperparameter tuning service) in an experiment with 500 workers; and beats the published result for a near state-of-the-art LSTM architecture in under 2x the time to train a single model.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05934](https://arxiv.org/abs/1810.05934)

##### PDF
[https://arxiv.org/pdf/1810.05934](https://arxiv.org/pdf/1810.05934)

