---
layout: post
title: "A Little Annotation does a Lot of Good: A Study in Bootstrapping Low-resource Named Entity Recognizers"
date: 2019-08-23 19:15:07
categories: arXiv_CL
tags: arXiv_CL Transfer_Learning Prediction Recognition
author: Aditi Chaudhary, Jiateng Xie, Zaid Sheikh, Graham Neubig, Jaime G. Carbonell
mathjax: true
---

* content
{:toc}

##### Abstract
Most state-of-the-art models for named entity recognition (NER) rely on the availability of large amounts of labeled data, making them challenging to extend to new, lower-resourced languages. However, there are now several proposed approaches involving either cross-lingual transfer learning, which learns from other highly resourced languages, or active learning, which efficiently selects effective training data based on model predictions. This paper poses the question: given this recent progress, and limited human annotation, what is the most effective method for efficiently creating high-quality entity recognizers in under-resourced languages? Based on extensive experimentation using both simulated and real human annotation, we find a dual-strategy approach best, starting with a cross-lingual transferred model, then performing targeted annotation of only uncertain entity spans in the target language, minimizing annotator effort. Results demonstrate that cross-lingual transfer is a powerful tool when very little data can be annotated, but an entity-targeted annotation strategy can achieve competitive accuracy quickly, with just one-tenth of training data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08983](http://arxiv.org/abs/1908.08983)

##### PDF
[http://arxiv.org/pdf/1908.08983](http://arxiv.org/pdf/1908.08983)

