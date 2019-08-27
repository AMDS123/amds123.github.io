---
layout: post
title: "City-Scale Road Extraction from Satellite Imagery v2: Road Speeds and Travel Times"
date: 2019-08-06 12:59:28
categories: arXiv_CV
tags: arXiv_CV Inference
author: Adam Van Etten
mathjax: true
---

* content
{:toc}

##### Abstract
Automated road network extraction from remote sensing imagery remains a significant challenge despite its importance in a broad array of applications. To this end, we explore road network extraction at scale with inference of semantic features of the graph, identifying speed limits and route travel times for each roadway. We call this approach City-Scale Road Extraction from Satellite Imagery v2 (CRESIv2). Including estimates for travel time permits true optimal routing, not just the shortest geographic distance. We compare SpaceNet labels to OpenStreetMap (OSM) labels, and find that models both trained and tested on SpaceNet labels outperform OSM labels by 60% or greater. For a diverse test set of SpaceNet data and a traditional edge weight of geometric distance, we find an aggregate of 5% improvement over existing methods. We also test our algorithm on Google satellite imagery with OpenStreetMap labels, and find a 23% improvement over previous work. Metric scores decrease by only 4% on large graphs when using travel time rather than geometric distance for edge weights, indicating that optimizing routing for travel time is feasible with this approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09715](http://arxiv.org/abs/1908.09715)

##### PDF
[http://arxiv.org/pdf/1908.09715](http://arxiv.org/pdf/1908.09715)

