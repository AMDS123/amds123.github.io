---
layout: post
title: "Detecting the Starting Frame of Actions in Video"
date: 2019-06-07 21:48:09
categories: arXiv_CV
tags: arXiv_CV RNN Prediction Detection Relation
author: Iljung S. Kwak, David Kriegman, Kristin Branson
mathjax: true
---

* content
{:toc}

##### Abstract
To understand causal relationships between events in the world, it is useful to pinpoint when actions occur in videos and to examine the state of the world at and around that time point. For example, one must accurately detect the start of an audience response -- laughter in a movie, cheering at a sporting event -- to understand the cause of the reaction. In this work, we focus on the problem of accurately detecting action starts rather than isolated events or action ends. We introduce a novel structured loss function based on matching predictions to true action starts that is tailored to this problem; it more heavily penalizes extra and missed action start detections over small misalignments. Recurrent neural networks are used to minimize a differentiable approximation of this loss. To evaluate these methods, we introduce the Mouse Reach Dataset, a large, annotated video dataset of mice performing a sequence of actions. The dataset was labeled by experts for the purpose of neuroscience research on causally relating neural activity to behavior. On this dataset, we demonstrate that the structured loss leads to significantly higher accuracy than a baseline of mean-squared error loss.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03340](http://arxiv.org/abs/1906.03340)

##### PDF
[http://arxiv.org/pdf/1906.03340](http://arxiv.org/pdf/1906.03340)

