---
layout: post
title: "Medical Multimodal Classifiers Under Scarce Data Condition"
date: 2019-02-24 03:38:41
categories: arXiv_CV
tags: arXiv_CV Embedding Transfer_Learning Classification Deep_Learning Detection
author: Faik Aydin, Maggie Zhang, Michelle Ananda-Rajah, Gholamreza Haffari
mathjax: true
---

* content
{:toc}

##### Abstract
Data is one of the essential ingredients to power deep learning research. Small datasets, especially specific to medical institutes, bring challenges to deep learning training stage. This work aims to develop a practical deep multimodal that can classify patients into abnormal and normal categories accurately as well as assist radiologists to detect visual and textual anomalies by locating areas of interest. The detection of the anomalies is achieved through a novel technique which extends the integrated gradients methodology with an unsupervised clustering algorithm. This technique also introduces a tuning parameter which trades off true positive signals to denoise false positive signals in the detection process. To overcome the challenges of the small training dataset which only has 3K frontal X-ray images and medical reports in pairs, we have adopted transfer learning for the multimodal which concatenates the layers of image and text submodels. The image submodel was trained on the vast ChestX-ray14 dataset, while the text submodel transferred a pertained word embedding layer from a hospital-specific corpus. Experimental results show that our multimodal improves the accuracy of the classification by 4% and 7% on average of 50 epochs, compared to the individual text and image model, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08888](http://arxiv.org/abs/1902.08888)

##### PDF
[http://arxiv.org/pdf/1902.08888](http://arxiv.org/pdf/1902.08888)

