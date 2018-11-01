---
layout: post
title: "R$^3$SGM: Real-time Raster-Respecting Semi-Global Matching for Power-Constrained Systems"
date: 2018-10-30 20:10:02
categories: arXiv_CV
tags: arXiv_CV Semi_Global
author: Oscar Rahnama, Tommaso Cavallari, Stuart Golodetz, Simon Walker, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Stereo depth estimation is used for many computer vision applications. Though many popular methods strive solely for depth quality, for real-time mobile applications (e.g. prosthetic glasses or micro-UAVs), speed and power efficiency are equally, if not more, important. Many real-world systems rely on Semi-Global Matching (SGM) to achieve a good accuracy vs. speed balance, but power efficiency is hard to achieve with conventional hardware, making the use of embedded devices such as FPGAs attractive for low-power applications. However, the full SGM algorithm is ill-suited to deployment on FPGAs, and so most FPGA variants of it are partial, at the expense of accuracy. In a non-FPGA context, the accuracy of SGM has been improved by More Global Matching (MGM), which also helps tackle the streaking artifacts that afflict SGM. In this paper, we propose a novel, resource-efficient method that is inspired by MGM's techniques for improving depth quality, but which can be implemented to run in real time on a low-power FPGA. Through evaluation on multiple datasets (KITTI and Middlebury), we show that in comparison to other real-time capable stereo approaches, we can achieve a state-of-the-art balance between accuracy, power efficiency and speed, making our approach highly desirable for use in real-time systems with limited power.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12988](http://arxiv.org/abs/1810.12988)

##### PDF
[http://arxiv.org/pdf/1810.12988](http://arxiv.org/pdf/1810.12988)

