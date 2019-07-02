---
layout: post
title: "Border-Peeling Clustering"
date: 2019-06-30 07:15:44
categories: arXiv_CV
tags: arXiv_CV CNN
author: Hadar Averbuch-Elor, Nadav Bar, Daniel Cohen-Or
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel non-parametric clustering technique. Our technique is based on the notion that each latent cluster is comprised of layers that surround its core, where the external layers, or border points, implicitly separate the clusters. Unlike previous techniques, such as DBSCAN, where the cores of the clusters are defined directly by their densities, here the latent cores are revealed by a progressive peeling of the border points. Analyzing the density of the local neighborhoods allows identifying the border points and associating them with points of inner layers. We show that the peeling process adapts to the local densities and characteristics to successfully separate adjacent clusters (of possibly different densities). We extensively tested our technique on large sets of labeled data, including high-dimensional datasets of deep features that were trained by a convolutional neural network. We show that our technique is competitive to other state-of-the-art non-parametric methods using a fixed set of parameters throughout the experiments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1612.04869](http://arxiv.org/abs/1612.04869)

##### PDF
[http://arxiv.org/pdf/1612.04869](http://arxiv.org/pdf/1612.04869)

