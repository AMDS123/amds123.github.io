---
layout: post
title: "From explanation to synthesis: Compositional program induction for learning from demonstration"
date: 2019-02-27 17:43:30
categories: arXiv_CV
tags: arXiv_CV Inference
author: Michael Burke, Svetlin Penkov, Subramanian Ramamoorthy
mathjax: true
---

* content
{:toc}

##### Abstract
Hybrid systems are a compact and natural mechanism with which to address problems in robotics. This work introduces an approach to learning hybrid systems from demonstrations, with an emphasis on extracting models that are explicitly verifiable and easily interpreted by robot operators. We fit a sequence of controllers using sequential importance sampling under a generative switching proportional controller task model. Here, we parameterise controllers using a proportional gain and a visually verifiable joint angle goal. Inference under this model is challenging, but we address this by introducing an attribution prior extracted from a neural end-to-end visuomotor control model. Given the sequence of controllers comprising a task, we simplify the trace using grammar parsing strategies, taking advantage of the sequence compositionality, before grounding the controllers by training perception networks to predict goals given images. Using this approach, we are successfully able to induce a program for a visuomotor reaching task involving loops and conditionals from a single demonstration and a neural end-to-end model. In addition, we are able to discover the program used for a tower building task. We argue that computer program-like control systems are more interpretable than alternative end-to-end learning approaches, and that hybrid systems inherently allow for better generalisation across task configurations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10657](http://arxiv.org/abs/1902.10657)

##### PDF
[http://arxiv.org/pdf/1902.10657](http://arxiv.org/pdf/1902.10657)

