---
layout: post
title: "CHiVE: Varying Prosody in Speech Synthesis with a Linguistically Driven Dynamic Hierarchical Conditional Variational Network"
date: 2019-05-17 11:03:58
categories: arXiv_CL
tags: arXiv_CL Embedding Inference
author: Vincent Wan, Chun-an Chan, Tom Kenter, Jakub Vit, Rob Clark
mathjax: true
---

* content
{:toc}

##### Abstract
The prosodic aspects of speech signals produced by current text-to-speech systems are typically averaged over training material, and as such lack the variety and liveliness found in natural speech. To avoid monotony and averaged prosody contours, it is desirable to have a way of modeling the variation in the prosodic aspects of speech, so audio signals can be synthesized in multiple ways for a given text. We present a new, hierarchically structured conditional variational autoencoder to generate prosodic features (fundamental frequency, energy and duration) suitable for use with a vocoder or a generative model like WaveNet. At inference time, an embedding representing the prosody of a sentence may be sampled from the variational layer to allow for prosodic variation. To efficiently capture the hierarchical nature of the linguistic input (words, syllables and phones), both the encoder and decoder parts of the auto-encoder are hierarchical, in line with the linguistic structure, with layers being clocked dynamically at the respective rates. We show in our experiments that our dynamic hierarchical network outperforms a non-hierarchical state-of-the-art baseline, and, additionally, that prosody transfer across sentences is possible by employing the prosody embedding of one sentence to generate the speech signal of another.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07195](http://arxiv.org/abs/1905.07195)

##### PDF
[http://arxiv.org/pdf/1905.07195](http://arxiv.org/pdf/1905.07195)

