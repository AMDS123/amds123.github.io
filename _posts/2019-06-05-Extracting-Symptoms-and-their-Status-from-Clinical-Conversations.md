---
layout: post
title: "Extracting Symptoms and their Status from Clinical Conversations"
date: 2019-06-05 18:34:16
categories: arXiv_CL
tags: arXiv_CL Deep_Learning
author: Nan Du, Kai Chen, Anjuli Kannan, Linh Tran, Yuhui Chen, Izhak Shafran
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes novel models tailored for a new application, that of extracting the symptoms mentioned in clinical conversations along with their status. Lack of any publicly available corpus in this privacy-sensitive domain led us to develop our own corpus, consisting of about 3K conversations annotated by professional medical scribes. We propose two novel deep learning approaches to infer the symptom names and their status: (1) a new hierarchical span-attribute tagging (\SAT) model, trained using curriculum learning, and (2) a variant of sequence-to-sequence model which decodes the symptoms and their status from a few speaker turns within a sliding window over the conversation. This task stems from a realistic application of assisting medical providers in capturing symptoms mentioned by patients from their clinical conversations. To reflect this application, we define multiple metrics. From inter-rater agreement, we find that the task is inherently difficult. We conduct comprehensive evaluations on several contrasting conditions and observe that the performance of the models range from an F-score of 0.5 to 0.8 depending on the condition. Our analysis not only reveals the inherent challenges of the task, but also provides useful directions to improve the models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02239](http://arxiv.org/abs/1906.02239)

##### PDF
[http://arxiv.org/pdf/1906.02239](http://arxiv.org/pdf/1906.02239)

