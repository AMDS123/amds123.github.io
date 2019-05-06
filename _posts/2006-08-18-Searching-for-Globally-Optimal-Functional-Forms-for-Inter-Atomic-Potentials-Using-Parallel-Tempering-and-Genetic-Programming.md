---
layout: post
title: "Searching for Globally Optimal Functional Forms for Inter-Atomic Potentials Using Parallel Tempering and Genetic Programming"
date: 2006-08-18 23:17:32
categories: arXiv_CV
tags: arXiv_CV Optimization
author: A. Slepoy, A. P. Thompson, M. D. Peters
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a Genetic Programming-based methodology that enables discovery of novel functional forms for classical inter-atomic force-fields, used in molecular dynamics simulations. Unlike previous efforts in the field, that fit only the parameters to the fixed functional forms, we instead use a novel algorithm to search the space of many possible functional forms. While a follow-on practical procedure will use experimental and {\it ab inito} data to find an optimal functional form for a forcefield, we first validate the approach using a manufactured solution. This validation has the advantage of a well-defined metric of success. We manufactured a training set of atomic coordinate data with an associated set of global energies using the well-known Lennard-Jones inter-atomic potential. We performed an automatic functional form fitting procedure starting with a population of random functions, using a genetic programming functional formulation, and a parallel tempering Metropolis-based optimization algorithm. Our massively-parallel method independently discovered the Lennard-Jones function after searching for several hours on 100 processors and covering a miniscule portion of the configuration space. We find that the method is suitable for unsupervised discovery of functional forms for inter-atomic potentials/force-fields. We also find that our parallel tempering Metropolis-based approach significantly improves the optimization convergence time, and takes good advantage of the parallel cluster architecture.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/cs/0608078](https://arxiv.org/abs/cs/0608078)

##### PDF
[https://arxiv.org/pdf/cs/0608078](https://arxiv.org/pdf/cs/0608078)

