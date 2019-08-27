---
layout: post
title: "Stochastic Filter Groups for Multi-Task CNNs: Learning Specialist and Generalist Convolution Kernels"
date: 2019-08-26 11:09:44
categories: arXiv_CV
tags: arXiv_CV CNN Inference Relation
author: Felix J.S. Bragman, Ryutaro Tanno, Sebastien Ourselin, Daniel C. Alexander, M. Jorge Cardoso
mathjax: true
---

* content
{:toc}

##### Abstract
The performance of multi-task learning in Convolutional Neural Networks (CNNs) hinges on the design of feature sharing between tasks within the architecture. The number of possible sharing patterns are combinatorial in the depth of the network and the number of tasks, and thus hand-crafting an architecture, purely based on the human intuitions of task relationships can be time-consuming and suboptimal. In this paper, we present a probabilistic approach to learning task-specific and shared representations in CNNs for multi-task learning. Specifically, we propose "stochastic filter groups'' (SFG), a mechanism to assign convolution kernels in each layer to "specialist'' or "generalist'' groups, which are specific to or shared across different tasks, respectively. The SFG modules determine the connectivity between layers and the structures of task-specific and shared representations in the network. We employ variational inference to learn the posterior distribution over the possible grouping of kernels and network parameters. Experiments demonstrate that the proposed method generalises across multiple tasks and shows improved performance over baseline methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09597](http://arxiv.org/abs/1908.09597)

##### PDF
[http://arxiv.org/pdf/1908.09597](http://arxiv.org/pdf/1908.09597)

