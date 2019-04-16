---
layout: post
title: "Linear Memory Networks"
date: 2018-11-08 11:08:04
categories: arXiv_CV
tags: arXiv_CV Optimization RNN Memory_Networks
author: Davide Bacciu, Antonio Carta, Alessandro Sperduti
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks can learn complex transduction problems that require maintaining and actively exploiting a memory of their inputs. Such models traditionally consider memory and input-output functionalities indissolubly entangled. We introduce a novel recurrent architecture based on the conceptual separation between the functional input-output transformation and the memory mechanism, showing how they can be implemented through different neural components. By building on such conceptualization, we introduce the Linear Memory Network, a recurrent model comprising a feedforward neural network, realizing the non-linear functional transformation, and a linear autoencoder for sequences, implementing the memory component. The resulting architecture can be efficiently trained by building on closed-form solutions to linear optimization problems. Further, by exploiting equivalence results between feedforward and recurrent neural networks we devise a pretraining schema for the proposed architecture. Experiments on polyphonic music datasets show competitive results against gated recurrent networks and other state of the art models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.03356](https://arxiv.org/abs/1811.03356)

##### PDF
[https://arxiv.org/pdf/1811.03356](https://arxiv.org/pdf/1811.03356)

