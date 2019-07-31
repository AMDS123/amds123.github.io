---
layout: post
title: "Exploring large scale public medical image datasets"
date: 2019-07-30 03:09:27
categories: arXiv_CV
tags: arXiv_CV Review
author: Luke Oakden-Rayner
mathjax: true
---

* content
{:toc}

##### Abstract
Rationale and Objectives: Medical artificial intelligence systems are dependent on well characterised large scale datasets. Recently released public datasets have been of great interest to the field, but pose specific challenges due to the disconnect they cause between data generation and data usage, potentially limiting the utility of these datasets. 
 Materials and Methods: We visually explore two large public datasets, to determine how accurate the provided labels are and whether other subtle problems exist. The ChestXray14 dataset contains 112,120 frontal chest films, and the MURA dataset contains 40,561 upper limb radiographs. A subset of around 700 images from both datasets was reviewed by a board-certified radiologist, and the quality of the original labels was determined. 
 Results: The ChestXray14 labels did not accurately reflect the visual content of the images, with positive predictive values mostly between 10% and 30% lower than the values presented in the original documentation. There were other significant problems, with examples of hidden stratification and label disambiguation failure. The MURA labels were more accurate, but the original normal/abnormal labels were inaccurate for the subset of cases with degenerative joint disease, with a sensitivity of 60% and a specificity of 82%. 
 Conclusion: Visual inspection of images is a necessary component of understanding large image datasets. We recommend that teams producing public datasets should perform this important quality control procedure and include a thorough description of their findings, along with an explanation of the data generating procedures and labelling rules, in the documentation for their datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12720](http://arxiv.org/abs/1907.12720)

##### PDF
[http://arxiv.org/pdf/1907.12720](http://arxiv.org/pdf/1907.12720)

