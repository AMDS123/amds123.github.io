---
layout: post
title: "Appearance-based indoor localization: A comparison of patch descriptor performance"
date: 2015-03-11 21:43:46
categories: arXiv_CV
tags: arXiv_CV SLAM
author: Jose Rivera-Rubio, Ioannis Alexiou, Anil A. Bharath
mathjax: true
---

* content
{:toc}

##### Abstract
Vision is one of the most important of the senses, and humans use it extensively during navigation. We evaluated different types of image and video frame descriptors that could be used to determine distinctive visual landmarks for localizing a person based on what is seen by a camera that they carry. To do this, we created a database containing over 3 km of video-sequences with ground-truth in the form of distance travelled along different corridors. Using this database, the accuracy of localization - both in terms of knowing which route a user is on - and in terms of position along a certain route, can be evaluated. For each type of descriptor, we also tested different techniques to encode visual structure and to search between journeys to estimate a user's position. The techniques include single-frame descriptors, those using sequences of frames, and both colour and achromatic descriptors. We found that single-frame indexing worked better within this particular dataset. This might be because the motion of the person holding the camera makes the video too dependent on individual steps and motions of one particular journey. Our results suggest that appearance-based information could be an additional source of navigational data indoors, augmenting that provided by, say, radio signal strength indicators (RSSIs). Such visual information could be collected by crowdsourcing low-resolution video feeds, allowing journeys made by different users to be associated with each other, and location to be inferred without requiring explicit mapping. This offers a complementary approach to methods based on simultaneous localization and mapping (SLAM) algorithms.

##### Abstract (translated by Google)
视觉是最重要的感官之一，人类在航行中广泛使用视觉。我们评估了不同类型的图像和视频帧描述符，这些描述符可用于根据摄像机所携带的内容来确定区分人的独特视觉标志。为此，我们创建了一个包含超过3公里视频序列的数据库，其中包含沿着不同走廊行进的距离。使用这个数据库，可以评估本地化的准确性 - 无论是在了解用户所在的路线上，还是在沿着特定路线的位置方面。对于每种类型的描述符，我们还测试了不同的技术来对视觉结构进行编码，并在旅程之间进行搜索以估计用户的位置。这些技术包括单帧描述符，使用帧序列以及彩色和非彩色描述符的技术。我们发现单帧索引在这个特定的数据集内工作得更好。这可能是因为拿着相机的人的动作使得视频太依赖于一个特定旅程的个别步骤和动作。我们的研究结果表明，基于外观的信息可能是室内导航数据的一个额外来源，通过无线电信号强度指标（RSSI）等来提供。这种视觉信息可以通过众包低分辨率视频馈送来收集，使不同用户所做的旅程彼此相关联，并且可以推断位置而不需要明确的映射。这为基于同时定位和映射（SLAM）算法的方法提供了补充方法。

##### URL
[https://arxiv.org/abs/1503.03514](https://arxiv.org/abs/1503.03514)

##### PDF
[https://arxiv.org/pdf/1503.03514](https://arxiv.org/pdf/1503.03514)

