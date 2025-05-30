---
title: "Data-Driven Radar Target Position and Velocity Estimation"
collection: talks
type: "Talk"
permalink: /talks/data-driven_radar_target_position_velocity
venue: "U.S. Air Force Research Laboratory (AFRL)"
date: 2023-08-10
location: "Dayton, OH"
---

Target position and velocity estimation is a crucial aspect in the design of modern radar
systems, being foundational to various radar applications such as surveillance, navigation,
and military operations. This task involves determining the position and velocity of a target
in the presence of clutter and noise using radar STAP techniques. Much of the framework
for estimating these target attributes is defined post radar STAP detection, where received
radar signals are spatially and temporally processed to detect and subsequently estimate
target positions and velocities. Despite their advancements, however, radar STAP methods
have several limitations, including (1) sensitivity to noise and interference, and (2)
high computational costs. Expanding upon (1), the interference due to clutter, modeled
via the clutter covariance matrix, must be estimated from limited available samples when it
is unknown a priori. This weakens any optimality claims made regarding the adaptive radar
detection and subsequent target position and velocity estimation procedures (i.e., finding
the peak location from a detection test statistic). Resultantly, while optimal detection can
be achieved in the non-adaptive case (where the true clutter covariance matrix is known),
we cannot make claims of invariance in the adaptive case (where the clutter covariance
matrix is unknown). As a notional proof in the context of suboptimal detection for the
adaptive case, we analyze whether the accuracy of target position and velocity
estimation post radar STAP detection can be improved using a data-driven methodology.
