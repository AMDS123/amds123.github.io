---
layout: post
title: "On the definition of a general learning system with user-defined operators"
date: 2013-11-18 00:48:14
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning Transfer_Learning Prediction
author: Fernando Martínez-Plumed, Cèsar Ferri, José Hernández-Orallo, María-José Ramírez-Quintana
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we push forward the idea of machine learning systems whose operators can be modified and fine-tuned for each problem. This allows us to propose a learning paradigm where users can write (or adapt) their operators, according to the problem, data representation and the way the information should be navigated. To achieve this goal, data instances, background knowledge, rules, programs and operators are all written in the same functional language, Erlang. Since changing operators affect how the search space needs to be explored, heuristics are learnt as a result of a decision process based on reinforcement learning where each action is defined as a choice of operator and rule. As a result, the architecture can be seen as a 'system for writing machine learning systems' or to explore new operators where the policy reuse (as a kind of transfer learning) is allowed. States and actions are represented in a Q matrix which is actually a table, from which a supervised model is learnt. This makes it possible to have a more flexible mapping between old and new problems, since we work with an abstraction of rules and actions. We include some examples sharing reuse and the application of the system gErl to IQ problems. In order to evaluate gErl, we will test it against some structured problems: a selection of IQ test tasks and some experiments on some structured prediction problems (list patterns).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1311.4235](https://arxiv.org/abs/1311.4235)

##### PDF
[https://arxiv.org/pdf/1311.4235](https://arxiv.org/pdf/1311.4235)

