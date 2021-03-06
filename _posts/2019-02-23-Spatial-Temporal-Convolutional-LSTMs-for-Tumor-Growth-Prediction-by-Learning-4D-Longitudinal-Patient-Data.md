---
layout: post
title: "Spatial-Temporal Convolutional LSTMs for Tumor Growth Prediction by Learning 4D Longitudinal Patient Data"
date: 2019-02-23 02:05:50
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN RNN Deep_Learning Prediction
author: Ling Zhang, Le Lu, Robert M. Zhu, Mohammadhadi Bagheri, Ronald M. Summers, Jianhua Yao
mathjax: true
---

* content
{:toc}

##### Abstract
Prognostic tumor growth modeling via medical imaging observations is a challenging yet important problem in precision and predictive medicine. Traditionally, this problem is tackled through mathematical modeling and evaluated using relatively small patient datasets. Recent advances of convolutional networks (ConvNets) have demonstrated their higher accuracy than mathematical models in predicting future tumor volumes. This indicates that deep learning may have great potentials on addressing such problem. The state-of-the-art work models the cell invasion and mass-effect of tumor growth by training separate ConvNets on 2D image patches. Nevertheless such a 2D modeling approach cannot make full use of the spatial-temporal imaging context of the tumor's longitudinal 4D (3D + time) patient data. Moreover, previous methods are incapable to predict clinically-relevant tumor properties, other than the tumor volumes. 
 In this paper, we exploit to formulate the tumor growth process through convolutional LSTMs (ConvLSTM) that extract tumor's static imaging appearances and simultaneously capture its temporal dynamic changes within a single network. We extend ConvLSTM into the spatial-temporal domain (ST-ConvLSTM) by jointly learning the inter-slice 3D contexts and the longitudinal dynamics. Our approach can incorporate other non-imaging patient information in an end-to-end trainable manner. Experiments are conducted on the largest 4D longitudinal tumor dataset of 33 patients to date. Results validate that the proposed ST-ConvLSTM model produces a Dice score of 83.2%+-5.1% and a RVD of 11.2%+-10.8%, both statistically significantly outperforming (p&lt;0.05) other compared methods of traditional linear model, ConvLSTM, and generative adversarial network (GAN) under the metric of predicting future tumor volumes. Last, our new method enables the prediction of both cell density and CT intensity numbers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08716](http://arxiv.org/abs/1902.08716)

##### PDF
[http://arxiv.org/pdf/1902.08716](http://arxiv.org/pdf/1902.08716)

