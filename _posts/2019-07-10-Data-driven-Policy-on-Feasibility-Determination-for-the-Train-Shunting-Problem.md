---
layout: post
title: "Data-driven Policy on Feasibility Determination for the Train Shunting Problem"
date: 2019-07-10 13:32:14
categories: arXiv_AI
tags: arXiv_AI CNN Prediction
author: Paulo R. de O. da Costa, J. Rhuggenaath, Y. Zhang, A. Akcay, W. Lee, U. Kaymak
mathjax: true
---

* content
{:toc}

##### Abstract
Parking, matching, scheduling, and routing are common problems in train maintenance. In particular, train units are commonly maintained and cleaned at dedicated shunting yards. The planning problem that results from such situations is referred to as the Train Unit Shunting Problem (TUSP). This problem involves matching arriving train units to service tasks and determining the schedule for departing trains. The TUSP is an important problem as it is used to determine the capacity of shunting yards and arises as a sub-problem of more general scheduling and planning problems. In this paper, we consider the case of the Dutch Railways (NS) TUSP. As the TUSP is complex, NS currently uses a local search (LS) heuristic to determine if an instance of the TUSP has a feasible solution. Given the number of shunting yards and the size of the planning problems, improving the evaluation speed of the LS brings significant computational gain. In this work, we use a machine learning approach that complements the LS and accelerates the search process. We use a Deep Graph Convolutional Neural Network (DGCNN) model to predict the feasibility of solutions obtained during the run of the LS heuristic. We use this model to decide whether to continue or abort the search process. In this way, the computation time is used more efficiently as it is spent on instances that are more likely to be feasible. Using simulations based on real-life instances of the TUSP, we show how our approach improves upon the previous method on prediction accuracy and leads to computational gains for the decision-making process.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04711](http://arxiv.org/abs/1907.04711)

##### PDF
[http://arxiv.org/pdf/1907.04711](http://arxiv.org/pdf/1907.04711)

