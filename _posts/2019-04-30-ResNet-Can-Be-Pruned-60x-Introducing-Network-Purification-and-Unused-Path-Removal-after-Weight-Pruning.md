---
layout: post
title: "ResNet Can Be Pruned 60x: Introducing Network Purification and Unused Path Removal after Weight Pruning"
date: 2019-04-30 23:40:51
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Xiaolong Ma, Geng Yuan, Sheng Lin, Zhengang Li, Hao Sun, Yanzhi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The state-of-art DNN structures involve high computation and great demand for memory storage which pose intensive challenge on DNN framework resources. To mitigate the challenges, weight pruning techniques has been studied. However, high accuracy solution for extreme structured pruning that combines different types of structured sparsity still waiting for unraveling due to the extremely reduced weights in DNN networks. In this paper, we propose a DNN framework which combines two different types of structured weight pruning (filter and column prune) by incorporating alternating direction method of multipliers (ADMM) algorithm for better prune performance. We are the first to find non-optimality of ADMM process and unused weights in a structured pruned model, and further design an optimization framework which contains the first proposed Network Purification and Unused Path Removal algorithms which are dedicated to post-processing an structured pruned model after ADMM steps. Some high lights shows we achieve 232x compression on LeNet-5, 60x compression on ResNet-18 CIFAR-10 and over 5x compression on AlexNet. We share our models at anonymous link <a href="http://bit.ly/2VJ5ktv.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00136](http://arxiv.org/abs/1905.00136)

##### PDF
[http://arxiv.org/pdf/1905.00136](http://arxiv.org/pdf/1905.00136)

