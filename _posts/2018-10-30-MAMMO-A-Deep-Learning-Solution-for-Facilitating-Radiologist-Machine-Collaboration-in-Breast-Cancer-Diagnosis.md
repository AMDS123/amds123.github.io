---
layout: post
title: "MAMMO: A Deep Learning Solution for Facilitating Radiologist-Machine Collaboration in Breast Cancer Diagnosis"
date: 2018-10-30 10:45:53
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Prediction
author: Trent Kyono, Fiona J. Gilbert, Mihaela van der Schaar
mathjax: true
---

* content
{:toc}

##### Abstract
With an aging and growing population, the number of women requiring either screening or symptomatic mammograms is increasing. To reduce the number of mammograms that need to be read by a radiologist while keeping the diagnostic accuracy the same or better than current clinical practice, we develop Man and Machine Mammography Oracle (MAMMO) - a clinical decision support system capable of triaging mammograms into those that can be confidently classified by a machine and those that cannot be, thus requiring the reading of a radiologist. The first component of MAMMO is a novel multi-view convolutional neural network (CNN) with multi-task learning (MTL). MTL enables the CNN to learn the radiological assessments known to be associated with cancer, such as breast density, conspicuity, suspicion, etc., in addition to learning the primary task of cancer diagnosis. We show that MTL has two advantages: 1) learning refined feature representations associated with cancer improves the classification performance of the diagnosis task and 2) issuing radiological assessments provides an additional layer of model interpretability that a radiologist can use to debug and scrutinize the diagnoses provided by the CNN. The second component of MAMMO is a triage network, which takes as input the radiological assessment and diagnostic predictions of the first network's MTL outputs and determines which mammograms can be correctly and confidently diagnosed by the CNN and which mammograms cannot, thus needing to be read by a radiologist. Results obtained on a private dataset of 8,162 patients show that MAMMO reduced the number of radiologist readings by 42.8% while improving the overall diagnostic accuracy in comparison to readings done by radiologists alone. We analyze the triage of patients decided by MAMMO to gain a better understanding of what unique mammogram characteristics require radiologists' expertise.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02661](http://arxiv.org/abs/1811.02661)

##### PDF
[http://arxiv.org/pdf/1811.02661](http://arxiv.org/pdf/1811.02661)

