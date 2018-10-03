---
layout: post
title:  "Joint Estimation of DOA and Carrier Frequency"
date:   2018-03-28
excerpt: "<strong><big>K.-C. Hsu</big></strong> and J.-F. Kiang, ''Joint Estimation of DOA and Carrier Frequency Based on Coprime Arrays ,'' 
<i>Progress In Electromagnetics Research Symposium</i>, 2018."
feature_fig: <figure class="half"><img src="https://kevin71104.github.io/assets/img/DOA_JE/partFreq_JE.jpg" class="img-disappear"> <img src="https://kevin71104.github.io/assets/img/DOA_JE/partFreq_10Mu.jpg"></figure>
research: true
tag:
- Research
- Direction-of-Arrival Estimation
- Array Signal Processing
- Frequency Estimation
- Degree-of-Freedom
comments: true
---

<figure>
	<img src="https://kevin71104.github.io/assets/img/DOA_JE/mainarray.jpg">
</figure>

In practical scenarios like air-plane navigation and monitoring near an airport, 
the target signals consist of carrier frequency (CF) known and carrier frequency unknown source signals.
When the carrier frequency is unknown, state-of-the-art algorithms like **MUltiple SIgnal Classification (MUSIC)** cannot be directly applied.
In addition, the complexity of **Compressed Sensing (CS)** approach is too high to use in practice.
Although joint **estimation of signal parameters via rotational invariance techniques (ESPRIT)** can estimate CF and DOA simultaneously,
the number of detectable source signals is limited.
In our work, we proposed a two-stage estimation algorithm to jointly estimate DOA and CF, 
and two orthogonal co-prime arrays (CPA) were used to increase degree-of-freedoms.
In the first stage, the DOAs of CF known sources were estimated by spatial-smoothing MUSIC and a simple matching method.
In the second stage, **projected joint ESPRIT (PJE)** was used to estimate the DOAs and CFs of CF unknown sources.

The contribution of this work comes in two aspects:
- Our proposed PJE can detect more accurately even when the number of sources grows
- The orthogonal CPAs are utilized and the corresponding signal processing techniques are proposed

<figure class="half">
	<img src="https://kevin71104.github.io/assets/img/DOA_JE/partFreq_JE.jpg" class="img-disappear"> 
	<img src="https://kevin71104.github.io/assets/img/DOA_JE/partFreq_10Mu.jpg">
</figure>

<p class="double_underline">PUBLICATION:</p>
**K.-C. Hsu** and J.-F. Kiang, 
''Joint Estimation of DOA and Carrier Frequency Based on Coprime Arrays,'' 
*Progress In Electromagnetics Research Symposium*, 2018.
