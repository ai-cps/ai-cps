---
#layout: archive
title: "Research"
permalink: /research/
author_profile: true
toc: true
---

## PhD Dissertation Research

Anomaly detection techniques are important in system health monitoring applications (e.g., fault detection and disease diagnosis). By recognizing suspicious patterns in data, anomaly detection models can tell whether system has degraded from the normal operating condition into a faulty or diseased state. To avoid unnecessary losses, it is desirable to have a way to identify incipient anomalies, i.e. to detect potential problems in their early stages of development. In buildings, early detection of incipient faults can help reduce maintenance and repair costs, save energy, and enhance occupant comfort. In healthcare, if incipient diseases can be discovered early, effective treatments can be applied and can prevent diseases from progressing into more severe stages. 

However, it is a challenge to accurately identify incipient anomalies while at the same time not incurring too many false alarms. Incipient anomalies present milder symptoms compared to severe ones, and are difficult to detect and diagnose due to their close resemblance to normal operating conditions. Anomaly detection approaches based on supervised machine learning rely on high-quality labeled data to build accurate classifiers. However, the lack of incipient anomaly examples in the training data can pose severe risks to anomaly detection methods that are built upon machine learning techniques, because these anomalies can be easily mistaken as normal operating conditions.

Ensemble learning is widely applied in machine learning to improve model performance and to mitigate decision risks. In ensemble approaches, predictions from a diverse set of learners are combined to obtain a joint decision with lower bias and variance. Recently, various methods have been explored in literature for estimating prediction uncertainties using ensemble learning. To address this challenge of incipient anomalies, I propose to utilize the uncertainty information available from ensemble learning to identify potential misclassified incipient anomalies. I show that ensemble learning methods can give improved performance on incipient anomalies and identify common pitfalls in these models through extensive experiments on two real-world applications---detection of chiller faults and diagnosing diabetic retinopathy diseases. A theoretical analysis that compares the two popular strategies for extracting uncertainty information will also be given. I will also discuss how to design more effective ensemble models for detecting incipient anomalies.