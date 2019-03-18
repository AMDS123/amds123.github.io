---
layout: post
title: "Alignment Based Matching Networks for One-Shot Classification and Open-Set Recognition"
date: 2019-03-11 02:50:27
categories: arXiv_CV
tags: arXiv_CV Attention CNN Classification Deep_Learning Recognition
author: Paresh Malalur, Tommi Jaakkola
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning for object classification relies heavily on convolutional models. While effective, CNNs are rarely interpretable after the fact. An attention mechanism can be used to highlight the area of the image that the model focuses on thus offering a narrow view into the mechanism of classification. We expand on this idea by forcing the method to explicitly align images to be classified to reference images representing the classes. The mechanism of alignment is learned and therefore does not require that the reference objects are anything like those being classified. Beyond explanation, our exemplar based cross-alignment method enables classification with only a single example per category (one-shot). Our model cuts the 5-way, 1-shot error rate in Omniglot from 2.1% to 1.4% and in MiniImageNet from 53.5% to 46.5% while simultaneously providing point-wise alignment information providing some understanding on what the network is capturing. This method of alignment also enables the recognition of an unsupported class (open-set) in the one-shot setting while maintaining an F1-score of above 0.5 for Omniglot even with 19 other distracting classes while baselines completely fail to separate the open-set class in the one-shot setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06538](http://arxiv.org/abs/1903.06538)

##### PDF
[http://arxiv.org/pdf/1903.06538](http://arxiv.org/pdf/1903.06538)

