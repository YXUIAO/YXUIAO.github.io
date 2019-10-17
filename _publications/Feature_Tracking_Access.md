---
title: "Feature Tracking Based on Line Segments with the Dynamic and Active-pixel Vision Sensor (DAVIS)"
collection: publications
permalink: /Feature_Tracking_Access
# excerpt: 'In this paper, we propose a novel fast and asynchronous event-based corner detection method which is called FA-Harris. FA-Harris consists of several components, including an event filter, a Global Surface of Active Events (G-SAE) maintaining unit, a corner candidate selecting unit, and a corner candidate refining unit.'
date: 2019-07-11
venue: IEEE Access
# paperurl: 'https://arxiv.org/pdf/1906.10925.pdf'
# citation: 'Ruoxiang, Li and Dianxi, Shi and Yongjun, Zhang and Kaiyue, Li and Ruihao, Li. "FA-Harris: A Fast and Asynchronous Corner Detector for Event Cameras". IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2019.'
youtubeId: v5CcBVkmI6w
---
<a href="https://www.researchgate.net/publication/335013030_Feature_Tracking_Based_on_Line_Segments_with_the_Dynamic_and_Active-pixel_Vision_Sensor_DAVIS" target="_blank"><b>PDF</b></a>&emsp;
# <a href="https://youtu.be/v5CcBVkmI6w" target="_blank"><b>Video</b></a>&emsp;
# <a href="https://ruoxianglee.github.io/files/2019_iros_fa_harris.txt" target="_blank"><b>

<b>Abstract.</b>
As a novel vision sensor, the Dynamic and Active-pixel Vision Sensor (DAVIS) combines a standard camera and an asynchronous event-based sensor in the same pixel array. In this paper, we propose a novel asynchronous feature tracking method based on line segments with the DAVIS. The proposed method takes asynchronous events, synchronous image frames and IMU data as the input. We first use the Harris detector to extract feature points and the Canny detector to extract line segment templates from image frames. Then we select spatio-temporal windows from asynchronous events and perform registration to estimate the optical flow. The registration is achieved by associating the extracted line segments with the events inside the window. Expectation Maximization-Iterative Closest Point (EM-ICP) is adopted for the registration. Afterward, we use the estimated optical flow and the IMU data to update the position of line segments, and take them as the new templates. We evaluate our method on the public Event Camera Datasets. The results show that our method can achieve comparable performance to other methods in terms of accuracy and tracking time.

<b>Reference:</b> 
* Kaiyue, Li and Dianxi, Shi and Yongjun, Zhang and <b>Ruoxiang, Li</b> and Ruihao, Li, "Feature Tracking Based on Line Segments with the Dynamic and Active-pixel Vision Sensor (DAVIS)," IEEE Access 7 (2019): 110874-110883.
