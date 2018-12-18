---
layout: post
title: "Lifelong Path Planning with Kinematic Constraints for Multi-Agent Pickup and Delivery"
date: 2018-12-15 20:55:25
categories: arXiv_AI
tags: arXiv_AI
author: Hang Ma, Wolfgang H&#xf6;nig, T. K. Satish Kumar, Nora Ayanian, Sven Koenig
mathjax: true
---

* content
{:toc}

##### Abstract
The Multi-Agent Pickup and Delivery (MAPD) problem models applications where a large number of agents attend to a stream of incoming pickup-and-delivery tasks. Token Passing (TP) is a recent MAPD algorithm that is efficient and effective. We make TP even more efficient and effective by using a novel combinatorial search algorithm, called Safe Interval Path Planning with Reservation Table (SIPPwRT), for single-agent path planning. SIPPwRT uses an advanced data structure that allows for fast updates and lookups of the current paths of all agents in an online setting. The resulting MAPD algorithm TP-SIPPwRT takes kinematic constraints of real robots into account directly during planning, computes continuous agent movements with given velocities that work on non-holonomic robots rather than discrete agent movements with uniform velocity, and is complete for well-formed MAPD instances. We demonstrate its benefits for automated warehouses using both an agent simulator and a standard robot simulator. For example, we demonstrate that it can compute paths for hundreds of agents and thousands of tasks in seconds and is more efficient and effective than existing MAPD algorithms that use a post-processing step to adapt their paths to continuous agent movements with given velocities.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06355](http://arxiv.org/abs/1812.06355)

##### PDF
[http://arxiv.org/pdf/1812.06355](http://arxiv.org/pdf/1812.06355)

