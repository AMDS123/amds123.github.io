---
layout: post
title: "Learning to Reason in Large Theories without Imitation"
date: 2019-05-25 02:36:25
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Kshitij Bansal, Sarah M. Loos, Markus N. Rabe, Christian Szegedy
mathjax: true
---

* content
{:toc}

##### Abstract
Automated theorem proving in large theories can be learned via reinforcement learning over an indefinitely growing action space. In order to select actions, one performs nearest neighbor lookups in the knowledge base to find premises to be applied. Here we address the exploration for reinforcement learning in this space. Approaches (like epsilon-greedy strategy) that sample actions uniformly do not scale to this scenario as most actions lead to dead ends and unsuccessful proofs which are not useful for training our models. In this paper, we compare approaches that select premises using randomly initialized similarity measures and mixing them with the proposals of the learned model. We evaluate these on the HOList benchmark for tactics based higher order theorem proving. We implement an automated theorem prover named DeepHOL-Zero that does not use any of the human proofs and show that our improved exploration method manages to expand the training set continuously. DeepHOL-Zero outperforms the best theorem prover trained by imitation learning alone.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10501](http://arxiv.org/abs/1905.10501)

##### PDF
[http://arxiv.org/pdf/1905.10501](http://arxiv.org/pdf/1905.10501)

