---
layout: post
title: "Deceiving Google's Cloud Video Intelligence API Built for Summarizing Videos"
date: 2017-03-31 05:25:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Image_Classification Classification
author: Hossein Hosseini, Baicen Xiao, Radha Poovendran
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the rapid progress of the techniques for image classification, video annotation has remained a challenging task. Automated video annotation would be a breakthrough technology, enabling users to search within the videos. Recently, Google introduced the Cloud Video Intelligence API for video analysis. As per the website, the system can be used to "separate signal from noise, by retrieving relevant information at the video, shot or per frame" level. A demonstration website has been also launched, which allows anyone to select a video for annotation. The API then detects the video labels (objects within the video) as well as shot labels (description of the video events over time). In this paper, we examine the usability of the Google's Cloud Video Intelligence API in adversarial environments. In particular, we investigate whether an adversary can subtly manipulate a video in such a way that the API will return only the adversary-desired labels. For this, we select an image, which is different from the video content, and insert it, periodically and at a very low rate, into the video. We found that if we insert one image every two seconds, the API is deceived into annotating the video as if it only contained the inserted image. Note that the modification to the video is hardly noticeable as, for instance, for a typical frame rate of 25, we insert only one image per 50 video frames. We also found that, by inserting one image per second, all the shot labels returned by the API are related to the inserted image. We perform the experiments on the sample videos provided by the API demonstration website and show that our attack is successful with different videos and images.

##### Abstract (translated by Google)
尽管图像分类技术的快速发展，视频注释仍然是一个具有挑战性的任务。自动视频注释将是一项突破性的技术，使用户能够在视频内进行搜索。最近，Google推出了用于视频分析的Cloud Video Intelligence API。根据该网站，该系统可用于“通过检索视频，镜头或每帧的相关信息”来分离信号与噪声。示范网站也已经启动，允许任何人选择一个视频进行注释。 API然后检测视频标签（视频内的对象）以及镜头标签（随着时间的推移描述视频事件）。在本文中，我们考察了Google的Cloud Video Intelligence API在对抗环境中的可用性。特别是，我们调查对手是否可以巧妙地操纵视频，使得API只返回敌手所需的标签。为此，我们选择一个与视频内容不同的图像，并定期以非常低的速率将其插入到视频中。我们发现，如果我们每两秒钟插入一张图片，那么API就会被欺骗，将视频注释为只包含插入的图片。请注意，对视频的修改几乎不可察觉，例如，对于典型的25帧的帧速率，我们每50个视频帧只插入一个图像。我们还发现，通过每秒插入一个图像，API返回的所有镜头标签都与插入的图像相关。我们对API演示网站提供的示例视频进行实验，并用不同的视频和图像显示我们的攻击是成功的。

##### URL
[https://arxiv.org/abs/1703.09793](https://arxiv.org/abs/1703.09793)

##### PDF
[https://arxiv.org/pdf/1703.09793](https://arxiv.org/pdf/1703.09793)

