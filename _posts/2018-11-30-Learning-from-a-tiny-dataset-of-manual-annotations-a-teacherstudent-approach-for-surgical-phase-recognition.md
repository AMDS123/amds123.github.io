---
layout: post
title: "Learning from a tiny dataset of manual annotations: a teacher/student approach for surgical phase recognition"
date: 2018-11-30 19:50:05
categories: arXiv_CV
tags: arXiv_CV Inference RNN Prediction Recognition
author: Tong Yu, Didier Mutter, Jacques Marescaux, Nicolas Padoy
mathjax: true
---

* content
{:toc}

##### Abstract
Vision algorithms capable of interpreting scenes from a real-time video stream are necessary for computer-assisted surgery systems to achieve context-aware behavior. In laparoscopic procedures one particular algorithm needed for such systems is the identification of surgical phases, for which the current state of the art is a model based on a CNN-LSTM. A number of previous works using models of this kind have trained them in a fully supervised manner, requiring a fully annotated dataset. Instead, our work confronts the problem of learning surgical phase recognition in scenarios presenting scarce amounts of annotated data (under 25% of all available video recordings). We propose a teacher/student type of approach, where a strong predictor called the teacher, trained beforehand on a small dataset of ground truth-annotated videos, generates synthetic annotations for a larger dataset, which another model - the student - learns from. In our case, the teacher features a novel CNN-biLSTM-CRF architecture, designed for offline inference only. The student, on the other hand, is a CNN-LSTM capable of making real-time predictions. Results for various amounts of manually annotated videos demonstrate the superiority of the new CNN-biLSTM-CRF predictor as well as improved performance from the CNN-LSTM trained using synthetic labels generated for unannotated videos. For both offline and online surgical phase recognition with very few annotated recordings available, this new teacher/student strategy provides a valuable performance improvement by efficiently leveraging the unannotated data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00033](http://arxiv.org/abs/1812.00033)

##### PDF
[http://arxiv.org/pdf/1812.00033](http://arxiv.org/pdf/1812.00033)

