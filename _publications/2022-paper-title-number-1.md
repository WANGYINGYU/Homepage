---
title: "Occupancy-SLAM: Simultaneously Optimizing Robot Poses and Continuous Occupancy Map"
collection: publications
permalink: /publication/2022-paper-title-number-1
date: 2022-06-27
venue: 'Robotics: Science and Systems'
paperurl: 'https://www.roboticsproceedings.org/rss18/p003.pdf'
citation: '@INPROCEEDINGS{Zhao-RSS-22, 
    AUTHOR    = {Liang Zhao AND Yingyu Wang AND Shoudong Huang}, 
    TITLE     = {{Occupancy-SLAM: Simultaneously Optimizing Robot Poses and Continuous Occupancy Map}}, 
    BOOKTITLE = {Proceedings of Robotics: Science and Systems}, 
    YEAR      = {2022}, 
    ADDRESS   = {New York City, NY, USA}, 
    MONTH     = {June}, 
    DOI       = {10.15607/RSS.2022.XVIII.003} 
} '
---
In this paper, we propose an optimization based SLAM approach to simultaneously optimize the robot trajectory and the occupancy map using 2D laser scans (and odometry) information. The key novelty is that the robot poses and the occupancy map are optimized together, which is significantly different from existing occupancy mapping strategies where the robot poses need to be obtained first before the map can be estimated. In our formulation, the map is represented as a continuous occupancy map where each 2D point in the environment has a corresponding evidence value. The Occupancy-SLAM problem is formulated as an optimization problem where the variables include all the robot poses and the occupancy values at the selected discrete grid cell nodes. We propose a variation of Gauss-Newton method to solve this new formulated problem, obtaining the optimized occupancy map and robot trajectory together with their uncertainties. Our algorithm is an offline approach since it is based on batch optimization and the number of variables involved is large. Evaluations using simulations and publicly available practical 2D laser datasets demonstrate that the proposed approach can estimate the maps and robot trajectories more accurately than the state-of-the-art techniques, when a relatively accurate initial guess is provided to our algorithm.

[Download paper here](https://www.roboticsproceedings.org/rss18/p003.pdf)