---
layout: post
title: "Semi-supervised Transfer Learning for Image Rain Removal"
date: 2019-04-12 04:30:54
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Deep_Learning
author: Wei Wei, Deyu Meng, Qian Zhao, Zongben Xu, Ying Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Single image rain removal is a typical inverse problem in computer vision. The deep learning technique has been verified to be effective for this task and achieved state-of-the-art performance. However, previous deep learning methods need to pre-collect a large set of image pairs with/without synthesized rain for training, which tends to make the neural network be biased toward learning the specific patterns of the synthesized rain, while be less able to generalize to real test samples whose rain types differ from those in the training data. To this issue, this paper firstly proposes a semi-supervised learning paradigm toward this task. Different from traditional deep learning methods which only use supervised image pairs with/without synthesized rain, we further put real rainy images, without need of their clean ones, into the network training process. This is realized by elaborately formulating the residual between an input rainy image and its expected network output (clear image without rain) as a specific parametrized rain streaks distribution. The network is therefore trained to adapt real unsupervised diverse rain types through transferring from the supervised synthesized rain, and thus both the short-of-training-sample and bias-to-supervised-sample issues can be evidently alleviated. Experiments on synthetic and real data verify the superiority of our model compared to the state-of-the-arts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.11078](http://arxiv.org/abs/1807.11078)

##### PDF
[http://arxiv.org/pdf/1807.11078](http://arxiv.org/pdf/1807.11078)

