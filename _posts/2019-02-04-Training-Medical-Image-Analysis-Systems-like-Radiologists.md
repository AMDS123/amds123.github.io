---
layout: post
title: "Training Medical Image Analysis Systems like Radiologists"
date: 2019-02-04 05:12:29
categories: arXiv_AI
tags: arXiv_AI Classification
author: Gabriel Maicas, Andrew P. Bradley, Jacinto C. Nascimento, Ian Reid, Gustavo Carneiro
mathjax: true
---

* content
{:toc}

##### Abstract
The training of medical image analysis systems using machine learning approaches follows a common script: collect and annotate a large dataset, train the classifier on the training set, and test it on a hold-out test set. This process bears no direct resemblance with radiologist training, which is based on solving a series of tasks of increasing difficulty, where each task involves the use of significantly smaller datasets than those used in machine learning. In this paper, we propose a novel training approach inspired by how radiologists are trained. In particular, we explore the use of meta-training that models a classifier based on a series of tasks. Tasks are selected using teacher-student curriculum learning, where each task consists of simple classification problems containing small training sets. We hypothesize that our proposed meta-training approach can be used to pre-train medical image analysis models. This hypothesis is tested on the automatic breast screening classification from DCE-MRI trained with weakly labeled datasets. The classification performance achieved by our approach is shown to be the best in the field for that application, compared to state of art baseline approaches: DenseNet, multiple instance learning and multi-task learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.10884](http://arxiv.org/abs/1805.10884)

##### PDF
[http://arxiv.org/pdf/1805.10884](http://arxiv.org/pdf/1805.10884)

