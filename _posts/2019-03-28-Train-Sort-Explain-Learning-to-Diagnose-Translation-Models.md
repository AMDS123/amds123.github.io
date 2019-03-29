---
layout: post
title: "Train, Sort, Explain: Learning to Diagnose Translation Models"
date: 2019-03-28 14:45:42
categories: arXiv_CL
tags: arXiv_CL Adversarial Classification
author: Robert Schwarzenberg, David Harbecke, Vivien Macketanz, Eleftherios Avramidis, Sebastian M&#xf6;ller
mathjax: true
---

* content
{:toc}

##### Abstract
Evaluating translation models is a trade-off between effort and detail. On the one end of the spectrum there are automatic count-based methods such as BLEU, on the other end linguistic evaluations by humans, which arguably are more informative but also require a disproportionately high effort. To narrow the spectrum, we propose a general approach on how to automatically expose systematic differences between human and machine translations to human experts. Inspired by adversarial settings, we train a neural text classifier to distinguish human from machine translations. A classifier that performs and generalizes well after training should recognize systematic differences between the two classes, which we uncover with neural explainability methods. Our proof-of-concept implementation, DiaMaT, is open source. Applied to a dataset translated by a state-of-the-art neural Transformer model, DiaMaT achieves a classification accuracy of 75% and exposes meaningful differences between humans and the Transformer, amidst the current discussion about human parity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12017](http://arxiv.org/abs/1903.12017)

##### PDF
[http://arxiv.org/pdf/1903.12017](http://arxiv.org/pdf/1903.12017)

