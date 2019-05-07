---
layout: post
title: "Many Paths to Equilibrium: GANs Do Not Need to Decrease a Divergence At Every Step"
date: 2018-02-20 22:10:33
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: William Fedus, Mihaela Rosca, Balaji Lakshminarayanan, Andrew M. Dai, Shakir Mohamed, Ian Goodfellow
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) are a family of generative models that do not minimize a single training criterion. Unlike other generative models, the data distribution is learned via a game between a generator (the generative model) and a discriminator (a teacher providing training signal) that each minimize their own cost. GANs are designed to reach a Nash equilibrium at which each player cannot reduce their cost without changing the other players' parameters. One useful approach for the theory of GANs is to show that a divergence between the training distribution and the model distribution obtains its minimum value at equilibrium. Several recent research directions have been motivated by the idea that this divergence is the primary guide for the learning process and that every step of learning should decrease the divergence. We show that this view is overly restrictive. During GAN training, the discriminator provides learning signal in situations where the gradients of the divergences between distributions would not be useful. We provide empirical counterexamples to the view of GAN training as divergence minimization. Specifically, we demonstrate that GANs are able to learn distributions in situations where the divergence minimization point of view predicts they would fail. We also show that gradient penalties motivated from the divergence minimization perspective are equally helpful when applied in other contexts in which the divergence minimization perspective does not predict they would be helpful. This contributes to a growing body of evidence that GAN training may be more usefully viewed as approaching Nash equilibria via trajectories that do not necessarily minimize a specific divergence at each step.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1710.08446](https://arxiv.org/abs/1710.08446)

##### PDF
[https://arxiv.org/pdf/1710.08446](https://arxiv.org/pdf/1710.08446)

