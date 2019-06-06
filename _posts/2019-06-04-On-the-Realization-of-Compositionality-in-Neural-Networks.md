---
layout: post
title: "On the Realization of Compositionality in Neural Networks"
date: 2019-06-04 07:30:48
categories: arXiv_AI
tags: arXiv_AI Attention GAN Inference
author: Joris Baan, Jana Leible, Mitja Nikolaus, David Rau, Dennis Ulmer, Tim Baumg&#xe4;rtner, Dieuwke Hupkes, Elia Bruni
mathjax: true
---

* content
{:toc}

##### Abstract
We present a detailed comparison of two types of sequence to sequence models trained to conduct a compositional task. The models are architecturally identical at inference time, but differ in the way that they are trained: our baseline model is trained with a task-success signal only, while the other model receives additional supervision on its attention mechanism (Attentive Guidance), which has shown to be an effective method for encouraging more compositional solutions (Hupkes et al.,2019). We first confirm that the models with attentive guidance indeed infer more compositional solutions than the baseline, by training them on the lookup table task presented by Li\v{s}ka et al. (2019). We then do an in-depth analysis of the structural differences between the two model types, focusing in particular on the organisation of the parameter space and the hidden layer activations and find noticeable differences in both these aspects. Guided networks focus more on the components of the input rather than the sequence as a whole and develop small functional groups of neurons with specific purposes that use their gates more selectively. Results from parameter heat maps, component swapping and graph analysis also indicate that guided networks exhibit a more modular structure with a small number of specialized, strongly connected neurons.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01634](http://arxiv.org/abs/1906.01634)

##### PDF
[http://arxiv.org/pdf/1906.01634](http://arxiv.org/pdf/1906.01634)

