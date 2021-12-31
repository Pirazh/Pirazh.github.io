---
title: "Towards real-time systems for vehicle re-identification, multi-camera tracking, and anomaly detection"
collection: publications
permalink: /publication/CVPRW2020
excerpt: ''
date: 2020-06-01
venue: 'Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops'
paperurl: 
citation: 'Peri, Neehar, Pirazh Khorramshahi, Sai Saketh Rambhatla, Vineet Shenoy, Saumya Rawat, Jun-Cheng Chen, and Rama Chellappa. "Towards real-time systems for vehicle re-identification, multi-camera tracking, and anomaly detection." In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops, pp. 622-623. 2020.'
---
Vehicle re-identification, multi-camera vehicle tracking, and anomaly detection are essential for city-scale intelligent transportation systems. Both vehicle re-id and multi-camera tracking are challenging due to variations in aspect-ratio, occlusion, and orientation. Robust re-id and tracking systems must consider small scale variations in a vehicle’s appearance to accurately distinguish among vehicles of the same make, model, and color. Scalability is critical for multi-camera systems, as the number of objects in a scene is not known a-priori. Anomaly detection presents a unique challenge due to a dearth of annotations and varied video quality. In this paper, we address the task of vehicle re-id by introducing an unsupervised excitation layer to enhance representation learning. We propose a multi-camera tracking pipeline leveraging this re-id feature extractor to compute a distance matrix and perform clustering to obtain multi-camera vehicle trajectories. Lastly, we leverage background modeling techniques to localize anomalies such as stalled vehicles and collisions. We show the effectiveness of our proposed method on the NVIDIA AI City Challenge, where we obtain 7th place out of 41 teams for the task of vehicle re-id, with an mAP score of $66.68\%$ and achieve state-of-the-art results on the Vehicle-ID dataset. We also obtain an IDF1 score of $12.45\%$ on multi-camera vehicle tracking, and an S4 score of $29.52\%$ for task of anomaly detection, ranking in the top 5 for both tracks.

[Link](http://openaccess.thecvf.com/content_CVPRW_2020/papers/w35/Peri_Towards_Real-Time_Systems_for_Vehicle_Re-Identification_Multi-Camera_Tracking_and_Anomaly_CVPRW_2020_paper.pdf)