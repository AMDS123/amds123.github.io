---
layout: post
title: "Believe It or Not, We Know What You Are Looking at!"
date: 2019-07-04 12:29:06
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Dongze Lian, Zehao Yu, Shenghua Gao
mathjax: true
---

* content
{:toc}

##### Abstract
By borrowing the wisdom of human in gaze following, we propose a two-stage solution for gaze point prediction of the target persons in a scene. Specifically, in the first stage, both head image and its position are fed into a gaze direction pathway to predict the gaze direction, and then multi-scale gaze direction fields are generated to characterize the distribution of gaze points without considering the scene contents. In the second stage, the multi-scale gaze direction fields are concatenated with the image contents and fed into a heatmap pathway for heatmap regression. There are two merits for our two-stage solution based gaze following: i) our solution mimics the behavior of human in gaze following, therefore it is more psychological plausible; ii) besides using heatmap to supervise the output of our network, we can also leverage gaze direction to facilitate the training of gaze direction pathway, therefore our network can be more robustly trained. Considering that existing gaze following dataset is annotated by the third-view persons, we build a video gaze following dataset, where the ground truth is annotated by the observers in the videos. Therefore it is more reliable. The evaluation with such a dataset reflects the capacity of different methods in real scenarios better. Extensive experiments on both datasets show that our method significantly outperforms existing methods, which validates the effectiveness of our solution for gaze following. Our dataset and codes are released in https://github.com/svip-lab/GazeFollowing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02364](http://arxiv.org/abs/1907.02364)

##### PDF
[http://arxiv.org/pdf/1907.02364](http://arxiv.org/pdf/1907.02364)

