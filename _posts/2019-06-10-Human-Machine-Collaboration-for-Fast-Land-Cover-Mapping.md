---
layout: post
title: "Human-Machine Collaboration for Fast Land Cover Mapping"
date: 2019-06-10 16:04:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction
author: Caleb Robinson, Anthony Ortiz, Kolya Malkin, Blake Elias, Andi Peng, Dan Morris, Bistra Dilkina, Nebojsa Jojic
mathjax: true
---

* content
{:toc}

##### Abstract
We propose incorporating human labelers in a model fine-tuning system that provides immediate user feedback. In our framework, human labelers can interactively query model predictions on unlabeled data, choose which data to label, and see the resulting effect on the model's predictions. This bi-directional feedback loop allows humans to learn how the model responds to new data. Our hypothesis is that this rich feedback allows human labelers to create mental models that enable them to better choose which biases to introduce to the model. We compare human-selected points to points selected using standard active learning methods. We further investigate how the fine-tuning methodology impacts the human labelers' performance. We implement this framework for fine-tuning high-resolution land cover segmentation models. Specifically, we fine-tune a deep neural network -- trained to segment high-resolution aerial imagery into different land cover classes in Maryland, USA -- to a new spatial area in New York, USA. The tight loop turns the algorithm and the human operator into a hybrid system that can produce land cover maps of a large area much more efficiently than the traditional workflows. Our framework has applications in geospatial machine learning settings where there is a practically limitless supply of unlabeled data, of which only a small fraction can feasibly be labeled through human efforts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04176](http://arxiv.org/abs/1906.04176)

##### PDF
[http://arxiv.org/pdf/1906.04176](http://arxiv.org/pdf/1906.04176)

