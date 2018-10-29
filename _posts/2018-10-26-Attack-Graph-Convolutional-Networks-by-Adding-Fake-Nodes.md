---
layout: post
title: "Attack Graph Convolutional Networks by Adding Fake Nodes"
date: 2018-10-26 06:59:12
categories: arXiv_AI
tags: arXiv_AI GAN CNN Classification
author: Xiaoyun Wang, Joe Eaton, Cho-Jui Hsieh, Felix Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Graph convolutional networks (GCNs) have been widely used for classifying graph nodes in the semi-supervised setting. Previous work have shown that GCNs are vulnerable to the perturbation on adjacency and feature matrices of existing nodes. However, it is unrealistic to change existing nodes in many applications, such as existing users in social networks. In this paper, we design algorithms to attack GCNs by adding fake nodes. A greedy algorithm is proposed to generate adjacency and feature matrices of fake nodes, aiming to minimize the classification accuracy on the existing nodes. In additional, we introduce a discriminator to classify fake nodes from real nodes, and propose a Greedy-GAN attack to simultaneously update the discriminator and the attacker, to make fake nodes indistinguishable to the real ones. Our non-targeted attack decreases the accuracy of GCN down to 0.10, and our targeted attack reaches a success rate of 99% on the whole datasets, and 94% on average for attacking a single target node.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10751](https://arxiv.org/abs/1810.10751)

##### PDF
[https://arxiv.org/pdf/1810.10751](https://arxiv.org/pdf/1810.10751)

