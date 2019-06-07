---
layout: post
title: "Generative Model-Based Ischemic Stroke Lesion Segmentation"
date: 2019-06-06 03:25:11
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Tao Song
mathjax: true
---

* content
{:toc}

##### Abstract
CT perfusion (CTP) has been used to triage ischemic stroke patients in the early stage, because of its speed, availability, and lack of contraindications. Perfusion parameters including cerebral blood volume (CBV), cerebral blood flow (CBF), mean transit time (MTT) and time of peak (Tmax) could also be computed from CTP data. However, CTP data or the perfusion parameters, are ambiguous to locate the infarct core or tissue at risk (penumbra), which is normally confirmed by the follow-up Diffusion Weighted Imaging (DWI) or perfusion diffusion mismatch. In this paper, we propose a novel generative modelbased segmentation framework composed of an extractor, a generator and a segmentor for ischemic stroke lesion segmentation. First, an extractor is used to directly extract the representative feature images from the CTP feature images. Second, a generator is used to generate the clinical relevant DWI images using the output from the extractor and perfusion parameters. Finally, the segmentor is used to precisely segment the ischemic stroke lesion using the generated DWI from the generator. Meanwhile, a novel pixel-region loss function, generalized dice combined with weighted cross entropy, is used to handle data unbalance problem which is commonly encountered in medical image segmentation. All networks are trained end-to-end from scratch using the 2018 Ischemic Stroke Lesion Segmentation Challenge (ISLES) dataset and our method won the first place in the 2018 ischemic stroke lesions segmentation challenge in the test stage.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02392](http://arxiv.org/abs/1906.02392)

##### PDF
[http://arxiv.org/pdf/1906.02392](http://arxiv.org/pdf/1906.02392)

