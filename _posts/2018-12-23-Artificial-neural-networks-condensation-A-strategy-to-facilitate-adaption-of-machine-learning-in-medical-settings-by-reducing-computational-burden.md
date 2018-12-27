---
layout: post
title: "Artificial neural networks condensation: A strategy to facilitate adaption of machine learning in medical settings by reducing computational burden"
date: 2018-12-23 05:08:24
categories: arXiv_AI
tags: arXiv_AI Sparse RNN Prediction
author: Dianbo Liu, Nestor Sepulveda, Ming Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Machine Learning (ML) applications on healthcare can have a great impact on people's lives helping deliver better and timely treatment to those in need. At the same time, medical data is usually big and sparse requiring important computational resources. Although it might not be a problem for wide-adoption of ML tools in developed nations, availability of computational resource can very well be limited in third-world nations. This can prevent the less favored people from benefiting of the advancement in ML applications for healthcare. In this project we explored methods to increase computational efficiency of ML algorithms, in particular Artificial Neural Nets (NN), while not compromising the accuracy of the predicted results. We used in-hospital mortality prediction as our case analysis based on the MIMIC III publicly available dataset. We explored three methods on two different NN architectures. We reduced the size of recurrent neural net (RNN) and dense neural net (DNN) by applying pruning of "unused" neurons. Additionally, we modified the RNN structure by adding a hidden-layer to the LSTM cell allowing to use less recurrent layers for the model. Finally, we implemented quantization on DNN forcing the weights to be 8-bits instead of 32-bits. We found that all our methods increased computational efficiency without compromising accuracy and some of them even achieved higher accuracy than the pre-condensed baseline models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09659](http://arxiv.org/abs/1812.09659)

##### PDF
[http://arxiv.org/pdf/1812.09659](http://arxiv.org/pdf/1812.09659)

