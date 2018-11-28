---
layout: post
title: "Optimization of Information-Seeking Dialogue Strategy for Argumentation-Based Dialogue System"
date: 2018-11-26 22:56:07
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Hisao Katsumi, Takuya Hiraoka, Koichiro Yoshino, Kazeto Yamamoto, Shota Motoura, Kunihiko Sadamasa, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
Argumentation-based dialogue systems, which can handle and exchange arguments through dialogue, have been widely researched. It is required that these systems have sufficient supporting information to argue their claims rationally; however, the systems often do not have enough of such information in realistic situations. One way to fill in the gap is acquiring such missing information from dialogue partners (information-seeking dialogue). Existing information-seeking dialogue systems are based on handcrafted dialogue strategies that exhaustively examine missing information. However, the proposed strategies are not specialized in collecting information for constructing rational arguments. Moreover, the number of system's inquiry candidates grows in accordance with the size of the argument set that the system deal with. In this paper, we formalize the process of information-seeking dialogue as Markov decision processes (MDPs) and apply deep reinforcement learning (DRL) for automatically optimizing a dialogue strategy. By utilizing DRL, our dialogue strategy can successfully minimize objective functions, the number of turns it takes for our system to collect necessary information in a dialogue. We conducted dialogue experiments using two datasets from different domains of argumentative dialogue. Experimental results show that the proposed formalization based on MDP works well, and the policy optimized by DRL outperformed existing heuristic dialogue strategies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10728](http://arxiv.org/abs/1811.10728)

##### PDF
[http://arxiv.org/pdf/1811.10728](http://arxiv.org/pdf/1811.10728)

