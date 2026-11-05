---
layout: about
title: about
permalink: /
subtitle: minji.kang0408@gmail.com <!--<a href='#'>Affiliations</a>.-->  <!--Etc.-->
---

I am a researcher who worked at Korea Electronics Technical Institute. My research interest lies in Reliable and Robust AI for real-world/physical system. I did My Bachelor of Science degree at Kangwon National University under Prof. [Sang-Ki Ko](https://sites.google.com/site/sangkikotoc/).

[GitHub](https://github.com/minD9it) / [CV](/assets/pdf/Minji_Kang_CV.pdf) / [LinkedIn](https://www.linkedin.com/in/minji-kang-175ba4337/)


### Publications
**Primary Lithium Battery SOC Prediction System for Estimating Life-time of Industrial IoT Devices**  
**Minji Kang**, Seongseop Kim, Seungwoo Lee  
Autumn Annual Conference of The institute of Electronics and Information Engineers, 2023  
2023-11-24
<details>
  <summary>Abstract</summary>
  <div markdown="1">
    In this paper, we propose a method for estimating lithium primary battery capacity in embedded device systems. The proposed technology is a method of predicting remaining power using the voltage characteristics of lithium primary batteries and profile-based operation modes. In order to apply the proposed remaining capacity prediction structure to embedded systems, the parameters using LUT are designed to be lightweight. As a result, it was confirmed that the accuracy of estimating the remaining primary battery capacity of the proposed module was with 10%.
  </div>
</details>

**SoC Estimation of Lithium Thionyl Chloride Battery Using Voltage Recovery Time**  
**Minji Kang**, Seongseop Kim, Seungwoo Lee  
The 11th International Conference on Electronics, Electrical Engineering, Computer Science 2022  
2022-12-20

**Analysis of EDLC-based Primary Battery Current Consumption Characteristics Considering Operation Patterns in IoT Devices**  
**Minji Kang**, Seongseop Kim, Seungwoo Lee  
The 10th International Conference on Electronics, Electrical Engineering, Computer Science 2022  
2022-07-21

<details>
  <summary>Abstract</summary>
  <div markdown="1">
    This paper presents an analysis of the discharge characteristics of EDLC-based primary battery in accordance with the operating characteristics of IoT devices. To extract discharge characteristics, we analyzed the difference between an EDLC-based primary battery and a primary battery not using EDLC after the experiment. The current consumption pattern of the IoT device used in the experiment has a structure that includes IDLE, Processing, and communication transmission/reception, and we comparatively analyzed the voltage change at this time. As a result, it shows that the voltage recovery time of the EDLC-based primary battery is up to 15 times greater than the regular one, but the average of the maximum voltage regulation is about 11 times less.
  </div>
  </details>
    
**Battery Lifetime Estimation System for IoT Devices using Voltage Measurement**  
Seongseop Kim, **Minji Kang**, Youngmin Kwon, Seungwoo Lee  
Institute of Embedded Engineering of Korea 2021  
2021-11-11
<details>
  <summary>Abstract</summary>
  <div markdown="1">
    Primary battery has been widely used in many industry, because of its advantage in high capacity and low self discharging. However, due to the characteristic of a sudden drop in voltage before replacing the battery, it is hard to replace the battery before discharging. In this study, we propose a measurement technique for battery lifetime estimation based on voltage recovery measurement. The voltage recovery time of a primary lithium battery was measured using electronic load, which can load specific current, same as embedded system. The result shows that the voltage recovery time of the primary lithium battery became slower as battery capacity decreased, which can be implemented in embedded system.
  </div>
</details>

**End-to-End Joint Time–Space Synchronization of GPS and Video for Football Game Analysis**   
Changjo Kim, **Minji Kang**, Geonhee Jo, Miru Hong, Jinsung Yoon, and Sang-Ki Ko   
Preprint  
<details>
  <summary>Abstract</summary>
  <div markdown="1">
    Fusing measurements from heterogeneous sensors — here a wearable GNSS receiver (∼10 Hz) and a stadium video camera (∼25 fps) tracking the same set of football players — is bottlenecked by three preprocessing tasks that the sensor- fusion literature usually treats independently: (i) recovering the time offset between the two streams, (ii) calibrating the residual transform that maps the video sensor’s image-plane detections onto the world (pitch) frame, and (iii) estimating the per-device GPS positional bias caused by satellite geometry, atmospheric delay, and stadium multipath [1]. Prior work in football analytics treats (i) as a brute-force scan over candidate offsets (Hungarian linear assignment, movement-vector cosine similarity, or quartic kernel density estimation), leaves (ii) to a separate one-shot manual homography from four pitch keypoints, and either ignores (iii) or estimates it post-hoc per player. This costs tens of minutes of compute per match and never closes the loop between time alignment, sensor calibration, and GPS-side error. We recast the three preprocessing stages as a single end- to-end differentiable optimisation. Linear interpolation between adjacent precomputed GPS heat maps turns the time offset t into a learnable scalar; a differentiable affine warp of the video heat map captures the residual perspective error of the manual homography in a six-DoF matrix M ; and a differentiable shift of the GPS heat map by a low-degree polynomial b(g) absorbs the slowly varying team-wide GPS positional drift driven by satellite geometry, atmospheric delay and stadium multipath. All three are recovered jointly by stochastic gradient descent on the one-sided KDE residual that defines the strongest brute-force baseline. We additionally analyse the identifiability of (t, M, b) and show that the time–bias direction admits a first-order ambiguity that is broken by the bias regulariser. On eight professional football matches with manually verified ground-truth offsets, the proposed method beats every brute-force baseline (Hungarian, KDE, movement-vector field) on both mean absolute error and ±1-frame success rate at ∼3−9× lower wall time per match, outperforms 1-D cross-correlation baselines (motion-energy and phase-only correlation) by orders of magnitude, and additionally produces a calibrated residual perspective and a per-receiver GPS bias trajectory that no prior synchronization method provides — the very three quantities that downstream GPS–video sensor fusion pipelines [1] consume. We further validate the method on the publicly available SoccerNet GameState-2024 dataset under three regimes of increasing structural noise; on the regime that synthesizes the K-League acquisition profile, only the proposed method retains a usable success rate (80% within ±120 ms vs 1–21% for the centroid and brute-force baselines).
  </div>
</details>
