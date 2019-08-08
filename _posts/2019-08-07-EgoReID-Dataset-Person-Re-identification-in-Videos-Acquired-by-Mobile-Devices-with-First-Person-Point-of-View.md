---
layout: post
title: "EgoReID Dataset: Person Re-identification in Videos Acquired by Mobile Devices with First-Person Point-of-View"
date: 2019-08-07 03:36:28
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Detection
author: Emrah Basaran, Yonatan Tariku Tesfaye, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, we have seen the performance of video-based person Re-Identification (ReID) methods have improved considerably. However, most of the work in this area has dealt with videos acquired by fixed cameras with wider field of view. Recently, widespread use of wearable cameras and recording devices such as cellphones have opened the door to interesting research in first-person Point-of-view (POV) videos (egocentric videos). Nonetheless, analysis of such videos is challenging due to factors such as poor video quality due to ego-motion, blurriness, severe changes in lighting conditions and perspective distortions. To facilitate the research towards conquering these challenges, this paper contributes a new dataset called EgoReID. The dataset is captured using 3 mobile cellphones with non-overlapping field-of-view. It contains 900 IDs and around 10,200 tracks with a total of 176,000 detections. The dataset also contains 12-sensor meta data e.g. camera orientation pitch and rotation for each video. 
 In addition, we propose a new framework which takes advantage of both visual and sensor meta data to successfully perform Person ReID. We extend image-based re-ID method employing human body parsing trained on ten datasets to video-based re-ID. In our method, first frame level local features are extracted for each semantic region, then 3D convolutions are applied to encode the temporal information in each sequence of semantic regions. Additionally, we employ sensor meta data to predict targets' next camera and their estimated time of arrival, which considerably improves our ReID performance as it significantly reduces our search space.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09570](http://arxiv.org/abs/1812.09570)

##### PDF
[http://arxiv.org/pdf/1812.09570](http://arxiv.org/pdf/1812.09570)

