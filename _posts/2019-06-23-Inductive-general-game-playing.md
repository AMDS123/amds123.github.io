---
layout: post
title: "Inductive general game playing"
date: 2019-06-23 19:06:09
categories: arXiv_AI
tags: arXiv_AI
author: Andrew Cropper, Richard Evans, Mark Law
mathjax: true
---

* content
{:toc}

##### Abstract
General game playing (GGP) is a framework for evaluating an agent's general intelligence across a wide range of tasks. In the GGP competition, an agent is given the rules of a game (described as a logic program) that it has never seen before. The task is for the agent to play the game, thus generating game traces. The winner of the GGP competition is the agent that gets the best total score over all the games. In this paper, we invert this task: a learner is given game traces and the task is to learn the rules that could produce the traces. This problem is central to inductive general game playing (IGGP). We introduce a technique that automatically generates IGGP tasks from GGP games. We introduce an IGGP dataset which contains traces from 50 diverse games, such as Sudoku, Sokoban, and Checkers. We claim that IGGP is difficult for existing inductive logic programming (ILP) approaches. To support this claim, we evaluate existing ILP systems on our dataset. Our empirical results show that most of the games cannot be correctly learned by existing systems. The best performing system solves only 40% of the tasks perfectly. Our results suggest that IGGP poses many challenges to existing approaches. Furthermore, because we can automatically generate IGGP tasks from GGP games, our dataset will continue to grow with the GGP competition, as new games are added every year. We therefore think that the IGGP problem and dataset will be valuable for motivating and evaluating future research.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09627](http://arxiv.org/abs/1906.09627)

##### PDF
[http://arxiv.org/pdf/1906.09627](http://arxiv.org/pdf/1906.09627)

