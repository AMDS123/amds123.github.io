---
layout: post
title: "Self-Supervised Learning of Depth and Camera Motion from 360° Videos"
date: 2018-11-13 14:07:27
categories: arXiv_CV
tags: arXiv_CV Face Drone Inference Prediction
author: Fu-En Wang, Hou-Ning Hu, Hsien-Tzu Cheng, Juan-Ting Lin, Shang-Ta Yang, Meng-Li Shih, Hung-Kuo Chu, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
As 360° cameras become prevalent in many autonomous systems (e.g., self-driving cars and drones), efficient 360° perception becomes more and more important. We propose a novel self-supervised learning approach for predicting the omnidirectional depth and camera motion from a 360° video. In particular, starting from the SfMLearner, which is designed for cameras with normal field-of-view, we introduce three key features to process 360° images efficiently. Firstly, we convert each image from equirectangular projection to cubic projection in order to avoid image distortion. In each network layer, we use Cube Padding (CP), which pads intermediate features from adjacent faces, to avoid image boundaries. Secondly, we propose a novel "spherical" photometric consistency constraint on the whole viewing sphere. In this way, no pixel will be projected outside the image boundary which typically happens in images with normal field-of-view. Finally, rather than naively estimating six independent camera motions (i.e., naively applying SfM-Learner to each face on a cube), we propose a novel camera pose consistency loss to ensure the estimated camera motions reaching consensus. To train and evaluate our approach, we collect a new PanoSUNCG dataset containing a large amount of 360° videos with groundtruth depth and camera motion. Our approach achieves state-of-the-art depth prediction and camera motion estimation on PanoSUNCG with faster inference speed comparing to equirectangular. In real-world indoor videos, our approach can also achieve qualitatively reasonable depth prediction by acquiring model pre-trained on PanoSUNCG.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.05304](https://arxiv.org/abs/1811.05304)

##### PDF
[https://arxiv.org/pdf/1811.05304](https://arxiv.org/pdf/1811.05304)

