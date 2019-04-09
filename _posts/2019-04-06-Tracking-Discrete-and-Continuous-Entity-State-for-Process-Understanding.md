---
layout: post
title: "Tracking Discrete and Continuous Entity State for Process Understanding"
date: 2019-04-06 19:56:14
categories: arXiv_CL
tags: arXiv_CL QA Tracking
author: Aditya Gupta, Greg Durrett
mathjax: true
---

* content
{:toc}

##### Abstract
Procedural text, which describes entities and their interactions as they undergo some process, depicts entities in a uniquely nuanced way. First, each entity may have some observable discrete attributes, such as its state or location; modeling these involves imposing global structure and enforcing consistency. Second, an entity may have properties which are not made explicit but can be effectively induced and tracked by neural networks. In this paper, we propose a structured neural architecture that reflects this dual nature of entity evolution. The model tracks each entity recurrently, updating its hidden continuous representation at each step to contain relevant state information. The global discrete state structure is explicitly modeled with a neural CRF over the changing hidden representation of the entity. This CRF can explicitly capture constraints on entity states over time, enforcing that, for example, an entity cannot move to a location after it is destroyed. We evaluate the performance of our proposed model on QA tasks over process paragraphs in the ProPara dataset and find that our model achieves state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03518](http://arxiv.org/abs/1904.03518)

##### PDF
[http://arxiv.org/pdf/1904.03518](http://arxiv.org/pdf/1904.03518)

