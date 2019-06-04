---
layout: post
title: "Pre-training of Graph Augmented Transformers for Medication Recommendation"
date: 2019-06-02 05:11:38
categories: arXiv_AI
tags: arXiv_AI Knowledge Represenation_Learning Language_Model Prediction Recommendation
author: Junyuan Shang, Tengfei Ma, Cao Xiao, Jimeng Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Medication recommendation is an important healthcare application. It is commonly formulated as a temporal prediction task. Hence, most existing works only utilize longitudinal electronic health records (EHRs) from a small number of patients with multiple visits ignoring a large number of patients with a single visit (selection bias). Moreover, important hierarchical knowledge such as diagnosis hierarchy is not leveraged in the representation learning process. To address these challenges, we propose G-BERT, a new model to combine the power of Graph Neural Networks (GNNs) and BERT (Bidirectional Encoder Representations from Transformers) for medical code representation and medication recommendation. We use GNNs to represent the internal hierarchical structures of medical codes. Then we integrate the GNN representation into a transformer-based visit encoder and pre-train it on EHR data from patients only with a single visit. The pre-trained visit encoder and representation are then fine-tuned for downstream predictive tasks on longitudinal EHRs from patients with multiple visits. G-BERT is the first to bring the language model pre-training schema into the healthcare domain and it achieved state-of-the-art performance on the medication recommendation task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00346](http://arxiv.org/abs/1906.00346)

##### PDF
[http://arxiv.org/pdf/1906.00346](http://arxiv.org/pdf/1906.00346)

