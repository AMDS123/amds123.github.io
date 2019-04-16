---
layout: post
title: "Video Captioning with Guidance of Multimodal Latent Topics"
date: 2017-09-02 15:34:44
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption Prediction
author: Shizhe Chen, Jia Chen, Qin Jin, Alexander Hauptmann
mathjax: true
---

* content
{:toc}

##### Abstract
The topic diversity of open-domain videos leads to various vocabularies and linguistic expressions in describing video contents, and therefore, makes the video captioning task even more challenging. In this paper, we propose an unified caption framework, M&M TGM, which mines multimodal topics in unsupervised fashion from data and guides the caption decoder with these topics. Compared to pre-defined topics, the mined multimodal topics are more semantically and visually coherent and can reflect the topic distribution of videos better. We formulate the topic-aware caption generation as a multi-task learning problem, in which we add a parallel task, topic prediction, in addition to the caption task. For the topic prediction task, we use the mined topics as the teacher to train a student topic prediction model, which learns to predict the latent topics from multimodal contents of videos. The topic prediction provides intermediate supervision to the learning process. As for the caption task, we propose a novel topic-aware decoder to generate more accurate and detailed video descriptions with the guidance from latent topics. The entire learning procedure is end-to-end and it optimizes both tasks simultaneously. The results from extensive experiments conducted on the MSR-VTT and Youtube2Text datasets demonstrate the effectiveness of our proposed model. M&M TGM not only outperforms prior state-of-the-art methods on multiple evaluation metrics and on both benchmark datasets, but also achieves better generalization ability.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.09667](https://arxiv.org/abs/1708.09667)

##### PDF
[https://arxiv.org/pdf/1708.09667](https://arxiv.org/pdf/1708.09667)

