---
title: 'PigV2: Monitoring Pig Vital Signs through Ground Vibrations Induced by Heartbeat
  and Respiration'
authors:
- Yiwen Dong
- Jesse R Codling
- Gary Rohrer
- Jeremy Miles
- Sudhendu Sharma
- Tami Brown-Brandl
- Pei Zhang
- Hae Young Noh
date: '2023-01-01'
publishDate: '2024-08-15T21:32:55.096422Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 20th ACM Conference on Embedded Networked Sensor
  Systems*'
doi: 10.1145/3560905.3568416
abstract: Pig vital sign monitoring (e.g., estimating the heart rate (HR) and respiratory
  rate (RR)) is essential to understand the stress level of the sow and detect the
  onset of parturition. It helps to maximize peri-natal survival and improve animal
  well-being in swine production. The existing approach mainly relies on manual measurement,
  which is labor-intensive and only provides a few points of information. Other sensing
  modalities such as wearables and cameras are developed to enable more continuous
  measurement, but are still limited due to animal discomfort, data transfer, and
  storage challenges. In this paper, we introduce PigV2, the first system to monitor
  pig heart rate and respiratory rate through ground vibrations. Our approach leverages
  the insight that both heartbeat and respiration generate ground vibrations when
  the sow is lying on the floor. We infer vital information by sensing and analyzing
  these vibrations. The main challenge in developing PigV2 is the overlap of vital-
  and non-vital-related information in the vibration signals, including pig movements,
  pig postures, pig-to-sensor distances, and so on. To address this issue, we first
  characterize their effects, extract their current status, and then reduce their
  impact by adaptively interpolating vital rates over multiple sensors. PigV2 is evaluated
  through a real-world deployment with 30 pigs. It has 3.4% and 8.3% average errors
  in monitoring the HR and RR of the sows, respectively.
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3560905.3568416
tags:
- Fully-Reviewed Conference
- Heart Rate
- Pigs Project
---