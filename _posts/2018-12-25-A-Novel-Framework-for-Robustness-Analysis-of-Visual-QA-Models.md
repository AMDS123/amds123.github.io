---
layout: post
title: "A Novel Framework for Robustness Analysis of Visual QA Models"
date: 2018-12-25 04:08:27
categories: arXiv_CV
tags: arXiv_CV Adversarial QA Optimization VQA
author: Jia-Hong Huang, Cuong Duc Dao, Modar Alfadly, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have been playing an essential role in many computer vision tasks including Visual Question Answering (VQA). Until recently, the study of their accuracy was the main focus of research but now there is a trend toward assessing the robustness of these models against adversarial attacks by evaluating their tolerance to varying noise levels. In VQA, adversarial attacks can target the image and/or the proposed main question and yet there is a lack of proper analysis of the later. In this work, we propose a flexible framework that focuses on the language part of VQA that uses semantically relevant questions, dubbed basic questions, acting as controllable noise to evaluate the robustness of VQA models. We hypothesize that the level of noise is positively correlated to the similarity of a basic question to the main question. Hence, to apply noise on any given main question, we rank a pool of basic questions based on their similarity by casting this ranking task as a LASSO optimization problem. Then, we propose a novel robustness measure, R_score, and two large-scale basic question datasets (BQDs) in order to standardize robustness analysis for VQA models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.06232](https://arxiv.org/abs/1711.06232)

##### PDF
[https://arxiv.org/pdf/1711.06232](https://arxiv.org/pdf/1711.06232)

