---
layout: post
title: "Named Entity Recognition in Electronic Health Records Using Transfer Learning Bootstrapped Neural Networks"
date: 2019-01-06 18:53:12
categories: arXiv_AI
tags: arXiv_AI Embedding Transfer_Learning Relation Recognition
author: Luka Gligic, Andrey Kormilitzin, Paul Goldberg, Alejo Nevado-Holgado
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks (NNs) have become the state of the art in many machine learning applications, especially in image and sound processing [1]. The same, although to a lesser extent [2,3], could be said in natural language processing (NLP) tasks, such as named entity recognition. However, the success of NNs remains dependent on the availability of large labelled datasets, which is a significant hurdle in many important applications. One such case are electronic health records (EHRs), which are arguably the largest source of medical data, most of which lies hidden in natural text [4,5]. Data access is difficult due to data privacy concerns, and therefore annotated datasets are scarce. With scarce data, NNs will likely not be able to extract this hidden information with practical accuracy. In our study, we develop an approach that solves these problems for named entity recognition, obtaining 94.6 F1 score in I2B2 2009 Medical Extraction Challenge [6], 4.3 above the architecture that won the competition. Beyond the official I2B2 challenge, we further achieve 82.4 F1 on extracting relationships between medical terms. To reach this state-of-the-art accuracy, our approach applies transfer learning to leverage on datasets annotated for other I2B2 tasks, and designs and trains embeddings that specially benefit from such transfer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01592](http://arxiv.org/abs/1901.01592)

##### PDF
[http://arxiv.org/pdf/1901.01592](http://arxiv.org/pdf/1901.01592)

