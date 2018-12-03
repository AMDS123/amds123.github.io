---
layout: post
title: "Compact and Efficient Encodings for Planning in Factored State and Action Spaces with Learned Binarized Neural Network Transition Models"
date: 2018-11-30 17:15:31
categories: arXiv_AI
tags: arXiv_AI
author: Buser Say, Scott Sanner
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we leverage the efficiency of Binarized Neural Networks (BNNs) to learn complex state transition models of planning domains with discretized factored state and action spaces. In order to directly exploit this transition structure for planning, we present two novel compilations of the learned factored planning problem with BNNs based on reductions to Weighted Partial Maximum Boolean Satisfiability (FD-SAT-Plan+) as well as Binary Linear Programming (FD-BLP-Plan+). Theoretically, we show that our SAT-based Bi-Directional Neuron Activation Encoding is asymptotically the most compact encoding in the literature and maintains the generalized arc-consistency property through unit propagation -- a property that facilitates efficiency in SAT solvers. Experimentally, we validate the computational efficiency of our Bi-Directional Neuron Activation Encoding in comparison to an existing neuron activation encoding, demonstrate the effectiveness of learning complex transition models with BNNs, and test the runtime efficiency of both FD-SAT-Plan+ and FD-BLP-Plan+ on the learned factored planning problem. Finally, we present a finite-time incremental constraint generation algorithm based on generalized landmark constraints to improve the planning accuracy of our encodings.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.10433](https://arxiv.org/abs/1811.10433)

##### PDF
[https://arxiv.org/pdf/1811.10433](https://arxiv.org/pdf/1811.10433)

