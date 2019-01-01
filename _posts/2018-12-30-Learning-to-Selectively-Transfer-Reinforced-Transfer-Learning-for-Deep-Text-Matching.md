---
layout: post
title: "Learning to Selectively Transfer: Reinforced Transfer Learning for Deep Text Matching"
date: 2018-12-30 15:39:57
categories: arXiv_CL
tags: arXiv_CL Transfer_Learning Optimization Inference
author: Chen Qu, Feng Ji, Minghui Qiu, Liu Yang, Zhiyu Min, Haiqing Chen, Jun Huang, W. Bruce Croft
mathjax: true
---

* content
{:toc}

##### Abstract
Deep text matching approaches have been widely studied for many applications including question answering and information retrieval systems. To deal with a domain that has insufficient labeled data, these approaches can be used in a Transfer Learning (TL) setting to leverage labeled data from a resource-rich source domain. To achieve better performance, source domain data selection is essential in this process to prevent the "negative transfer" problem. However, the emerging deep transfer models do not fit well with most existing data selection methods, because the data selection policy and the transfer learning model are not jointly trained, leading to sub-optimal training efficiency. 
 In this paper, we propose a novel reinforced data selector to select high-quality source domain data to help the TL model. Specifically, the data selector "acts" on the source domain data to find a subset for optimization of the TL model, and the performance of the TL model can provide "rewards" in turn to update the selector. We build the reinforced data selector based on the actor-critic framework and integrate it to a DNN based transfer learning model, resulting in a Reinforced Transfer Learning (RTL) method. We perform a thorough experimental evaluation on two major tasks for text matching, namely, paraphrase identification and natural language inference. Experimental results show the proposed RTL can significantly improve the performance of the TL model. We further investigate different settings of states, rewards, and policy optimization methods to examine the robustness of our method. Last, we conduct a case study on the selected data and find our method is able to select source domain data whose Wasserstein distance is close to the target domain data. This is reasonable and intuitive as such source domain data can provide more transferability power to the model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11561](http://arxiv.org/abs/1812.11561)

##### PDF
[http://arxiv.org/pdf/1812.11561](http://arxiv.org/pdf/1812.11561)

