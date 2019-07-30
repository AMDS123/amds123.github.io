---
layout: post
title: "Self-Supervised Learning for Stereo Reconstruction on Aerial Images"
date: 2019-07-29 14:10:26
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Patrick Kn&#xf6;belreiter, Christoph Vogel, Thomas Pock
mathjax: true
---

* content
{:toc}

##### Abstract
Recent developments established deep learning as an inevitable tool to boost the performance of dense matching and stereo estimation. On the downside, learning these networks requires a substantial amount of training data to be successful. Consequently, the application of these models outside of the laboratory is far from straight forward. In this work we propose a self-supervised training procedure that allows us to adapt our network to the specific (imaging) characteristics of the dataset at hand, without the requirement of external ground truth data. We instead generate interim training data by running our intermediate network on the whole dataset, followed by conservative outlier filtering. Bootstrapped from a pre-trained version of our hybrid CNN-CRF model, we alternate the generation of training data and network training. With this simple concept we are able to lift the completeness and accuracy of the pre-trained version significantly. We also show that our final model compares favorably to other popular stereo estimation algorithms on an aerial dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12446](http://arxiv.org/abs/1907.12446)

##### PDF
[http://arxiv.org/pdf/1907.12446](http://arxiv.org/pdf/1907.12446)

