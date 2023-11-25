---
layout: post
title:  "Multimodal Machine Perception"
date:   2023-11-24
excerpt: "Signal processing to analyze and understand dynamic scenes"
research: true

comments: false
---

My research pioneers robust sound distance estimation and new 
representations for sound event localization and detection (SELD). 
In a paper presented at the 2023 IEEE Workshop on Applications of 
Signal Processing to Audio and Acoustics, I introduced a new model
for sound source distance estimation (Kushwaha et al., 2023). 
We compiled a dataset consisting of real-world and open-source 
tetrahedral microphone recordings, captured in different geographical locations.
We focused on understanding and mitigating distance estimation error. 
Experiments showed the benefit of supervising model learning by converting 
error into a percentage of the ground truth distance. We significantly outperformed 
baseline approaches on the LOCATA benchmark, and we also evaluated our model's 
performance on many other datasets.

| ![distance.png](https://raw.githubusercontent.com/iranroman/iranroman.github.io/main/figures/distance.png) | 
|:--:| 
| *Model performance in sound source distance estimation is optimal when using a percentage- based loss: AE = abs error; APE= abs % error; TAPE = thresh- olded APE (δ = threshold)* |

My work also propels sound direction of arrival (DoA) estimation forward by 
optimizing acoustic imaging from low-resolution tetrahedral microphone arrays. 
To achieve this, my co-authors and I
leverage computer vision super-resolution models that
can upsample low-resolution arrays to high-resolution.
The result is a spherical heatmap that describes sound
source provenance. This representation allowed us to train a 
recurrent neural network that can carry out DoA. A detailed ablation study led to 
an optimal model displaying state-of-the-art performance on the LOCATA and 
STARSS2023 benchmarks (Roman et al., 2024).
My work also has leveraged acoustic signals to estimate room size (Liang et al., 2023).

| ![imaging.png](https://raw.githubusercontent.com/iranroman/iranroman.github.io/main/figures/imaging.png) | 
|:--:| 
| *Acoustic imaging is a high-resolution and interpretable spherical representation of a sound source's provenance on a spherical projection.* |

1. [Kushwaha SS, Roman IR, Bello JP. Analyzing the Effect of Equal-Angle Spatial Discretization on Sound Event Localization and Detection. In DCASE 2022 Nov.](https://ccrma.stanford.edu/~iran/papers/Kushwaha_et_al_DCASE_2022.pdf)
2. [Kushwaha SS, Roman IR, Fuentes M, Bello JP. Sound source distance estimation in diverse and dynamic acoustic conditions. In 2023 IEEE Workshop on Applications of Signal Processing to Audio and Acoustics (WASPAA) 2023 Oct 22 (pp. 1-5). IEEE.](https://ccrma.stanford.edu/~iran/papers/Kushwaha_et_al_WASPAA_2023.pdf)
3. [Roman AS, Roman IR, Bello JP. Robust direction of arrival estimation from deep acoustic imaging. IEEE International Conference on Acoustics, Speech and Signal Processing 2024]()
4. [Liang BS, Liang AS, Roman IR, Weiss T, Duinkharjav B, Bello JP, Sun Q. Reconstructing room scales with a single sound for augmented reality displays. Journal of Information Display. 2023 Jan 2;24(1):1- 2.](https://ccrma.stanford.edu/~iran/papers/Liang_et_al_JID_2023.pdf)

---
<p align="right">
&copy; 2023 Iran R. Roman
</p>
