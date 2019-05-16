---
layout: post
title: "Learning Policies from Self-Play with Policy Gradients and MCTS Value Estimates"
date: 2019-05-14 19:33:45
categories: arXiv_AI
tags: arXiv_AI
author: Dennis J. N. J. Soemers, &#xc9;ric Piette, Matthew Stephenson, Cameron Browne
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, state-of-the-art game-playing agents often involve policies that are trained in self-playing processes where Monte Carlo tree search (MCTS) algorithms and trained policies iteratively improve each other. The strongest results have been obtained when policies are trained to mimic the search behaviour of MCTS by minimising a cross-entropy loss. Because MCTS, by design, includes an element of exploration, policies trained in this manner are also likely to exhibit a similar extent of exploration. In this paper, we are interested in learning policies for a project with future goals including the extraction of interpretable strategies, rather than state-of-the-art game-playing performance. For these goals, we argue that such an extent of exploration is undesirable, and we propose a novel objective function for training policies that are not exploratory. We derive a policy gradient expression for maximising this objective function, which can be estimated using MCTS value estimates, rather than MCTS visit counts. We empirically evaluate various properties of resulting policies, in a variety of board games.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.05809](http://arxiv.org/abs/1905.05809)

##### PDF
[http://arxiv.org/pdf/1905.05809](http://arxiv.org/pdf/1905.05809)

