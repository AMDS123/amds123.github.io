---
layout: post
title: "Reinforcement Learning-based Automatic Diagnosis of Acute Appendicitis in Abdominal CT"
date: 2019-09-02 09:19:33
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning CNN Classification
author: Walid Abdullah Al, Il Dong Yun, Kyong Joon Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Acute appendicitis characterized by a painful inflammation of the vermiform appendix is one of the most common surgical emergencies. Localizing the appendix is challenging due to its unclear anatomy amidst the complex colon-structure as observed in the conventional CT views, resulting in a time-consuming diagnosis. End-to-end learning of a convolutional neural network (CNN) is also not likely to be useful because of the negligible size of the appendix compared with the abdominal CT volume. With no prior computational approaches to the best of our knowledge, we propose the first computerized automation for acute appendicitis diagnosis. In our approach, we utilize a reinforcement learning agent deployed in the lower abdominal region to obtain the appendix location first to reduce the search space for diagnosis. Then, we obtain the classification scores (i.e., the likelihood of acute appendicitis) for the local neighborhood around the localized position, using a CNN trained only on a small appendix patch per volume. From the spatial representation of the resultant scores, we finally define a region of low-entropy (RLE) to choose the optimal diagnosis score, which helps improve the classification accuracy showing robustness even under high appendix localization error cases. In our experiment with 319 abdominal CT volumes, the proposed RLE-based decision with prior localization showed significant improvement over the standard CNN-based diagnosis approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00617](http://arxiv.org/abs/1909.00617)

##### PDF
[http://arxiv.org/pdf/1909.00617](http://arxiv.org/pdf/1909.00617)

