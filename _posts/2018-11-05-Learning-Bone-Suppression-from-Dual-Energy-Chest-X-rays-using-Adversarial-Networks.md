---
layout: post
title: "Learning Bone Suppression from Dual Energy Chest X-rays using Adversarial Networks"
date: 2018-11-05 01:01:31
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Dong Yul Oh, Il Dong Yun
mathjax: true
---

* content
{:toc}

##### Abstract
Suppressing bones on chest X-rays such as ribs and clavicle is often expected to improve pathologies classification. These bones can interfere with a broad range of diagnostic tasks on pulmonary disease except for musculoskeletal system. Current conventional method for acquisition of bone suppressed X-rays is dual energy imaging, which captures two radiographs at a very short interval with different energy levels; however, the patient is exposed to radiation twice and the artifacts arise due to heartbeats between two shots. In this paper, we introduce a deep generative model trained to predict bone suppressed images on single energy chest X-rays, analyzing a finite set of previously acquired dual energy chest X-rays. Since the relatively small amount of data is available, such approach relies on the methodology maximizing the data utilization. Here we integrate the following two approaches. First, we use a conditional generative adversarial network that complements the traditional regression method minimizing the pairwise image difference. Second, we use Haar 2D wavelet decomposition to offer a perceptual guideline in frequency details to allow the model to converge quickly and efficiently. As a result, we achieve state-of-the-art performance on bone suppression as compared to the existing approaches with dual energy chest X-rays.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02628](http://arxiv.org/abs/1811.02628)

##### PDF
[http://arxiv.org/pdf/1811.02628](http://arxiv.org/pdf/1811.02628)

