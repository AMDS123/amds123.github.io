---
layout: post
title: "CollaboNet: collaboration of deep neural networks for biomedical named entity recognition"
date: 2019-05-29 16:34:50
categories: arXiv_CL
tags: arXiv_CL Relation_Extraction Classification Deep_Learning Relation Recognition
author: Wonjin Yoon, Chan Ho So, Jinhyuk Lee, Jaewoo Kang
mathjax: true
---

* content
{:toc}

##### Abstract
Background: Finding biomedical named entities is one of the most essential tasks in biomedical text mining. Recently, deep learning-based approaches have been applied to biomedical named entity recognition (BioNER) and showed promising results. However, as deep learning approaches need an abundant amount of training data, a lack of data can hinder performance. BioNER datasets are scarce resources and each dataset covers only a small subset of entity types. Furthermore, many bio entities are polysemous, which is one of the major obstacles in named entity recognition. Results: To address the lack of data and the entity type misclassification problem, we propose CollaboNet which utilizes a combination of multiple NER models. In CollaboNet, models trained on a different dataset are connected to each other so that a target model obtains information from other collaborator models to reduce false positives. Every model is an expert on their target entity type and takes turns serving as a target and a collaborator model during training time. The experimental results show that CollaboNet can be used to greatly reduce the number of false positives and misclassified entities including polysemous words. CollaboNet achieved state-of-the-art performance in terms of precision, recall and F1 score. Conclusions: We demonstrated the benefits of combining multiple models for BioNER. Our model has successfully reduced the number of misclassified entities and improved the performance by leveraging multiple datasets annotated for different entity types. Given the state-of-the-art performance of our model, we believe that CollaboNet can improve the accuracy of downstream biomedical text mining applications such as bio-entity relation extraction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.07950](http://arxiv.org/abs/1809.07950)

##### PDF
[http://arxiv.org/pdf/1809.07950](http://arxiv.org/pdf/1809.07950)

