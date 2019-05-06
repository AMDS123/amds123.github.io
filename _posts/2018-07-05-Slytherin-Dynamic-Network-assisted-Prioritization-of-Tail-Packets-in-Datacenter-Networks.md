---
layout: post
title: "Slytherin: Dynamic, Network-assisted Prioritization of Tail Packets in Datacenter Networks"
date: 2018-07-05 21:21:06
categories: arXiv_CV
tags: arXiv_CV
author: Hamed Rezaei, Mojtaba Malekpourshahraki, Balajee Vamanan
mathjax: true
---

* content
{:toc}

##### Abstract
Datacenter applications demand both low latency and high throughput; while interactive applications (e.g., Web Search) demand low tail latency for their short messages due to their partition-aggregate software architecture, many data-intensive applications (e.g., Map-Reduce) require high throughput for long flows as they move vast amounts of data across the network. Recent proposals improve latency of short flows and throughput of long flows by addressing the shortcomings of existing packet scheduling and congestion control algorithms, respectively. We make the key observation that long tails in the Flow Completion Times (FCT) of short flows result from packets that suffer congestion at more than one switch along their paths in the network. Our proposal, Slytherin, specifically targets packets that suffered from congestion at multiple points and prioritizes them in the network. Slytherin leverages ECN mechanism which is widely used in existing datacenters to identify such tail packets and dynamically prioritizes them using existing priority queues. As compared to existing state-of-the-art packet scheduling proposals, Slytherin achieves 18.6% lower 99th percentile flow completion times for short flows without any loss of throughput. Further, Slytherin drastically reduces 99th percentile queue length in switches by a factor of about 2x on average.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.02184](https://arxiv.org/abs/1807.02184)

##### PDF
[https://arxiv.org/pdf/1807.02184](https://arxiv.org/pdf/1807.02184)

