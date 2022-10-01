---
title: "Learned Monocular Depth Priors in Visual-Inertial Initialization"
layout: gridlay
excerpt: "Learned Monocular Depth Priors in Visual-Inertial Initialization"
sitemap: false
permalink: /mainpage/
---

[comment]: Title
<h2 align="center"> Learned Monocular Depth Priors in Visual-Inertial Initialization  </h2>
<p>&nbsp;</p>

[comment]: Authors
<p style="text-align: center;">
<a> Yunwen Zhou </a>
&nbsp;
<a> Abhishek Kar </a>
&nbsp;
<a> Eric Turner </a>
&nbsp;
<a> Adarsh Kowdle </a>
&nbsp;
<a> Chao X. Guo </a>
&nbsp;
<a> Ryan C. DuToit </a>
&nbsp;
<a> Konstantine Tsotsos </a>
&nbsp;
</p>
<p style="text-align: center;"> Google AR </p>
<p style="text-align: center;"> The European Conference on Computer Vision(ECCV) TEL AVIV 2022 </p>

[comment]: Abstract
<h3> Abstract </h3>
Visual-inertial odometry (VIO) is the pose estimation backbone for most AR/VR and autonomous robotic systems today, in both academia and industry. However, these systems are highly sensitive to the initialization of key parameters such as sensor biases, gravity direction, and metric scale. In practical scenarios where high-parallax or variable acceleration assumptions are rarely met (e.g. hovering aerial robot, smartphone AR user not gesticulating with phone), classical visual-inertial initialization formulations often become ill-conditioned and/or fail to meaningfully converge. In this paper we target visual-inertial initialization specifically for these low-excitation scenarios critical to in-the-wild usage. We propose to circumvent the limitations of classical visual-inertial structure-from-motion (SfM) initialization by incorporating a new learning-based measurement as a higher-level input. We leverage learned monocular depth images (mono-depth) to constrain the relative depth of features, and upgrade the mono-depths to metric scale by jointly optimizing for their scales and shifts. Our experiments show a significant improvement in problem conditioning compared to a classical formulation for visual-inertial initialization, and demonstrate significant accuracy and robustness improvements relative to the state-of-the-art on public benchmarks, particularly under low-excitation scenarios. We further extend this improvement to implementation within an existing odometry system to illustrate the impact of our improved initialization method on resulting tracking trajectories.

[comment]: Paper
<h3> Paper </h3>
- Paper: <a href="https://arxiv.org/abs/2204.09171" style="color: #CC0000"> arXiv </a>