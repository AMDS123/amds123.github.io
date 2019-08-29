---
layout: post
title: "Consistent Cross-view Matching for Unsupervised Person Re-identification"
date: 2019-08-27 22:35:43
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Inference Relation
author: Xueping Wang, Rameswar Panda, Min Liu, Amit K Roy-Chowdhury
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing unsupervised person re-identificationmethods focus on learning an identity discriminative feature em-bedding for efficiently representing images of different persons.However, higher-order relationships across the entire cameranetwork are often ignored leading to contradictory outputs whenthe results of different camera pairs are combined. In this paper,we address this problem by proposing a consistent cross-viewmatching framework for unsupervised person re-identificationby exploiting more reliable positive image pairs in a cameranetwork. Specifically, we first construct a bipartite graph foreach pair of cameras, in which each node denotes a person, andthen graph matching is used to obtain optimal global matchesacross camera pairs. Thereafter, loop consistent and transitiveinference consistent constraints are introduced into the cross-view matches, which consider similarity relationshipsacross theentire camera networkto increase confidence in the matched/non-matched pairs. We then train distance metric models for eachcamera pair using the reliably matched image pairs. Finally,we embed the cross-view matching method into an iterativeupdating framework that iterates between the consistent cross-view matching and the cross-view distance metric learning. Wedemonstrate the superiority of the proposed method over thestate-of-the-art unsupervised person re-identification methodson three benchmark datasets such as Market1501, MARS andDukeMTMC-VideoReID datasets

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10486](http://arxiv.org/abs/1908.10486)

##### PDF
[http://arxiv.org/pdf/1908.10486](http://arxiv.org/pdf/1908.10486)

