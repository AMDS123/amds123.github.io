---
layout: post
title: "Dynamic Prediction Length for Time Series with Sequence to Sequence Networks"
date: 2019-08-18 16:31:28
categories: arXiv_AI
tags: arXiv_AI Inference RNN Prediction
author: Mark Harmon, Diego Klabjan
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks and sequence to sequence models require a predetermined length for prediction output length. Our model addresses this by allowing the network to predict a variable length output in inference. A new loss function with a tailored gradient computation is developed that trades off prediction accuracy and output length. The model utilizes a function to determine whether a particular output at a time should be evaluated or not given a predetermined threshold. We evaluate the model on the problem of predicting the prices of securities. We find that the model makes longer predictions for more stable securities and it naturally balances prediction accuracy and length.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.00425](http://arxiv.org/abs/1807.00425)

##### PDF
[http://arxiv.org/pdf/1807.00425](http://arxiv.org/pdf/1807.00425)

