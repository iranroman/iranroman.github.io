---
layout: post
title:  "Theoretical Neuroscience"
date:   2023-11-24
excerpt: "Beyond prediction and recognition: strong anticipation explains perception & action in human behavior"
research: true

comments: false
---

My models of strong anticipation are mathematically parsimonious and build
upon the dynamics of a non-linear oscillator. One of them directly addresses
the Negative Mean Asynchony (NMA), attributing it to delayed neural communication.
This model notably
can account for the disparities between musicians and non-musicians, and
also the NMA growth as a function of longer metronome periods (Roman et al. 2019).

| ![nma.png](https://raw.githubusercontent.com/iranroman/iranroman.github.io/main/figures/nma.png) | 
|:--:| 
| *Left: The NMA in (non) musicians tapping with a metronome at different periods. Right: The NMA in the “musician” and “non-musician” versions of my model, which anticipates due to delayed feedback. The same regression lines for the behavioral data are shown in both plots.* |

Moreover, considering the recent discovery of a Positive Mean Asynchrony (PMA)
where individuals tend to lag rhythmic stimuli faster than their Spontaneous Motor Tempo (SMT)
I devised another model. Retaining the non-linear oscillator, this model uses a dynamic frequency 
term to resonate with a stimulus’ arbitrary frequency. However, this resonance comes with a pull 
towards a term that simulates an individual’s SMT. Hence, the model can show both the NMA and the PMA, 
both of which grow as the stimulus frequency deviates from the SMT (Roman et al., 2023). 
This work was funded by a seed grant from the Stanford AI Lab in 2020. 

| ![hebbian.png](https://raw.githubusercontent.com/iranroman/iranroman.github.io/main/figures/hebbian.png) | 
|:--:| 
| *PMA and NMA in my model as a function of a stimulus (FN=N% faster or slower) than its rate of spontaneous oscillation.* |

Collectively, these models provide a comprehensive understanding of human synchronization dynamics, challenging traditional Bayesian-based approaches.

1. [Roman IR, Washburn A, Large EW, Chafe C, Fujioka T. Delayed feedback embedded in perception-action coordination cycles results in anticipation behavior during synchronized rhythmic action: A dynamical systems approach. PLoS computational biology. 2019 Oct 31;15(10):e1007371](https://ccrma.stanford.edu/~iran/papers/Roman_et_al_PLoSCB_2019.pdf)
2. [Large EW, Roman IR, Kim JC, Cannon J, Pazdera JK, Trainor LJ, Rinzel J, Bose A. Dynamic models for musical rhythm perception and coordination. Frontiers in Computational Neuroscience. 2023 May 17;17:1151895.](https://ccrma.stanford.edu/~iran/papers/Large_et_al_FN_2023.pdf)
3. [Roman IR, Roman AS, Kim JC, Large EW. Hebbian learning with elasticity explains how the spontaneous motor tempo affects music performance synchronization. PLOS Computational Biology. 2023 Jun 7;19(6):e1011154.](https://ccrma.stanford.edu/~iran/papers/Roman_et_al_PLoSCB_2023.pdf)

---
<p align="right">
&copy; 2023 Iran R. Roman
</p>
