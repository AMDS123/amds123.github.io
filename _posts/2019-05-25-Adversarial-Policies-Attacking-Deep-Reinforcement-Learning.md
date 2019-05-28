---
layout: post
title: "Adversarial Policies: Attacking Deep Reinforcement Learning"
date: 2019-05-25 15:23:19
categories: arXiv_AI
tags: arXiv_AI Adversarial Reinforcement_Learning
author: Adam Gleave, Michael Dennis, Neel Kant, Cody Wild, Sergey Levine, Stuart Russell
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning (RL) policies are known to be vulnerable to adversarial perturbations to their observations, similar to adversarial examples for classifiers. However, an attacker is not usually able to directly modify another agent's observations. This might lead one to wonder: is it possible to attack an RL agent simply by choosing an adversarial policy acting in a multi-agent environment so as to create natural observations that are adversarial? We demonstrate the existence of adversarial policies in zero-sum games between simulated humanoid robots with proprioceptive observations, against state-of-the-art victims trained via self-play to be robust to opponents. The adversarial policies reliably win against the victims but generate seemingly random and uncoordinated behavior. We find that these policies are more successful in high-dimensional environments, and induce substantially different activations in the victim policy network than when the victim plays against a normal opponent. Videos are available at <a href="http://adversarialpolicies.github.io.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10615](http://arxiv.org/abs/1905.10615)

##### PDF
[http://arxiv.org/pdf/1905.10615](http://arxiv.org/pdf/1905.10615)

