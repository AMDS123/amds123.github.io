---
layout: post
title: "Context-Dependent Semantic Parsing over Temporally Structured Data"
date: 2019-05-01 10:16:46
categories: arXiv_CL
tags: arXiv_CL Attention Face RNN
author: Charles Chen, Razvan Bunescu
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a new semantic parsing setting that allows users to query the system using both natural language questions and actions within a graphical user interface. Multiple time series belonging to an entity of interest are stored in a database and the user interacts with the system to obtain a better understanding of the entity's state and behavior, entailing sequences of actions and questions whose answers may depend on previous factual or navigational interactions. We design an LSTM-based encoder-decoder architecture that models context dependency through copying mechanisms and multiple levels of attention over inputs and previous outputs. When trained to predict tokens using supervised learning, the proposed architecture substantially outperforms standard sequence generation baselines. Training the architecture using policy gradient leads to further improvements in performance, reaching a sequence-level accuracy of 88.7% on artificial data and 74.8% on real data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00245](http://arxiv.org/abs/1905.00245)

##### PDF
[http://arxiv.org/pdf/1905.00245](http://arxiv.org/pdf/1905.00245)

