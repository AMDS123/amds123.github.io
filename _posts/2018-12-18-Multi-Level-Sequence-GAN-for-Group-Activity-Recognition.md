---
layout: post
title: "Multi-Level Sequence GAN for Group Activity Recognition"
date: 2018-12-18 01:21:36
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN RNN Classification Prediction Relation Recognition
author: Harshala Gammulle, Simon Denman, Sridha Sridharan, Clinton Fookes
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel semi-supervised, Multi-Level Sequential Generative Adversarial Network (MLS-GAN) architecture for group activity recognition. In contrast to previous works which utilise manually annotated individual human action predictions, we allow the models to learn it's own internal representations to discover pertinent sub-activities that aid the final group activity recognition task. The generator is fed with person-level and scene-level features that are mapped temporally through LSTM networks. Action-based feature fusion is performed through novel gated fusion units that are able to consider long-term dependencies, exploring the relationships among all individual actions, to learn an intermediate representation or `action code' for the current group activity. The network achieves its semi-supervised behaviour by allowing it to perform group action classification together with the adversarial real/fake validation. We perform extensive evaluations on different architectural variants to demonstrate the importance of the proposed architecture. Furthermore, we show that utilising both person-level and scene-level features facilitates the group activity prediction better than using only person-level features. Our proposed architecture outperforms current state-of-the-art results for sports and pedestrian based classification tasks on Volleyball and Collective Activity datasets, showing it's flexible nature for effective learning of group activities.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07124](http://arxiv.org/abs/1812.07124)

##### PDF
[http://arxiv.org/pdf/1812.07124](http://arxiv.org/pdf/1812.07124)

