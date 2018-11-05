---
layout: post
title: "Automated Theorem Proving in Intuitionistic Propositional Logic by Deep Reinforcement Learning"
date: 2018-11-02 09:49:18
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Deep_Learning
author: Mitsuru Kusumoto, Keisuke Yahata, Masahiro Sakai
mathjax: true
---

* content
{:toc}

##### Abstract
The problem-solving in automated theorem proving (ATP) can be interpreted as a search problem where the prover constructs a proof tree step by step. In this paper, we propose a deep reinforcement learning algorithm for proof search in intuitionistic propositional logic. The most significant challenge in the application of deep learning to the ATP is the absence of large, public theorem database. We, however, overcame this issue by applying a novel data augmentation procedure at each iteration of the reinforcement learning. We also improve the efficiency of the algorithm by representing the syntactic structure of formulas by a novel compact graph representation. Using the large volume of augmented data, we train highly accurate graph neural networks that approximate the value function for the set of the syntactic structures of formulas. Our method is also cost-efficient in terms of computational time. We will show that our prover outperforms Coq's $\texttt{tauto}$ tactic, a prover based on human-engineered heuristics. Within the specified time limit, our prover solved 84% of the theorems in a benchmark library, while $\texttt{tauto}$ was able to solve only 52%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00796](http://arxiv.org/abs/1811.00796)

##### PDF
[http://arxiv.org/pdf/1811.00796](http://arxiv.org/pdf/1811.00796)

