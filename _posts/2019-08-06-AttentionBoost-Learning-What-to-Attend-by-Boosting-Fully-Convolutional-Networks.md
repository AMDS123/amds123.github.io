---
layout: post
title: "AttentionBoost: Learning What to Attend by Boosting Fully Convolutional Networks"
date: 2019-08-06 12:06:12
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Prediction
author: Gozde Nur Gunesli, Cenk Sokmensuer, Cigdem Gunduz-Demir
mathjax: true
---

* content
{:toc}

##### Abstract
Dense prediction models are widely used for image segmentation. One important challenge is to sufficiently train these models to yield good generalizations for hard-to-learn pixels. A typical group of such hard-to-learn pixels are boundaries between instances. Many studies have proposed to give specific attention to learning the boundary pixels. They include designing multi-task networks with an additional task of boundary prediction and increasing the weights of boundary pixels' predictions in the loss function. Such strategies require defining what to attend beforehand and incorporating this defined attention to the learning model. However, there may exist other groups of hard-to-learn pixels and manually defining and incorporating the appropriate attention for each group may not be feasible. In order to provide a more attainable and scalable solution, this paper proposes AttentionBoost, which is a new multi-attention learning model based on adaptive boosting. AttentionBoost designs a multi-stage network and introduces a new loss adjustment mechanism for a dense prediction model to adaptively learn what to attend at each stage directly on image data without necessitating any prior definition about what to attend. This mechanism modulates the attention of each stage to correct the mistakes of previous stages, by adjusting the loss weight of each pixel prediction separately with respect to how accurate the previous stages are on this pixel. This mechanism enables AttentionBoost to learn different attentions for different pixels at the same stage, according to difficulty of learning these pixels, as well as multiple attentions for the same pixel at different stages, according to confidence of these stages on their predictions for this pixel. Using gland segmentation as a showcase application, our experiments demonstrate that AttentionBoost improves the results of its counterparts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02095](http://arxiv.org/abs/1908.02095)

##### PDF
[http://arxiv.org/pdf/1908.02095](http://arxiv.org/pdf/1908.02095)

