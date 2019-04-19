---
layout: post
title: "Constructing Bias on Skin Lesion Datasets"
date: 2019-04-18 14:49:23
categories: arXiv_CV
tags: arXiv_CV Detection Relation
author: Alceu Bissoto, Michel Fornaciali, Eduardo Valle, Sandra Avila
mathjax: true
---

* content
{:toc}

##### Abstract
Melanoma is the deadliest form of skin cancer. Automated skin lesion analysis plays an important role for early detection. Nowadays, the ISIC Archive and the Atlas of Dermoscopy dataset are the most employed skin lesion sources to benchmark deep-learning based tools. However, all datasets contain biases, often unintentional, due to how they were acquired and annotated. Those biases distort the performance of machine-learning models, creating spurious correlations that the models can unfairly exploit, or, contrarily destroying cogent correlations that the models could learn. In this paper, we propose a set of experiments that reveal both types of biases, positive and negative, in existing skin lesion datasets. Our results show that models can correctly classify skin lesion images without clinically-meaningful information: disturbingly, the machine-learning model learned over images where no information about the lesion remains, presents an accuracy above the AI benchmark curated with dermatologists' performances. That strongly suggests spurious correlations guiding the models. We fed models with additional clinically meaningful information, which failed to improve the results even slightly, suggesting the destruction of cogent correlations. Our main findings raise awareness of the limitations of models trained and evaluated in small datasets such as the ones we evaluated, and may suggest future guidelines for models intended for real-world deployment.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08818](http://arxiv.org/abs/1904.08818)

##### PDF
[http://arxiv.org/pdf/1904.08818](http://arxiv.org/pdf/1904.08818)

