---
layout: post
title: "Cautious Deep Learning"
date: 2019-02-27 19:27:58
categories: arXiv_AI
tags: arXiv_AI Adversarial CNN Deep_Learning Prediction
author: Yotam Hechtlinger, Barnab&#xe1;s P&#xf3;czos, Larry Wasserman
mathjax: true
---

* content
{:toc}

##### Abstract
Most classifiers operate by selecting the maximum of an estimate of the conditional distribution $p(y|x)$ where $x$ stands for the features of the instance to be classified and $y$ denotes its label. This often results in a {\em hubristic bias}: overconfidence in the assignment of a definite label. Usually, the observations are concentrated on a small volume but the classifier provides definite predictions for the entire space. We propose constructing conformal prediction sets which contain a set of labels rather than a single label. These conformal prediction sets contain the true label with probability $1-\alpha$. Our construction is based on $p(x|y)$ rather than $p(y|x)$ which results in a classifier that is very cautious: it outputs the null set --- meaning "I don't know" --- when the object does not resemble the training examples. An important property of our approach is that adversarial attacks are likely to be predicted as the null set or would also include the true label. We demonstrate the performance on the ImageNet ILSVRC dataset and the CelebA and IMDB-Wiki facial datasets using high dimensional features obtained from state of the art convolutional neural networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.09460](http://arxiv.org/abs/1805.09460)

##### PDF
[http://arxiv.org/pdf/1805.09460](http://arxiv.org/pdf/1805.09460)

