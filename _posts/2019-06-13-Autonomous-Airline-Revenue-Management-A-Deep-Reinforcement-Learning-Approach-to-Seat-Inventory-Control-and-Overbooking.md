---
layout: post
title: "Autonomous Airline Revenue Management: A Deep Reinforcement Learning Approach to Seat Inventory Control and Overbooking"
date: 2019-06-13 19:14:27
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Syed Arbab Mohd Shihab, Caleb Logemann, Deepak-George Thomas, Peng Wei
mathjax: true
---

* content
{:toc}

##### Abstract
Revenue management can enable airline corporations to maximize the revenue generated from each scheduled flight departing in their transportation network by means of finding the optimal policies for differential pricing, seat inventory control and overbooking. As different demand segments in the market have different Willingness-To-Pay (WTP), airlines use differential pricing, booking restrictions, and service amenities to determine different fare classes or products targeted at each of these demand segments. Because seats are limited for each flight, airlines also need to allocate seats for each of these fare classes to prevent lower fare class passengers from displacing higher fare class ones and set overbooking limits in anticipation of cancellations and no-shows such that revenue is maximized. Previous work addresses these problems using optimization techniques or classical Reinforcement Learning methods. This paper focuses on the latter problem - the seat inventory control problem - casting it as a Markov Decision Process to be able to find the optimal policy. Multiple fare classes, concurrent continuous arrival of passengers of different fare classes, overbooking and random cancellations that are independent of class have been considered in the model. We have addressed this problem using Deep Q-Learning with the goal of maximizing the reward for each flight departure. The implementation of this technique allows us to employ large continuous state space but also presents the potential opportunity to test on real time airline data. To generate data and train the agent, a basic air-travel market simulator was developed. The performance of the agent in different simulated market scenarios was compared against theoretically optimal solutions and was found to be nearly close to the expected optimal revenue.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06824](http://arxiv.org/abs/1902.06824)

##### PDF
[http://arxiv.org/pdf/1902.06824](http://arxiv.org/pdf/1902.06824)

