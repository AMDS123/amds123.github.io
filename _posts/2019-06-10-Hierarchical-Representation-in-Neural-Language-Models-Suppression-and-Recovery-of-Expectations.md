---
layout: post
title: "Hierarchical Representation in Neural Language Models: Suppression and Recovery of Expectations"
date: 2019-06-10 15:20:32
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Deep_Learning Language_Model
author: Ethan Wilcox, Roger Levy, Richard Futrell
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning sequence models have led to a marked increase in performance for a range of Natural Language Processing tasks, but it remains an open question whether they are able to induce proper hierarchical generalizations for representing natural language from linear input alone. Work using artificial languages as training input has shown that LSTMs are capable of inducing the stack-like data structures required to represent context-free and certain mildly context-sensitive languages---formal language classes which correspond in theory to the hierarchical structures of natural language. Here we present a suite of experiments probing whether neural language models trained on linguistic data induce these stack-like data structures and deploy them while incrementally predicting words. We study two natural language phenomena: center embedding sentences and syntactic island constraints on the filler--gap dependency. In order to properly predict words in these structures, a model must be able to temporarily suppress certain expectations and then recover those expectations later, essentially pushing and popping these expectations on a stack. Our results provide evidence that models can successfully suppress and recover expectations in many cases, but do not fully recover their previous grammatical state.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04068](http://arxiv.org/abs/1906.04068)

##### PDF
[http://arxiv.org/pdf/1906.04068](http://arxiv.org/pdf/1906.04068)

