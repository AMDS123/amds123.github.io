---
layout: post
title: "Learning joint lesion and tissue segmentation from task-specific hetero-modal datasets"
date: 2019-07-07 18:09:43
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Reuben Dorent, Wenqi Li, Jinendra Ekanayake, Sebastien Ourselin, Tom Vercauteren
mathjax: true
---

* content
{:toc}

##### Abstract
Brain tissue segmentation from multimodal MRI is a key building block of many neuroscience analysis pipelines. It could also play an important role in many clinical imaging scenarios. Established tissue segmentation approaches have however not been developed to cope with large anatomical changes resulting from pathology. The effect of the presence of brain lesions, for example, on their performance is thus currently uncontrolled and practically unpredictable. Contrastingly, with the advent of deep neural networks (DNNs), segmentation of brain lesions has matured significantly and is achieving performance levels making it of interest for clinical use. However, few existing approaches allow for jointly segmenting normal tissue and brain lesions. Developing a DNN for such joint task is currently hampered by the fact that annotated datasets typically address only one specific task and rely on a task-specific hetero-modal imaging protocol. In this work, we propose a novel approach to build a joint tissue and lesion segmentation model from task-specific hetero-modal and partially annotated datasets. Starting from a variational formulation of the joint problem, we show how the expected risk can be decomposed and optimised empirically. We exploit an upper-bound of the risk to deal with missing imaging modalities. For each task, our approach reaches comparable performance than task-specific and fully-supervised models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03327](http://arxiv.org/abs/1907.03327)

##### PDF
[http://arxiv.org/pdf/1907.03327](http://arxiv.org/pdf/1907.03327)

