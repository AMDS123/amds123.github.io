---
layout: post
title: "Hybrid system identification using switching density networks"
date: 2019-07-09 18:31:51
categories: arXiv_CV
tags: arXiv_CV Classification
author: Michael Burke, Yordan Hristov, Subramanian Ramamoorthy
mathjax: true
---

* content
{:toc}

##### Abstract
Behaviour cloning is a commonly used strategy for imitation learning and can be extremely effective in constrained domains. However, in cases where the dynamics of an environment may be state dependent and varying, behaviour cloning places a burden on model capacity and the number of demonstrations required. This paper introduces switching density networks, which rely on a categorical reparametrisation for hybrid system identification. This results in a network comprising a classification layer that is followed by a regression layer. We use switching density networks to predict the parameters of hybrid control laws, which are toggled by a switching layer to produce different controller outputs, when conditioned on an input state. This work shows how switching density networks can be used for hybrid system identification in a variety of tasks, successfully identifying the key joint angle goals that make up manipulation tasks, while simultaneously learning image-based goal classifiers and regression networks that predict joint angles from images. We also show that they can cluster the phase space of an inverted pendulum, identifying the balance, spin and pump controllers required to solve this task. Switching density networks can be difficult to train, but we introduce a cross entropy regularisation loss that stabilises training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04360](http://arxiv.org/abs/1907.04360)

##### PDF
[http://arxiv.org/pdf/1907.04360](http://arxiv.org/pdf/1907.04360)

