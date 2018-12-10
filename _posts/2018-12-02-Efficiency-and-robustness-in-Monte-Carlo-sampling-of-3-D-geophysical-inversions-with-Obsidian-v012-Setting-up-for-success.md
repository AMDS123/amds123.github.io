---
layout: post
title: "Efficiency and robustness in Monte Carlo sampling of 3-D geophysical inversions with Obsidian v0.1.2: Setting up for success"
date: 2018-12-02 03:58:33
categories: arXiv_AI
tags: arXiv_AI Face
author: Richard Scalzo, David Kohn, Hugo Olierook, Gregory Houseman, Rohitash Chandra, Mark Girolami, Sally Cripps
mathjax: true
---

* content
{:toc}

##### Abstract
The rigorous quantification of uncertainty in geophysical inversions is a challenging problem. Inversions are often ill-posed and the likelihood surface may be multi-modal; properties of any single mode become inadequate uncertainty measures, and sampling methods become inefficient for irregular posteriors or high-dimensional parameter spaces. We explore the influences of different choices made by the practitioner on the efficiency and accuracy of Bayesian geophysical inversion methods that rely on Markov chain Monte Carlo sampling to assess uncertainty, using a multi-sensor inversion of the three-dimensional structure and composition of a region in the Cooper Basin of South Australia as a case study. The inversion is performed using an updated version of the Obsidian distributed inversion software. We find that the posterior for this inversion has complex local covariance structure, hindering the efficiency of adaptive sampling methods that adjust the proposal based on the chain history. Within the context of a parallel-tempered Markov chain Monte Carlo scheme for exploring high-dimensional multi-modal posteriors, a preconditioned Crank-Nicholson proposal outperforms more conventional forms of random walk. Aspects of the problem setup, such as priors on petrophysics or on 3-D geological structure, affect the shape and separation of posterior modes, influencing sampling performance as well as the inversion results. Use of uninformative priors on sensor noise can improve inversion results by enabling optimal weighting among multiple sensors even if noise levels are uncertain. Efficiency could be further increased by using posterior gradient information within proposals, which Obsidian does not currently support, but which could be emulated using posterior surrogates.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00318](http://arxiv.org/abs/1812.00318)

##### PDF
[http://arxiv.org/pdf/1812.00318](http://arxiv.org/pdf/1812.00318)

