---
layout: post
title: "Visualizing and Understanding Curriculum Learning for Long Short-Term Memory Networks"
date: 2016-11-18 19:38:59
categories: arXiv_CV
tags: arXiv_CV Sentiment RNN Prediction Memory_Networks
author: Volkan Cirik, Eduard Hovy, Louis-Philippe Morency
mathjax: true
---

* content
{:toc}

##### Abstract
Curriculum Learning emphasizes the order of training instances in a computational learning setup. The core hypothesis is that simpler instances should be learned early as building blocks to learn more complex ones. Despite its usefulness, it is still unknown how exactly the internal representation of models are affected by curriculum learning. In this paper, we study the effect of curriculum learning on Long Short-Term Memory (LSTM) networks, which have shown strong competency in many Natural Language Processing (NLP) problems. Our experiments on sentiment analysis task and a synthetic task similar to sequence prediction tasks in NLP show that curriculum learning has a positive effect on the LSTM's internal states by biasing the model towards building constructive representations i.e. the internal representation at the previous timesteps are used as building blocks for the final prediction. We also find that smaller models significantly improves when they are trained with curriculum learning. Lastly, we show that curriculum learning helps more when the amount of training data is limited.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1611.06204](https://arxiv.org/abs/1611.06204)

##### PDF
[https://arxiv.org/pdf/1611.06204](https://arxiv.org/pdf/1611.06204)

