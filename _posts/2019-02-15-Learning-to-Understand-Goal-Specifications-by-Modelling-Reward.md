---
layout: post
title: "Learning to Understand Goal Specifications by Modelling Reward"
date: 2019-02-15 17:54:56
categories: arXiv_AI
tags: arXiv_AI Relation
author: Dzmitry Bahdanau, Felix Hill, Jan Leike, Edward Hughes, Arian Hosseini, Pushmeet Kohli, Edward Grefenstette
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown that deep reinforcement-learning agents can learn to follow language-like instructions from infrequent environment rewards. However, this places on environment designers the onus of designing language-conditional reward functions which may not be easily or tractably implemented as the complexity of the environment and the language scales. To overcome this limitation, we present a framework within which instruction-conditional RL agents are trained using rewards obtained not from the environment, but from reward models which are jointly trained from expert examples. As reward models improve, they learn to accurately reward agents for completing tasks for environment configurations---and for instructions---not present amongst the expert data. This framework effectively separates the representation of what instructions require from how they can be executed. In a simple grid world, it enables an agent to learn a range of commands requiring interaction with blocks and understanding of spatial relations and underspecified abstract arrangements. We further show the method allows our agent to adapt to changes in the environment without requiring new expert examples.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.01946](http://arxiv.org/abs/1806.01946)

##### PDF
[http://arxiv.org/pdf/1806.01946](http://arxiv.org/pdf/1806.01946)

