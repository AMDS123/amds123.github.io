---
layout: post
title: "Training Detection-Range-Frugal Cooperative Collision Avoidance Models for Quadcopters via Neuroevolution"
date: 2019-05-31 20:02:09
categories: arXiv_RO
tags: arXiv_RO Detection
author: Amir Behjat, Krushang Gabani, Souma Chowdhury
mathjax: true
---

* content
{:toc}

##### Abstract
Cooperative autonomous approaches to avoiding collisions among small Unmanned Aerial Vehicles (UAVs) is central to safe integration of UAVs within the civilian airspace. One potential online cooperative approach is the concept of reciprocal actions, where both UAVs take pre-trained mutually coherent actions that do not require active online coordination (thereby avoiding the computational burden and risk associated with it). This paper presents a learning based approach to train such reciprocal maneuvers. Neuroevolution, which uses evolutionary algorithms to simultaneously optimize the topology and weights of neural networks, is used as the learning method -- which operates over a set of sample approach scenarios. Unlike most existing work (that minimize travel distance, energy or risk), the training process here focuses on the objective of minimizing the required detection range; this has important practical implications w.r.t. alleviating the dependency on sophisticated sensing and their reliability under various environments. A specialized design of experiments and line search is used to identify the minimum detection range for each sample scenarios. In order to allow an efficient training process, a classifier is used to discard actions (without simulating them) where the controller would fail. The model obtained via neuroevolution is observed to generalize well to (i.e., successful collision avoidance over) unseen approach scenarios.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00052](http://arxiv.org/abs/1906.00052)

##### PDF
[http://arxiv.org/pdf/1906.00052](http://arxiv.org/pdf/1906.00052)

