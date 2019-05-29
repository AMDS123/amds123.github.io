---
layout: post
title: "Particle Filter Networks with Application to Visual Localization"
date: 2018-10-25 17:23:11
categories: arXiv_AI
tags: arXiv_AI Tracking Object_Tracking
author: Peter Karkus, David Hsu, Wee Sun Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Particle filtering is a powerful approach to sequential state estimation and finds application in many domains, including robot localization, object tracking, etc. To apply particle filtering in practice, a critical challenge is to construct probabilistic system models, especially for systems with complex dynamics or rich sensory inputs such as camera images. This paper introduces the Particle Filter Network (PFnet), which encodes both a system model and a particle filter algorithm in a single neural network. The PF-net is fully differentiable and trained end-to-end from data. Instead of learning a generic system model, it learns a model optimized for the particle filter algorithm. We apply the PF-net to a visual localization task, in which a robot must localize in a rich 3-D world, using only a schematic 2-D floor map. In simulation experiments, PF-net consistently outperforms alternative learning architectures, as well as a traditional model-based method, under a variety of sensor inputs. Further, PF-net generalizes well to new, unseen environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.08975](http://arxiv.org/abs/1805.08975)

##### PDF
[http://arxiv.org/pdf/1805.08975](http://arxiv.org/pdf/1805.08975)

