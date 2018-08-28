---
layout: post
title: "Autonomous Driving without a Burden: View from Outside with Elevated LiDAR"
date: 2018-08-26 20:20:37
categories: arXiv_AI
tags: arXiv_AI Detection
author: Nalin Jayaweera, Nandana Rajatheva, Matti Latva-aho
mathjax: true
---

* content
{:toc}

##### Abstract
The current autonomous driving architecture places a heavy burden in signal processing for the graphics processing units (GPUs) in the car. This directly transforms into battery drain and lower energy efficiency, crucial factors in electric vehicles. This is due to the high bit rate of the captured video and other sensing inputs, mainly due to Light Detection and Ranging (LiDAR) sensor at the top of the car which is an essential feature in todays autonomous vehicles. LiDAR is needed to obtain a high precision map for the vehicle AI to make relevant decisions. However, this is still a quite restricted view from the car. This is the same even in the case of cars without a LiDAR such as Telsa. The existing LiDARs and the cameras have limited horizontal and vertical fields of visions. In all cases it can be argued that precision is lower, given the smaller map generated. This also results in the accumulation of a huge amount of data in the order of several TBs in a day, the storage of which becomes challenging. If we are to reduce the effort for the processing units inside the car, we need to uplink the data to edge or an appropriately placed cloud. However, the required data rates in the order of several Gbps are difficult to be met even with the advent of 5G. Therefore, we propose to have a coordinated set of LiDAR's outside at an elevation which can provide an integrated view with a much larger field of vision (FoV) to a centralized decision making body which then sends the required control actions to the vehicles with a lower bit rate in the downlink and with the required latency. The calculations we have based on industry standard equipment from several manufacturers show that this is not just a concept but a feasible system which can be implemented.

##### Abstract (translated by Google)
当前的自动驾驶架构给汽车中的图形处理单元（GPU）的信号处理带来了沉重的负担。这直接转变为电池消耗和低能效，这是电动汽车的关键因素。这是由于捕获的视频和其他传感输入的高比特率，主要是由于汽车顶部的光探测和测距（LiDAR）传感器，这是当今自动驾驶汽车的基本特征。需要LiDAR来获得车辆AI的高精度地图以做出相关决策。然而，这仍然是汽车的一个非常有限的观点。即使在没有像Telsa这样的LiDAR的汽车的情况下也是如此。现有的激光雷达和相机具有有限的水平和垂直视野。在所有情况下，可以认为精度较低，因为生成的地图较小。这也导致一天中数TB的大量数据的累积，其存储变得具有挑战性。如果我们要减少汽车内部处理单元的工作量，我们需要将数据上传到边缘或适当放置的云。然而，即使随着5G的出现，也难以满足几Gbps量级的所需数据速率。因此，我们建议在一个高度上有一组协调的LiDAR外部，它可以为集中决策机构提供一个具有更大视野（FoV）的综合视图，然后向下方的车辆发送所需的控制动作。下行链路中的比特率和所需的延迟。我们基于几家制造商的行业标准设备进行的计算表明，这不仅仅是一个概念，而是一个可以实施的可行系统。

##### URL
[http://arxiv.org/abs/1808.08617](http://arxiv.org/abs/1808.08617)

##### PDF
[http://arxiv.org/pdf/1808.08617](http://arxiv.org/pdf/1808.08617)

