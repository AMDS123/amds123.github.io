---
layout: post
title: "Self-supervisory Signals for Object Discovery and Detection"
date: 2018-06-08 22:50:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Face Embedding Detection
author: Etienne Pot, Alexander Toshev, Jana Kosecka
mathjax: true
---

* content
{:toc}

##### Abstract
In robotic applications, we often face the challenge of discovering new objects while having very little or no labelled training data. In this paper we explore the use of self-supervision provided by a robot traversing an environment to learn representations of encountered objects. Knowledge of ego-motion and depth perception enables the agent to effectively associate multiple object proposals, which serve as training data for learning object representations from unlabelled images. We demonstrate the utility of this representation in two ways. First, we can automatically discover objects by performing clustering in the learned embedding space. Each resulting cluster contains examples of one instance seen from various viewpoints and scales. Second, given a small number of labeled images, we can efficiently learn detectors for these labels. In the few-shot regime, these detectors have a substantially higher mAP of 0.22 compared to 0.12 of off-the-shelf standard detectors trained on this limited data. Thus, the proposed self-supervision results in effective environment specific object discovery and detection at no or very small human labeling cost.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.03370](https://arxiv.org/abs/1806.03370)

##### PDF
[https://arxiv.org/pdf/1806.03370](https://arxiv.org/pdf/1806.03370)

