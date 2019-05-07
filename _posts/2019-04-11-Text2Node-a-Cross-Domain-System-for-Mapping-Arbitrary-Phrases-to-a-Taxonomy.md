---
layout: post
title: "Text2Node: a Cross-Domain System for Mapping Arbitrary Phrases to a Taxonomy"
date: 2019-04-11 17:31:23
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding RNN Classification
author: Rohollah Soltani, Alexandre Tomberg
mathjax: true
---

* content
{:toc}

##### Abstract
Electronic health record (EHR) systems are used extensively throughout the healthcare domain. However, data interchangeability between EHR systems is limited due to the use of different coding standards across systems. Existing methods of mapping coding standards based on manual human experts mapping, dictionary mapping, symbolic NLP and classification are unscalable and cannot accommodate large scale EHR datasets. 
 In this work, we present Text2Node, a cross-domain mapping system capable of mapping medical phrases to concepts in a large taxonomy (such as SNOMED CT). The system is designed to generalize from a limited set of training samples and map phrases to elements of the taxonomy that are not covered by training data. As a result, our system is scalable, robust to wording variants between coding systems and can output highly relevant concepts when no exact concept exists in the target taxonomy. Text2Node operates in three main stages: first, the lexicon is mapped to word embeddings; second, the taxonomy is vectorized using node embeddings; and finally, the mapping function is trained to connect the two embedding spaces. We compared multiple algorithms and architectures for each stage of the training, including GloVe and FastText word embeddings, CNN and Bi-LSTM mapping functions, and node2vec for node embeddings. We confirmed the robustness and generalisation properties of Text2Node by mapping ICD-9-CM Diagnosis phrases to SNOMED CT and by zero-shot training at comparable accuracy. 
 This system is a novel methodological contribution to the task of normalizing and linking phrases to a taxonomy, advancing data interchangeability in healthcare. When applied, the system can use electronic health records to generate an embedding that incorporates taxonomical medical knowledge to improve clinical predictive models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01958](http://arxiv.org/abs/1905.01958)

##### PDF
[http://arxiv.org/pdf/1905.01958](http://arxiv.org/pdf/1905.01958)

