---
layout: post
title: "Global and Local Sensitivity Guided Key Salient Object Re-augmentation for Video Saliency Detection"
date: 2018-11-19 03:27:23
categories: arXiv_CV
tags: arXiv_CV Salient Knowledge Deep_Learning Detection
author: Ziqi Zhou, Zheng Wang, Huchuan Lu, Song Wang, Meijun Sun
mathjax: true
---

* content
{:toc}

##### Abstract
The existing still-static deep learning based saliency researches do not consider the weighting and highlighting of extracted features from different layers, all features contribute equally to the final saliency decision-making. Such methods always evenly detect all "potentially significant regions" and unable to highlight the key salient object, resulting in detection failure of dynamic scenes. In this paper, based on the fact that salient areas in videos are relatively small and concentrated, we propose a \textbf{key salient object re-augmentation method (KSORA) using top-down semantic knowledge and bottom-up feature guidance} to improve detection accuracy in video scenes. KSORA includes two sub-modules (WFE and KOS): WFE processes local salient feature selection using bottom-up strategy, while KOS ranks each object in global fashion by top-down statistical knowledge, and chooses the most critical object area for local enhancement. The proposed KSORA can not only strengthen the saliency value of the local key salient object but also ensure global saliency consistency. Results on three benchmark datasets suggest that our model has the capability of improving the detection accuracy on complex scenes. The significant performance of KSORA, with a speed of 17FPS on modern GPUs, has been verified by comparisons with other ten state-of-the-art algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07480](http://arxiv.org/abs/1811.07480)

##### PDF
[http://arxiv.org/pdf/1811.07480](http://arxiv.org/pdf/1811.07480)

