---
layout: post
title: "Learning Conditional Random Fields with Augmented Observations for Partially Observed Action Recognition"
date: 2018-11-25 10:59:19
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Prediction Detection Recognition
author: Shih-Yao Lin, Yen-Yu Lin, Chu-Song Chen, Yi-Ping Hung
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims at recognizing partially observed human actions in videos. Action videos acquired in uncontrolled environments often contain corrupt frames, which make actions partially observed. Furthermore, these frames can last for arbitrary lengths of time and appear irregularly. They are inconsistent with training data and degrade the performance of pre-trained action recognition systems. We present an approach to address this issue. For each training and testing actions, we divide it into segments and explore the mutual dependency between temporal segments. This property states that the similarity of two actions at one segment often implies their similarity at another. We augment each segment with extra alternatives retrieved from training data. The augmentation algorithm is designed in a way where a few alternatives are good enough to replace the original segment where corrupt frames occur. Our approach is developed upon hidden conditional random fields and leverages the flexibility of hidden variables for uncertainty handling. It turns out that our approach integrates corrupt segment detection and alternative selection into the process of prediction, and can recognize partially observed actions more accurately. It is evaluated on both fully observed actions and partially observed ones with either synthetic or real corrupt frames. The experimental results manifest its general applicability and superior performance, especially when corrupt frames are present in the action videos.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.09986](https://arxiv.org/abs/1811.09986)

##### PDF
[https://arxiv.org/pdf/1811.09986](https://arxiv.org/pdf/1811.09986)

