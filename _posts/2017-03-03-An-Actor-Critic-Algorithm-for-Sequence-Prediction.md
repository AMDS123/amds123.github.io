---
layout: post
title: "An Actor-Critic Algorithm for Sequence Prediction"
date: 2017-03-03 15:43:52
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Caption Prediction
author: Dzmitry Bahdanau, Philemon Brakel, Kelvin Xu, Anirudh Goyal, Ryan Lowe, Joelle Pineau, Aaron Courville, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach to training neural networks to generate sequences using actor-critic methods from reinforcement learning (RL). Current log-likelihood training methods are limited by the discrepancy between their training and testing modes, as models must generate tokens conditioned on their previous guesses rather than the ground-truth tokens. We address this problem by introducing a \textit{critic} network that is trained to predict the value of an output token, given the policy of an \textit{actor} network. This results in a training procedure that is much closer to the test phase, and allows us to directly optimize for a task-specific score such as BLEU. Crucially, since we leverage these techniques in the supervised learning setting rather than the traditional RL setting, we condition the critic network on the ground-truth output. We show that our method leads to improved performance on both a synthetic task, and for German-English machine translation. Our analysis paves the way for such methods to be applied in natural language generation tasks, such as machine translation, caption generation, and dialogue modelling.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1607.07086](https://arxiv.org/abs/1607.07086)

##### PDF
[https://arxiv.org/pdf/1607.07086](https://arxiv.org/pdf/1607.07086)

