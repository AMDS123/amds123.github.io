---
layout: post
title: "Deep Learning Predicts Hip Fracture using Confounding Patient and Healthcare Variables"
date: 2018-11-08 22:23:07
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction
author: Marcus A. Badgeley, John R. Zech, Luke Oakden-Rayner, Benjamin S. Glicksberg, Manway Liu, William Gale, Michael V. McConnell, Beth Percha, Thomas M. Snyder, Joel T. Dudley
mathjax: true
---

* content
{:toc}

##### Abstract
Hip fractures are a leading cause of death and disability among older adults. Hip fractures are also the most commonly missed diagnosis on pelvic radiographs. Computer-Aided Diagnosis (CAD) algorithms have shown promise for helping radiologists detect fractures, but the image features underpinning their predictions are notoriously difficult to understand. In this study, we trained deep learning models on 17,587 radiographs to classify fracture, five patient traits, and 14 hospital process variables. All 20 variables could be predicted from a radiograph (p &lt; 0.05), with the best performances on scanner model (AUC=1.00), scanner brand (AUC=0.98), and whether the order was marked "priority" (AUC=0.79). Fracture was predicted moderately well from the image (AUC=0.78) and better when combining image features with patient data (AUC=0.86, p=2e-9) or patient data plus hospital process features (AUC=0.91, p=1e-21). The model performance on a test set with matched patient variables was significantly lower than a random test set (AUC=0.67, p=0.003); and when the test set was matched on patient and image acquisition variables, the model performed randomly (AUC=0.52, 95% CI 0.46-0.58), indicating that these variables were the main source of the model's predictive ability overall. We also used Naive Bayes to combine evidence from image models with patient and hospital data and found their inclusion improved performance, but that this approach was nevertheless inferior to directly modeling all variables. If CAD algorithms are inexplicably leveraging patient and process variables in their predictions, it is unclear how radiologists should interpret their predictions in the context of other known patient data. Further research is needed to illuminate deep learning decision processes so that computers and clinicians can effectively cooperate.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03695](http://arxiv.org/abs/1811.03695)

##### PDF
[http://arxiv.org/pdf/1811.03695](http://arxiv.org/pdf/1811.03695)

