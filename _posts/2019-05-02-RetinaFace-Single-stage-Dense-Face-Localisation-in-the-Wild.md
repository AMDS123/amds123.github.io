---
layout: post
title: "RetinaFace: Single-stage Dense Face Localisation in the Wild"
date: 2019-05-02 09:45:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Face_Detection
author: Jiankang Deng, Jia Guo, Yuxiang Zhou, Jinke Yu, Irene Kotsia, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
Though tremendous strides have been made in uncontrolled face detection, accurate and efficient face localisation in the wild remains an open challenge. This paper presents a robust single-stage face detector, named RetinaFace, which performs pixel-wise face localisation on various scales of faces by taking advantages of joint extra-supervised and self-supervised multi-task learning. Specifically, We make contributions in the following five aspects: (1) We manually annotate five facial landmarks on the WIDER FACE dataset and observe significant improvement in hard face detection with the assistance of this extra supervision signal. (2) We further add a self-supervised mesh decoder branch for predicting a pixel-wise 3D shape face information in parallel with the existing supervised branches. (3) On the WIDER FACE hard test set, RetinaFace outperforms the state of the art average precision (AP) by $1.1\%$ (achieving AP equal to {\bf $91.4\%$}). (4) On the IJB-C test set, RetinaFace enables state of the art methods (ArcFace) to improve their results in face verification (TAR=$89.59\%$ for FAR=1e-6). (5) By employing light-weight backbone networks, RetinaFace can run real-time on a single CPU core for a VGA-resolution image. Extra annotations and code will be released to facilitate future research.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00641](http://arxiv.org/abs/1905.00641)

##### PDF
[http://arxiv.org/pdf/1905.00641](http://arxiv.org/pdf/1905.00641)

