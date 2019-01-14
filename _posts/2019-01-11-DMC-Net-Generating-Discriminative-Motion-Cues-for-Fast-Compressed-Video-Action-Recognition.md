---
layout: post
title: "DMC-Net: Generating Discriminative Motion Cues for Fast Compressed Video Action Recognition"
date: 2019-01-11 02:39:41
categories: arXiv_CV
tags: arXiv_CV Adversarial Video_Caption Action_Recognition Inference Classification Recognition
author: Zheng Shou, Zhicheng Yan, Yannis Kalantidis, Laura Sevilla-Lara, Marcus Rohrbach, Xudong Lin, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Motion has shown to be useful for video understanding, where motion is typically represented by optical flow. However, computing flow from video frames is very time-consuming. Recent works directly leverage the motion vectors and residuals readily available in the compressed video to represent motion at no cost. While this avoids flow computation, it also hurts accuracy since the motion vector is noisy and has substantially reduced resolution, which makes it a less discriminative motion representation. To remedy these issues, we propose a lightweight generator network, which reduces noises in motion vectors and captures fine motion details, achieving a more Discriminative Motion Cue (DMC) representation. Since optical flow is a more accurate motion representation, we train the DMC generator to approximate flow using a reconstruction loss and a generative adversarial loss, jointly with the downstream action classification task. Extensive evaluations on three action recognition benchmarks (HMDB-51, UCF-101, and a subset of Kinetics) confirm the effectiveness of our method. Our full system, consisting of the generator and the classifier, is coined as DMC-Net which obtains high accuracy close to that of using flow and runs two orders of magnitude faster than using optical flow at inference time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03460](http://arxiv.org/abs/1901.03460)

##### PDF
[http://arxiv.org/pdf/1901.03460](http://arxiv.org/pdf/1901.03460)

