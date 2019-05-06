---
layout: post
title: "Deep Choice Model Using Pointer Networks for Airline Itinerary Prediction"
date: 2018-03-15 19:55:56
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention RNN Prediction
author: Alejandro Mottini, Rodrigo Acuna-Agost
mathjax: true
---

* content
{:toc}

##### Abstract
Travel providers such as airlines and on-line travel agents are becoming more and more interested in understanding how passengers choose among alternative itineraries when searching for flights. This knowledge helps them better display and adapt their offer, taking into account market conditions and customer needs. Some common applications are not only filtering and sorting alternatives, but also changing certain attributes in real-time (e.g., changing the price). In this paper, we concentrate with the problem of modeling air passenger choices of flight itineraries. This problem has historically been tackled using classical Discrete Choice Modelling techniques. Traditional statistical approaches, in particular the Multinomial Logit model (MNL), is widely used in industrial applications due to its simplicity and general good performance. However, MNL models present several shortcomings and assumptions that might not hold in real applications. To overcome these difficulties, we present a new choice model based on Pointer Networks. Given an input sequence, this type of deep neural architecture combines Recurrent Neural Networks with the Attention Mechanism to learn the conditional probability of an output whose values correspond to positions in an input sequence. Therefore, given a sequence of different alternatives presented to a customer, the model can learn to point to the one most likely to be chosen by the customer. The proposed method was evaluated on a real dataset that combines on-line user search logs and airline flight bookings. Experimental results show that the proposed model outperforms the traditional MNL model on several metrics.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.05976](https://arxiv.org/abs/1803.05976)

##### PDF
[https://arxiv.org/pdf/1803.05976](https://arxiv.org/pdf/1803.05976)

