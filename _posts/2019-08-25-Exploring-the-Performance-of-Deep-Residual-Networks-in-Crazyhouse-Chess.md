---
layout: post
title: "Exploring the Performance of Deep Residual Networks in Crazyhouse Chess"
date: 2019-08-25 10:18:02
categories: arXiv_AI
tags: arXiv_AI
author: Sun-Yu Gordon Chi
mathjax: true
---

* content
{:toc}

##### Abstract
Crazyhouse is a chess variant that incorporates all of the classical chess rules, but allows users to drop pieces captured from the opponent as a normal move. Until 2018, all competitive computer engines for this board game made use of an alpha-beta pruning algorithm with a hand-crafted evaluation function for each position. Previous machine learning-based algorithms for just regular chess, such as NeuroChess and Giraffe, took hand-crafted evaluation features as input rather than a raw board representation. More recent projects, such as AlphaZero, reached massive success but required massive computational resources in order to reach its final strength. 
 This paper describes the development of SixtyFour, an engine designed to compete in the chess variant of Crazyhouse with limited hardware. This specific variant poses a multitude of significant challenges due to its large branching factor, state-space complexity, and the multiple move types a player can make. We propose the novel creation of a neural network-based evaluation function for Crazyhouse. More importantly, we evaluate the effectiveness of an ensemble model, which allows the training time and datasets to be easily distributed on regular CPU hardware commodity. Early versions of the network have attained a playing level comparable to a strong amateur on online servers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09296](http://arxiv.org/abs/1908.09296)

##### PDF
[http://arxiv.org/pdf/1908.09296](http://arxiv.org/pdf/1908.09296)

