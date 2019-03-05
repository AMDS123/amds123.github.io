---
layout: post
title: "Sdf-GAN: Semi-supervised Depth Fusion with Multi-scale Adversarial Networks"
date: 2019-03-02 12:38:12
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Relation
author: Can Pu, Runzi Song, Radim Tylecek, Nanbo Li, Robert B Fisher
mathjax: true
---

* content
{:toc}

##### Abstract
Refining raw disparity maps from different algorithms to exploit their complementary advantages is still challenging. Uncertainty estimation and complex disparity relationships among pixels limit the accuracy and robustness of existing methods and there is no standard method for fusion of different kinds of depth data. In this paper, we introduce a new method to fuse disparity maps from different sources, while incorporating supplementary information (intensity, gradient, etc.) into a refiner network to better refine raw disparity inputs. A discriminator network classifies disparities at different receptive fields and scales. Assuming a Markov Random Field for the refined disparity map produces better estimates of the true disparity distribution. Both fully supervised and semi-supervised versions of the algorithm are proposed. The approach includes a more robust loss function to inpaint invalid disparity values and requires much less labeled data to train in the semi-supervised learning mode. The algorithm can be generalized to fuse depths from different kinds of depth sources. Experiments explored different fusion opportunities: stereo-monocular fusion, stereo-ToF fusion and stereo-stereo fusion. The experiments show the superiority of the proposed algorithm compared with the most recent algorithms on public synthetic datasets (Scene Flow, SYNTH3, our synthetic garden dataset) and real datasets (Kitti2015 dataset and Trimbot2020 Garden dataset).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.06657](http://arxiv.org/abs/1803.06657)

##### PDF
[http://arxiv.org/pdf/1803.06657](http://arxiv.org/pdf/1803.06657)

