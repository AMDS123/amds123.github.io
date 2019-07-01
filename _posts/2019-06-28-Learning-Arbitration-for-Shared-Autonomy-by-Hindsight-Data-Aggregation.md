---
layout: post
title: "Learning Arbitration for Shared Autonomy by Hindsight Data Aggregation"
date: 2019-06-28 16:01:59
categories: arXiv_RO
tags: arXiv_RO Inference Prediction
author: Yoojin Oh, Marc Toussaint, Jim Mainprice
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a framework for the teleoperation of pick-and-place tasks. We define a shared control policy that allows to blend between direct user control and autonomous control based on user intent inference. One of the main challenges in shared autonomy systems is to define the arbitration function, which decides when to let the autonomous agent take over. In this work, we propose a model and training method to learn the arbitration function. Our model is based on a recurrent neural network that takes as input the state, intent prediction scores and user command to produce an arbitration between user and robot commands. This work extends our previous work on differentiable policies for shared autonomy. Differentiability of the policy is desirable to further train the shared autonomy system end-to-end. In this work we propose training of the arbitration function by using data from user performing the task with shared control. We present initial results by teleoperating a gripper in a virtual environment using pre-trained motion generation and intent prediction. We compare our data aggregation training procedure to a handcrafted arbitration function. Our preliminary results show the efficacy of the approach and shed light on limitations that we believe demonstrate the need for user adaptability in shared autonomy systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.12280](http://arxiv.org/abs/1906.12280)

##### PDF
[http://arxiv.org/pdf/1906.12280](http://arxiv.org/pdf/1906.12280)

