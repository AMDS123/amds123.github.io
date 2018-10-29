---
layout: post
title: "MGP: Un algorithme de planification temps réel prenant en compte l'évolution dynamique du but"
date: 2018-10-22 12:02:56
categories: arXiv_AI
tags: arXiv_AI
author: Damien Pellier, Mickaël Vanneufville, Humbert Fiorino, Marc Métivier, Bruno Bouzy
mathjax: true
---

* content
{:toc}

##### Abstract
Devising intelligent robots or agents that interact with humans is a major challenge for artificial intelligence. In such contexts, agents must constantly adapt their decisions according to human activities and modify their goals. In this paper, we tackle this problem by introducing a novel planning approach, called Moving Goal Planning (MGP), to adapt plans to goal evolutions. This planning algorithm draws inspiration from Moving Target Search (MTS) algorithms. In order to limit the number of search iterations and to improve its efficiency, MGP delays as much as possible triggering new searches when the goal changes over time. To this purpose, MGP uses two strategies: Open Check (OC) that checks if the new goal is still in the current search tree and Plan Follow (PF) that estimates whether executing actions of the current plan brings MGP closer to the new goal. Moreover, MGP uses a parsimonious strategy to update incrementally the search tree at each new search that reduces the number of calls to the heuristic function and speeds up the search. Finally, we show evaluation results that demonstrate the effectiveness of our approach.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10908](https://arxiv.org/abs/1810.10908)

##### PDF
[https://arxiv.org/pdf/1810.10908](https://arxiv.org/pdf/1810.10908)

