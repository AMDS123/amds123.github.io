---
layout: post
title: "Imitation Learning of Factored Multi-agent Reactive Models"
date: 2019-03-12 03:50:27
categories: arXiv_AI
tags: arXiv_AI Inference RNN
author: Michael Teng, Tuan Anh Le, Adam Scibior, Frank Wood
mathjax: true
---

* content
{:toc}

##### Abstract
We apply recent advances in deep generative modeling to the task of imitation learning from biological agents. Specifically, we apply variations of the variational recurrent neural network model to a multi-agent setting where we learn policies of individual uncoordinated agents acting based on their perceptual inputs and their hidden belief state. We learn stochastic policies for these agents directly from observational data, without constructing a reward function. An inference network learned jointly with the policy allows for efficient inference over the agent's belief state given a sequence of its current perceptual inputs and the prior actions it performed, which lets us extrapolate observed sequences of behavior into the future while maintaining uncertainty estimates over future trajectories. We test our approach on a dataset of flies interacting in a 2D environment, where we demonstrate better predictive performance than existing approaches which learn deterministic policies with recurrent neural networks. We further show that the uncertainty estimates over future trajectories we obtain are well calibrated, which makes them useful for a variety of downstream processing tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04714](http://arxiv.org/abs/1903.04714)

##### PDF
[http://arxiv.org/pdf/1903.04714](http://arxiv.org/pdf/1903.04714)

