---
layout: post
title: "Automatic Accuracy Prediction for AMR Parsing"
date: 2019-04-17 14:59:45
categories: arXiv_CL
tags: arXiv_CL Prediction
author: Juri Opitz, Anette Frank
mathjax: true
---

* content
{:toc}

##### Abstract
Abstract Meaning Representation (AMR) represents sentences as directed, acyclic and rooted graphs, aiming at capturing their meaning in a machine readable format. AMR parsing converts natural language sentences into such graphs. However, evaluating a parser on new data by means of comparison to manually created AMR graphs is very costly. Also, we would like to be able to detect parses of questionable quality, or preferring results of alternative systems by selecting the ones for which we can assess good quality. We propose AMR accuracy prediction as the task of predicting several metrics of correctness for an automatically generated AMR parse - in absence of the corresponding gold parse. We develop a neural end-to-end multi-output regression model and perform three case studies: firstly, we evaluate the model's capacity of predicting AMR parse accuracies and test whether it can reliably assign high scores to gold parses. Secondly, we perform parse selection based on predicted parse accuracies of candidate parses from alternative systems, with the aim of improving overall results. Finally, we predict system ranks for submissions from two AMR shared tasks on the basis of their predicted parse accuracy averages. All experiments are carried out across two different domains and show that our method is effective.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08301](http://arxiv.org/abs/1904.08301)

##### PDF
[http://arxiv.org/pdf/1904.08301](http://arxiv.org/pdf/1904.08301)

