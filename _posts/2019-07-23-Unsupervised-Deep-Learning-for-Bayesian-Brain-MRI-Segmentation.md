---
layout: post
title: "Unsupervised Deep Learning for Bayesian Brain MRI Segmentation"
date: 2019-07-23 17:26:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning
author: Adrian V. Dalca, Evan Yu, Polina Golland, Bruce Fischl, Mert R. Sabuncu, Juan Eugenio Iglesias
mathjax: true
---

* content
{:toc}

##### Abstract
Probabilistic atlas priors have been commonly used to derive adaptive and robust brain MRI segmentation algorithms. Widely-used neuroimage analysis pipelines rely heavily on these techniques, which are often computationally expensive. In contrast, there has been a recent surge of approaches that leverage deep learning to implement segmentation tools that are computationally efficient at test time. However, most of these strategies rely on learning from manually annotated images. These supervised deep learning methods are therefore sensitive to the intensity profiles in the training dataset. To develop a deep learning-based segmentation model for a new image dataset (e.g., of different contrast), one usually needs to create a new labeled training dataset, which can be prohibitively expensive, or rely on suboptimal ad hoc adaptation or augmentation approaches. In this paper, we propose an alternative strategy that combines a conventional probabilistic atlas-based segmentation with deep learning, enabling one to train a segmentation model for new MRI scans without the need for any manually segmented images. Our experiments include thousands of brain MRI scans and demonstrate that the proposed method achieves good accuracy for a brain MRI segmentation task for different MRI contrasts, requiring only approximately 15 seconds at test time on a GPU. The code is freely available at <a href="http://voxelmorph.mit.edu.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11319](http://arxiv.org/abs/1904.11319)

##### PDF
[http://arxiv.org/pdf/1904.11319](http://arxiv.org/pdf/1904.11319)

