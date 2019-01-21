---
layout: post
title: "Instance-Level Microtubule Segmentation Using Recurrent Attention"
date: 2019-01-17 21:00:54
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Deep_Learning
author: Samira Masoudi, Afsaneh Razi, Cameron H.G. Wright, Jay C. Gatlin, Ulas Bagci
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new deep learning algorithm for multiple microtubule (MT) segmentation in time-lapse images using the recurrent attention. Segmentation results from each pair of succeeding frames are being fed into a Hungarian algorithm to assign correspondences among MTs to generate a distinct path through the frames. Based on the obtained trajectories, we calculate MT velocities. Results of this work is expected to help biologists to characterize MT behaviors as well as their potential interactions. To validate our technique, we first use the statistics derived from the real time-lapse series of MT gliding assays to produce a large set of simulated data. We employ this dataset to train our network and optimize its hyperparameters. Then, we utilize the trained model to initialize the network while learning about the real data. Our experimental results show that the proposed algorithm improves the precision for MT instance velocity estimation to 71.3% from the baseline result (29.3%). We also demonstrate how the injection of temporal information into our network can reduce the false negative rates from 67.8% (baseline) down to 28.7% (proposed).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06006](http://arxiv.org/abs/1901.06006)

##### PDF
[http://arxiv.org/pdf/1901.06006](http://arxiv.org/pdf/1901.06006)

