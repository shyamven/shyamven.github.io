---
title: "Subspace Perturbation Analysis for Data-Driven Radar Target Localization"
collection: talks
type: "Conference proceedings talk"
permalink: /talks/subspace_perturbation_analysis
venue: "2023 IEEE Radar Conference"
date: 2023-05-04
location: "San Antonio, TX"
---

Recent works exploring data-driven approaches to classical problems in adaptive radar have demonstrated promising results pertaining to the task of radar target localization. Via the use of space-time adaptive processing (STAP) techniques and convolutional neural networks, these data-driven approaches to target localization have helped benchmark the performance of neural networks for matched scenarios. However, the thorough bridging of these topics across mismatched scenarios still remains an open problem. As such, in this work, we augment our data-driven approach to radar target localization by performing a sub-space perturbation analysis, which allows us to benchmark the localization accuracy of our proposed deep learning framework across mismatched scenarios. To evaluate this framework, we generate comprehensive datasets by randomly placing targets of variable strengths in mismatched constrained areas via RFView®, a high-fidelity, site-specific modeling and simulation tool. For the radar returns from these constrained areas, we generate heatmap tensors in range, azimuth, and elevation using the normalized adaptive matched filter (NAMF) test statistic. We estimate target locations from these heatmap tensors using a convolutional neural network, and demonstrate that the predictive performance of our framework in the presence of mismatches can be predetermined.
