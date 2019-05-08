---
layout: post
title: "Neural Architecture Refinement: A Practical Way for Avoiding Overfitting in NAS"
date: 2019-05-07 03:41:12
categories: arXiv_CV
tags: arXiv_CV Face NAS Optimization Classification Recognition Face_Recognition
author: Yang Jiang, Cong Zhao, Lei Pang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural architecture search (NAS) is proposed to automate the architecture design process and attracts overwhelming interest from both academia and industry. However, it is confronted with overfitting issue due to the high-dimensional search space composed by $operator$ selection and $skip$ connection of each layer. This paper analyzes the overfitting issue from a novel perspective, which separates the primitives of search space into architecture-overfitting related and parameter-overfitting related elements. The $operator$ of each layer, which mainly contributes to parameter-overfitting and is important for model acceleration, is selected as our optimization target based on state-of-the-art architecture, meanwhile $skip$ which related to architecture-overfitting, is ignored. With the largely reduced search space, our proposed method is both quick to converge and practical to use in various tasks. Extensive experiments have demonstrated that the proposed method can achieve fascinated results, including classification, face recognition etc.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.02341](https://arxiv.org/abs/1905.02341)

##### PDF
[https://arxiv.org/pdf/1905.02341](https://arxiv.org/pdf/1905.02341)

