---
layout: post
title: "Deep Neural Networks for ECG-free Cardiac Phase and End-Diastolic Frame Detection on Coronary Angiographies"
date: 2018-11-07 08:23:59
categories: arXiv_CV
tags: arXiv_CV Prediction Detection
author: Costin Ciusdel, Alexandru Turcea, Andrei Puiu, Lucian Itu, Lucian Calmac, Emma Weiss, Cornelia Margineanu, Elisabeta Badila, Martin Berger, Thomas Redel, Tiziano Passerini, Mehmet Gulsun, Puneet Sharma
mathjax: true
---

* content
{:toc}

##### Abstract
Invasive coronary angiography (ICA) is the gold standard in Coronary Artery Disease (CAD) imaging. Detection of the end-diastolic frame (EDF) and, in general, cardiac phase detection on each temporal frame of a coronary angiography acquisition is of significant importance for the anatomical and non-invasive functional assessment of CAD. This task is generally performed via manual frame selection or semi-automated selection based on simultaneously acquired ECG signals - thus introducing the requirement of simultaneous ECG recordings. We evaluate the performance of a purely image based workflow based on deep neural networks for fully automated cardiac phase and EDF detection on coronary angiographies. A first deep neural network (DNN), trained to detect coronary arteries, is employed to preselect a subset of frames in which coronary arteries are well visible. A second DNN predicts cardiac phase labels for each frame. Only in the training and evaluation phases for the second DNN, ECG signals are used to provide ground truth labels for each angiographic frame. The networks were trained on 17800 coronary angiographies from 3900 patients and evaluated on 27900 coronary angiographies from 6250 patients. No exclusion criteria related to patient state, previous interventions, or pathology were formulated. Cardiac phase detection had an accuracy of 97.6%, a sensitivity of 97.6% and a specificity of 97.5% on the evaluation set. EDF prediction had a precision of 97.4% and a recall of 96.9%. Several sub-group analyses were performed, indicating that the cardiac phase detection performance is largely independent from acquisition angles and the heart rate of the patient. The average execution time of cardiac phase detection for one angiographic series was on average less than five seconds on a standard workstation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02797](http://arxiv.org/abs/1811.02797)

##### PDF
[http://arxiv.org/pdf/1811.02797](http://arxiv.org/pdf/1811.02797)

