---
layout: post
title: "Towards End-to-End Text Spotting in Natural Scenes"
date: 2019-06-14 04:20:55
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention CNN Detection Recognition
author: Hui Li, Peng Wang, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Text spotting in natural scene images is of great importance for many image understanding tasks. It includes two sub-tasks: text detection and recognition. In this work, we propose a unified network that simultaneously localizes and recognizes text with a single forward pass, avoiding intermediate processes such as image cropping and feature re-calculation, word separation, and character grouping. In contrast to existing approaches that consider text detection and recognition as two distinct tasks and tackle them one by one, the proposed framework settles these two tasks concurrently. The whole framework can be trained end-to-end and is able to handle text of arbitrary shapes. The convolutional features are calculated only once and shared by both detection and recognition modules. Through multi-task training, the learned features become more discriminate and improve the overall performance. By employing the $2$D attention model in word recognition, the irregularity of text can be robustly addressed. It provides the spatial location for each character, which not only helps local feature extraction in word recognition, but also indicates an orientation angle to refine text localization. Our proposed method has achieved state-of-the-art performance on several standard text spotting benchmarks, including both regular and irregular ones.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06013](https://arxiv.org/abs/1906.06013)

##### PDF
[https://arxiv.org/pdf/1906.06013](https://arxiv.org/pdf/1906.06013)

