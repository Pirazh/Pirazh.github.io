---
title: "A semi-automatic 2D solution for vehicle speed estimation from monocular videos"
collection: publications
permalink: /publication/CVPRW2018
excerpt: ''
date: 2018
venue: 'Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops'
paperurl: 
citation: 'Kumar, Amit, Pirazh Khorramshahi, Wei-An Lin, Prithviraj Dhar, Jun-Cheng Chen, and Rama Chellappa. "A semi-automatic 2D solution for vehicle speed estimation from monocular videos." In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops, pp. 137-144. 2018.'
---
In this work, we present a novel approach for vehicle speed estimation from monocular videos. The pipeline consists of modules for multi-object detection, robust tracking, and speed estimation. The tracking algorithm has the capability for jointly tracking individual vehicles and estimating velocities in the image domain. However, since camera parameters are often unavailable and extensive variations are present in the scenes, transforming measurements in the image domain to real world is challenging. We propose a simple two-stage algorithm to approximate the transformation. Images are first rectified to restore affine properties, then the scaling factor is compensated for each scene. We show the effectiveness of the proposed method with extensive experiments on the traffic speed analysis dataset in the NVIDIA AI City challenge. We achieve a detection rate of 1.0 in vehicle detection and tracking, and Root Mean Square Error of 9.54 (mph) for the task of vehicle speed estimation in unconstrained traffic videos.

[Link](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w3/Kumar_A_Semi-Automatic_2D_CVPR_2018_paper.pdf)