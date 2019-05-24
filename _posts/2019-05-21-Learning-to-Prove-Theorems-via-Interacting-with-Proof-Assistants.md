---
layout: post
title: "Learning to Prove Theorems via Interacting with Proof Assistants"
date: 2019-05-21 17:56:02
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Kaiyu Yang, Jia Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Humans prove theorems by relying on substantial high-level reasoning and problem-specific insights. Proof assistants offer a formalism that resembles human mathematical reasoning, representing theorems in higher-order logic and proofs as high-level tactics. However, human experts have to construct proofs manually by entering tactics into the proof assistant. In this paper, we study the problem of using machine learning to automate the interaction with proof assistants. We construct CoqGym, a large-scale dataset and learning environment containing 71K human-written proofs from 123 projects developed with the Coq proof assistant. We develop ASTactic, a deep learning-based model that generates tactics as programs in the form of abstract syntax trees (ASTs). Experiments show that ASTactic trained on CoqGym can generate effective tactics and can be used to prove new theorems not previously provable by automated methods. Code is available at https://github.com/princeton-vl/CoqGym.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09381](http://arxiv.org/abs/1905.09381)

##### PDF
[http://arxiv.org/pdf/1905.09381](http://arxiv.org/pdf/1905.09381)

