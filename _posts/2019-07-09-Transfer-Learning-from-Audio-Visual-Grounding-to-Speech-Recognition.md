---
layout: post
title: "Transfer Learning from Audio-Visual Grounding to Speech Recognition"
date: 2019-07-09 18:23:32
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition Transfer_Learning Recognition
author: Wei-Ning Hsu, David Harwath, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
Transfer learning aims to reduce the amount of data required to excel at a new task by re-using the knowledge acquired from learning other related tasks. This paper proposes a novel transfer learning scenario, which distills robust phonetic features from grounding models that are trained to tell whether a pair of image and speech are semantically correlated, without using any textual transcripts. As semantics of speech are largely determined by its lexical content, grounding models learn to preserve phonetic information while disregarding uncorrelated factors, such as speaker and channel. To study the properties of features distilled from different layers, we use them as input separately to train multiple speech recognition models. Empirical results demonstrate that layers closer to input retain more phonetic information, while following layers exhibit greater invariance to domain shift. Moreover, while most previous studies include training data for speech recognition for feature extractor training, our grounding models are not trained on any of those data, indicating more universal applicability to new domains.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04355](http://arxiv.org/abs/1907.04355)

##### PDF
[http://arxiv.org/pdf/1907.04355](http://arxiv.org/pdf/1907.04355)

