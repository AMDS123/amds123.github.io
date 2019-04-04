---
layout: post
title: "Identifying disease-free chest X-ray images with deep transfer learning"
date: 2019-04-02 20:26:53
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Classification
author: Ken C. L. Wong, Mehdi Moradi, Joy Wu, Tanveer Syeda-Mahmood
mathjax: true
---

* content
{:toc}

##### Abstract
Chest X-rays (CXRs) are among the most commonly used medical image modalities. They are mostly used for screening, and an indication of disease typically results in subsequent tests. As this is mostly a screening test used to rule out chest abnormalities, the requesting clinicians are often interested in whether a CXR is normal or not. A machine learning algorithm that can accurately screen out even a small proportion of the "real normal" exams out of all requested CXRs would be highly beneficial in reducing the workload for radiologists. In this work, we report a deep neural network trained for classifying CXRs with the goal of identifying a large number of normal (disease-free) images without risking the discharge of sick patients. We use an ImageNet-pretrained Inception-ResNet-v2 model to provide the image features, which are further used to train a model on CXRs labelled by expert radiologists. The probability threshold for classification is optimized for 100% precision for the normal class, ensuring no sick patients are released. At this threshold we report an average recall of 50%. This means that the proposed solution has the potential to cut in half the number of disease-free CXRs examined by radiologists, without risking the discharge of sick patients.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.01654](https://arxiv.org/abs/1904.01654)

##### PDF
[https://arxiv.org/pdf/1904.01654](https://arxiv.org/pdf/1904.01654)

