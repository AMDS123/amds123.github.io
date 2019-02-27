---
layout: post
title: "MFQE 2.0: A New Approach for Multi-frame Quality Enhancement on Compressed Video"
date: 2019-02-26 02:35:55
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN RNN Deep_Learning Detection
author: Zhenyu Guan, Qunliang Xing, Mai Xu, Ren Yang, Tie Liu, Zulin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The past few years have witnessed great success in applying deep learning to enhance the quality of compressed image/video. The existing approaches mainly focus on enhancing the quality of a single frame, not considering the similarity between consecutive frames. Since heavy fluctuation exists across compressed video frames as investigated in this paper, frame similarity can be utilized for quality enhancement of low-quality frames by using their neighboring high-quality frames. This task can be seen as Multi-Frame Quality Enhancement (MFQE). Accordingly, this paper proposes an MFQE approach for compressed video, as the first attempt in this direction. In our approach, we firstly develop a Bidirectional Long Short-Term Memory (BiLSTM) based detector to locate Peak Quality Frames (PQFs) in compressed video. Then, a novel Multi-Frame Convolutional Neural Network (MF-CNN) is designed to enhance the quality of compressed video, in which the non-PQF and its nearest two PQFs are the input. In MF-CNN, motion between the non-PQF and PQFs is compensated by a motion compensation subnet. Subsequently, a quality enhancement subnet fuses the non-PQF and compensated PQFs, and then reduces the compression artifacts of the non-PQF. Finally, experiments validate the effectiveness and generalization ability of our MFQE approach in advancing the state-of-the-art quality enhancement of compressed video. The code of our MFQE approach is available at https://github.com/RyanXingQL/MFQE2.0.git.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09707](http://arxiv.org/abs/1902.09707)

##### PDF
[http://arxiv.org/pdf/1902.09707](http://arxiv.org/pdf/1902.09707)

