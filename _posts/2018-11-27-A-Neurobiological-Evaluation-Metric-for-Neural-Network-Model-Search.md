---
layout: post
title: "A Neurobiological Evaluation Metric for Neural Network Model Search"
date: 2018-11-27 00:51:03
categories: arXiv_CV
tags: arXiv_CV Prediction Relation
author: Nathaniel Blanchard, Jeffery Kinnison, Brandon RichardWebster, Pouya Bashivan, Walter J. Scheirer
mathjax: true
---

* content
{:toc}

##### Abstract
Neuroscience theory posits that the brain's visual system coarsely identifies broad object categories via neural activation patterns, with similar objects producing similar neural responses. Artificial neural networks also have internal activation behavior in response to stimuli. We hypothesize that networks exhibiting brain-like activation behavior will demonstrate brain-like characteristics, e.g., stronger generalization capabilities. In this paper we introduce a human-model similarity (HMS) metric, which quantifies the similarity of human fMRI and network activation behavior. To calculate HMS, representational dissimilarity matrices (RDMs) are created as abstractions of activation behavior, measured by the correlations of activations to stimulus pairs. HMS is then the correlation between the fMRI RDM and the neural network RDM across all stimulus pairs. We test the metric on unsupervised predictive coding networks, which specifically model visual perception, and assess the metric for statistical significance over a large range of hyperparameters. Our experiments show that networks with increased human-model similarity are correlated with better performance on two computer vision tasks: next frame prediction and object matching accuracy. Further, HMS identifies networks with high performance on both tasks. An unexpected secondary finding is that the metric can be employed during training as an early-stopping mechanism.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.10726](http://arxiv.org/abs/1805.10726)

##### PDF
[http://arxiv.org/pdf/1805.10726](http://arxiv.org/pdf/1805.10726)

