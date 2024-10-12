---
layout: post
title:  "Multimodal Machine Perception"
date:   2023-11-24
excerpt: "AI to analyze and understand dynamic scenes"
research: true

comments: false
---

My research focuses on advancing machine perception capabilities, specifically in the areas of sound source distance estimation, direction of arrival estimation, and sound event localization and detection. These advancements have significant implications for the development of intelligent systems that can analyze and interpret dynamic real-world scenes, particularly in applications such as augmented reality, robotics, and immersive media experiences.

### Sound Source Distance Estimation and SELD Data Simulation
In one line of research, I focus on accurately estimating the distance of sound sources in various acoustic environments. This task, though crucial for spatial perception, has been underexplored relative to direction of arrival estimation. By introducing models that account for diverse room acoustics, my work has significantly improved sound source distance estimation across multiple datasets. Our approach has outperformed recent benchmarks and characterizes the model’s performance under various room conditions, highlighting the importance of training models with diverse acoustic scenarios to enhance robustness.

Complementing this work is the development of *SpatialScaper*, a tool for simulating and augmenting soundscapes for SELD tasks. The tool allows for the creation of virtual room acoustics via parameterized room impulse responses, offering a way to generate realistic training data for sound event localization models. By incorporating both sound source distance estimation and simulated soundscapes, my research provides a comprehensive approach to improving machine perception in dynamic acoustic environments.

### Acoustic Imaging for Direction of Arrival Estimation (DoAE)
A significant focus of my research is on enhancing DoAE by leveraging acoustic imaging. I have developed two complementary approaches that use spherical representations of sound energy to improve the accuracy of DoAE tasks. 

The first approach was fully supervised **deep acoustic imaging**. Using spherical intensity maps (SIMs), derived from high-resolution microphone arrays, we achieved state-of-the-art performance in DoAE tasks. By employing super-resolution techniques, we upsampled low-resolution microphone data to create high-resolution acoustic images, which significantly improved the accuracy of sound direction estimation.

Building on this, my latest contribution is a **self-supervised method** that generates SIMs for DoAE without requiring annotated data. This approach leverages large quantities of recordings from both low- and high-resolution microphones to generate an intuitive representation of sound energy across time and space. SIMs have proven effective in unsupervised DoAE tasks, matching or exceeding the performance of supervised models on key benchmarks. This method represents a significant step toward more generalizable and scalable DoAE solutions.

### Reconstructing Room Scales with Sound for AR Displays
Another application of my research lies in augmented reality (AR), where I have explored using audio to reconstruct room scales. Unlike traditional 3D reconstruction methods that rely on optical sensors, my approach utilizes sound waves to estimate the geometric properties of a room. This method is particularly useful in environments where line-of-sight optical techniques are limited or impractical, such as occluded or inaccessible spaces. By harnessing audio reflections, we can create more efficient and accurate room reconstructions for AR applications, enhancing user experience in immersive environments.

Through these contributions, my work continues to push the boundaries of machine perception, integrating audio and visual modalities to enable machines to perceive the world with greater precision and context-awareness.

You can find papers related to these topics on [my google scholar page](https://scholar.google.com/citations?user=W_PoFfkAAAAJ&hl).

---
<p align="right">
&copy; 2024 Iran R. Roman
</p>
