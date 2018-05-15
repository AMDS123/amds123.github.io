---
layout: post
title: "I Have Seen Enough: A Teacher Student Network for Video Classification Using Fewer Frames"
date: 2018-05-12 06:22:54
categories: arXiv_CV
tags: arXiv_CV Attention Summarization Video_Classification Inference Classification
author: Shweta Bhardwaj, Mitesh M. Khapra
mathjax: true
---

* content
{:toc}

##### Abstract
Over the past few years, various tasks involving videos such as classification, description, summarization and question answering have received a lot of attention. Current models for these tasks compute an encoding of the video by treating it as a sequence of images and going over every image in the sequence. However, for longer videos this is very time consuming. In this paper, we focus on the task of video classification and aim to reduce the computational time by using the idea of distillation. Specifically, we first train a teacher network which looks at all the frames in a video and computes a representation for the video. We then train a student network whose objective is to process only a small fraction of the frames in the video and still produce a representation which is very close to the representation computed by the teacher network. This smaller student network involving fewer computations can then be employed at inference time for video classification. We experiment with the YouTube-8M dataset and show that the proposed student network can reduce the inference time by upto 30% with a very small drop in the performance

##### Abstract (translated by Google)
在过去的几年里，涉及视频的各种任务，如分类，描述，总结和问题回答都受到了很多关注。当前的这些任务模型通过将视频编码为一系列图像并遍历序列中的每个图像来计算视频的编码。但是，对于较长的视频，这非常耗时。在本文中，我们着重于视频分类的任务，旨在通过使用蒸馏的思想来缩短计算时间。具体而言，我们首先训练一个教师网络，该网络查看视频中的所有帧并计算视频的表示。然后，我们训练一个学生网络，其目标是只处理视频中的一小部分帧，并仍然产生一个非常接近教师网络计算表示的表示。这个较小的学生网络涉及较少的计算，然后可以用于视频分类的推理时间。我们对YouTube-8M数据集进行了实验，结果表明，建议的学生网络可以将推断时间减少多达30％，并且性能下降很小

##### URL
[https://arxiv.org/abs/1805.04668](https://arxiv.org/abs/1805.04668)

##### PDF
[https://arxiv.org/pdf/1805.04668](https://arxiv.org/pdf/1805.04668)

