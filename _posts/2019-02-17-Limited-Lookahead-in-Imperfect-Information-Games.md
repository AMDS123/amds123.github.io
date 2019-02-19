---
layout: post
title: "Limited Lookahead in Imperfect-Information Games"
date: 2019-02-17 21:50:05
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Christian Kroer, Tuomas Sandholm
mathjax: true
---

* content
{:toc}

##### Abstract
Limited lookahead has been studied for decades in complete-information games. We initiate a new direction via two simultaneous deviation points: generalization to incomplete-information games and a game-theoretic approach. We study how one should act when facing an opponent whose lookahead is limited. We study this for opponents that differ based on their lookahead depth, based on whether they, too, have incomplete information, and based on how they break ties. We characterize the hardness of finding a Nash equilibrium or an optimal commitment strategy for either player, showing that in some of these variations the problem can be solved in polynomial time while in others it is PPAD-hard or NP-hard. We proceed to design algorithms for computing optimal commitment strategies---for when the opponent breaks ties favorably, according to a fixed rule, or adversarially. We then experimentally investigate the impact of limited lookahead. The limited-lookahead player often obtains the value of the game if she knows the expected values of nodes in the game tree for some equilibrium---but we prove this is not sufficient in general. Finally, we study the impact of noise in those estimates and different lookahead depths. This uncovers an incomplete-information game lookahead pathology.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06335](http://arxiv.org/abs/1902.06335)

##### PDF
[http://arxiv.org/pdf/1902.06335](http://arxiv.org/pdf/1902.06335)

