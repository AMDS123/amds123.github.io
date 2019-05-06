---
layout: post
title: "Transfer Learning to Learn with Multitask Neural Model Search"
date: 2017-10-30 05:32:50
categories: arXiv_CV
tags: arXiv_CV Knowledge NAS Reinforcement_Learning Transfer_Learning Optimization Deep_Learning
author: Catherine Wong, Andrea Gesmundo
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models require extensive architecture design exploration and hyperparameter optimization to perform well on a given task. The exploration of the model design space is often made by a human expert, and optimized using a combination of grid search and search heuristics over a large space of possible choices. Neural Architecture Search (NAS) is a Reinforcement Learning approach that has been proposed to automate architecture design. NAS has been successfully applied to generate Neural Networks that rival the best human-designed architectures. However, NAS requires sampling, constructing, and training hundreds to thousands of models to achieve well-performing architectures. This procedure needs to be executed from scratch for each new task. The application of NAS to a wide set of tasks currently lacks a way to transfer generalizable knowledge across tasks. In this paper, we present the Multitask Neural Model Search (MNMS) controller. Our goal is to learn a generalizable framework that can condition model construction on successful model searches for previously seen tasks, thus significantly speeding up the search for new tasks. We demonstrate that MNMS can conduct an automated architecture search for multiple tasks simultaneously while still learning well-performing, specialized models for each task. We then show that pre-trained MNMS controllers can transfer learning to new tasks. By leveraging knowledge from previous searches, we find that pre-trained MNMS models start from a better location in the search space and reduce search time on unseen tasks, while still discovering models that outperform published human-designed models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1710.10776](https://arxiv.org/abs/1710.10776)

##### PDF
[https://arxiv.org/pdf/1710.10776](https://arxiv.org/pdf/1710.10776)

