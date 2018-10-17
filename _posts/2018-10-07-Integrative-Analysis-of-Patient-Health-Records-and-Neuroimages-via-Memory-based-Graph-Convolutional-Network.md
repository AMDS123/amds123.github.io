---
layout: post
title: "Integrative Analysis of Patient Health Records and Neuroimages via Memory-based Graph Convolutional Network"
date: 2018-10-07 14:02:12
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Xi Zhang, Jingyuan Chou, Fei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
With the arrival of the big data era, more and more data are becoming readily available in various real-world applications and those data are usually highly heterogeneous. Taking computational medicine as an example, we have both Electronic Health Records (EHR) and medical images for each patient. For complicated diseases such as Parkinson's and Alzheimer's, both EHR and neuroimaging information are very important for disease understanding because they contain complementary aspects of the disease. However, EHR and neuroimage are completely different. So far the existing research has been mainly focusing on one of them. In this paper, we proposed a framework, Memory-Based Graph Convolution Network (MemGCN), to perform integrative analysis with such multi-modal data. Specifically, GCN is used to extract useful information from the patients' neuroimages. The information contained in the patient EHRs before the acquisition of each brain image is captured by a memory network because of its sequential nature. The information contained in each brain image is combined with the information read out from the memory network to infer the disease state at the image acquisition timestamp. To further enhance the analytical power of MemGCN, we also designed a multi-hop strategy that allows multiple reading and updating on the memory can be performed at each iteration. We conduct experiments using the patient data from the Parkinson's Progression Markers Initiative (PPMI) with the task of classification of Parkinson's Disease (PD) cases versus controls. We demonstrate that superior classification performance can be achieved with our proposed framework, comparing with existing approaches involving a single type of data.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.06018](https://arxiv.org/abs/1809.06018)

##### PDF
[https://arxiv.org/pdf/1809.06018](https://arxiv.org/pdf/1809.06018)

