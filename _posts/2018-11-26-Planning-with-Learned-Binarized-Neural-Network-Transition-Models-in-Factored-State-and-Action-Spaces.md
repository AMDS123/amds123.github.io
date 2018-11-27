---
layout: post
title: "Planning with Learned Binarized Neural Network Transition Models in Factored State and Action Spaces"
date: 2018-11-26 14:59:29
categories: arXiv_AI
tags: arXiv_AI
author: Buser Say, Scott Sanner
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we leverage the efficiency of Binarized Neural Networks (BNNs) to learn complex state transition models of planning domains with discretized factored state and action spaces. In order to directly exploit this transition structure for planning, we present two novel compilations of the learned factored planning problem with BNNs based on reductions to Weighted Partial Maximum Boolean Satisfiability (FD-SAT-Plan+) as well as Binary Linear Programming (FD-BLP-Plan+). Theoretically, we show that our SAT-based Bi-Directional Neuron Activation Encoding maintains the generalized arc-consistency property through unit propagation, which is one of the most important properties that certificate the efficiency of a SAT-based encoding. Experimentally, we validate the computational efficiency of our Bi-Directional Neuron Activation Encoding in comparison to the existing neuron activation encoding, demonstrate the effectiveness of learning complex transition models with BNNs, and test the runtime efficiency of both FD-SAT-Plan+ and FD-BLP-Plan+ on the learned factored planning problem. Finally, we present a finite-time incremental constraint generation algorithm based on generalized landmark constraints to improve the planning accuracy of our encodings.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.10433](https://arxiv.org/abs/1811.10433)

##### PDF
[https://arxiv.org/pdf/1811.10433](https://arxiv.org/pdf/1811.10433)

