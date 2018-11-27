---
layout: post
title: "Recognizing Plans by Learning Embeddings from Observed Action Distributions"
date: 2018-11-24 17:30:54
categories: arXiv_AI
tags: arXiv_AI Face Embedding Recognition
author: Yantian Zha, Yikang Li, Sriram Gopalakrishnan, Baoxin Li, Subbarao Kambhampati
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in visual activity recognition have raised the possibility of applications such as automated video surveillance. Effective approaches for such problems however require the ability to recognize the plans of agents from video information. Although traditional plan recognition algorithms depend on access to sophisticated planning domain models, one recent promising direction involves learning approximated (or shallow) domain models directly from the observed activity sequences DUP. One limitation is that such approaches expect observed action sequences as inputs. In many cases involving vision/sensing from raw data, there is considerable uncertainty about the specific action at any given time point. The most we can expect in such cases is probabilistic information about the action at that point. The input will then be sequences of such observed action distributions. In this work, we address the problem of constructing an effective data-interface that allows a plan recognition module to directly handle such observation distributions. Such an interface works like a bridge between the low-level perception module, and the high-level plan recognition module. We propose two approaches. The first involves resampling the distribution sequences to single action sequences, from which we could learn an action affinity model based on learned action (word) embeddings for plan recognition. The second is to directly learn action distribution embeddings by our proposed Distr2vec (distribution to vector) model, to construct an affinity model for plan recognition.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.01949](http://arxiv.org/abs/1712.01949)

##### PDF
[http://arxiv.org/pdf/1712.01949](http://arxiv.org/pdf/1712.01949)

