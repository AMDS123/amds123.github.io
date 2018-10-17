---
layout: post
title: "Generating Self-Guided Dense Annotations for Weakly Supervised Semantic Segmentation"
date: 2018-10-16 14:49:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Semantic_Segmentation
author: Zi-Yi Ke, Chiou-Ting Hsu
mathjax: true
---

* content
{:toc}

##### Abstract
Learning semantic segmentation models under image-level supervision is far more challenging than under fully supervised setting. Without knowing the exact pixel-label correspondence, most weakly-supervised methods rely on external models to infer pseudo pixel-level labels for training semantic segmentation models. In this paper, we aim to develop a single neural network without resorting to any external models. We propose a novel self-guided strategy to fully utilize features learned across multiple levels to progressively generate the dense pseudo labels. First, we use high-level features as class-specific localization maps to roughly locate the classes. Next, we propose an affinity-guided method to encourage each localization map to be consistent with their intermediate level features. Third, we adopt the training image itself as guidance and propose a self-guided refinement to further transfer the image's inherent structure into the maps. Finally, we derive pseudo pixel-level labels from these localization maps and use the pseudo labels as ground truth to train the semantic segmentation model. Our proposed self-guided strategy is a unified framework, which is built on a single network and alternatively updates the feature representation and refines localization maps during the training procedure. Experimental results on PASCAL VOC 2012 segmentation benchmark demonstrate that our method outperforms other weakly-supervised methods under the same setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07050](http://arxiv.org/abs/1810.07050)

##### PDF
[http://arxiv.org/pdf/1810.07050](http://arxiv.org/pdf/1810.07050)

