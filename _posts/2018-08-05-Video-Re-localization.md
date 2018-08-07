---
layout: post
title: "Video Re-localization"
date: 2018-08-05 07:52:33
categories: arXiv_CV
tags: arXiv_CV GAN Classification Prediction Detection
author: Yang Feng, Lin Ma, Wei Liu, Tong Zhang, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Many methods have been developed to help people find the video contents they want efficiently. However, there are still some unsolved problems in this area. For example, given a query video and a reference video, how to accurately localize a segment in the reference video such that the segment semantically corresponds to the query video? We define a distinctively new task, namely \textbf{video re-localization}, to address this scenario. Video re-localization is an important emerging technology implicating many applications, such as fast seeking in videos, video copy detection, video surveillance, etc. Meanwhile, it is also a challenging research task because the visual appearance of a semantic concept in videos can have large variations. The first hurdle to clear for the video re-localization task is the lack of existing datasets. It is labor expensive to collect pairs of videos with semantic coherence or correspondence and label the corresponding segments. We first exploit and reorganize the videos in ActivityNet to form a new dataset for video re-localization research, which consists of about 10,000 videos of diverse visual appearances associated with localized boundary information. Subsequently, we propose an innovative cross gated bilinear matching model such that every time-step in the reference video is matched against the attentively weighted query video. Consequently, the prediction of the starting and ending time is formulated as a classification problem based on the matching results. Extensive experimental results show that the proposed method outperforms the competing methods. Our code is available at: this https URL

##### Abstract (translated by Google)
已经开发了许多方法来帮助人们有效地找到他们想要的视频内容。但是，这方面仍有一些未解决的问题。例如，给定查询视频和参考视频，如何准确地定位参考视频中的片段，使得片段在语义上对应于查询视频？我们定义了一个独特的新任务，即\ textbf {video re-localization}，以解决这个问题。视频重定位是一项重要的新兴技术，涉及许多应用，如视频快速搜索，视频拷贝检测，视频监控等。同时，它也是一项具有挑战性的研究任务，因为视频中语义概念的视觉外观可以有变化很大。清除视频重新定位任务的第一个障碍是缺少现有数据集。收集具有语义连贯性或对应性的视频对并标记相应的片段是劳动昂贵的。我们首先利用并重新组织ActivityNet中的视频，以形成视频重新定位研究的新数据集，其中包含大约10,000个与本地化边界信息相关的各种视觉外观的视频。随后，我们提出了一种创新的交叉门控双线性匹配模型，使得参考视频中的每个时间步骤与专心加权的查询视频相匹配。因此，基于匹配结果将开始和结束时间的预测公式化为分类问题。大量实验结果表明，该方法优于竞争方法。我们的代码位于：此https网址

##### URL
[https://arxiv.org/abs/1808.01575](https://arxiv.org/abs/1808.01575)

##### PDF
[https://arxiv.org/pdf/1808.01575](https://arxiv.org/pdf/1808.01575)

