---
title: "Semantic Segmentation under Adverse Conditions: A Weather and Nighttime aware Synthetic Data-based Approach"
collection: publications
permalink: /publication/Semantic_Segmentation_under_Adverse_Conditions_A_Weather_and_Nighttime-aware_Synthetic_Data-based_Approach_BMVC_2022
excerpt: ''
date: 2022-11-21
venue: 'The British Machine Vision Conference (BMVC)'
---
**Abdulrahman Kerim**, Felipe Chamone, Washington Ramos, Leandro Soriano Marcolino, Erickson R Nascimento, Richard Jiang

<p align= "justify">

Recent semantic segmentation models perform well under standard weather conditions and sufficient illumination but struggle
with adverse weather conditions and nighttime. Collecting and annotating training data under these conditions is expensive,
time-consuming, error-prone, and not always practical. Usually, synthetic data is used as a feasible data source to increase
the amount of training data. However, just directly using synthetic data may actually harm the model's performance under normal
weather conditions while getting only small gains in adverse situations. Therefore, we present a novel architecture specifically
designed for using synthetic training data for domain adaptation. We propose a simple yet powerful addition to DeepLabV3+ by using
weather and time-of-the-day supervisors trained with multi-task learning, making it both weather and nighttime aware, which improves
its mIoU accuracy by 14 percentage points on the ACDC dataset while maintaining a score of 75% mIoU on the Cityscapes dataset.
Our code is available at
<a href="https://github.com/lsmcolab/Semantic-Segmentation-under-Adverse-Conditions"> https://github.com/lsmcolab/Semantic-Segmentation-under-Adverse-Conditions</a>.
</p>

  <div style="text-align: center">
         <img width="400" src="images/logos/bmvc-2023.png" width="150" >
  </div>

    <div style="text-align: center">
         <img width="400" src="images/Qualitative_Results_BMVC2022.png" width="150" >
  </div>


paperurl: [https://bmvc2022.mpi-inf.mpg.de/0977.pdf](https://bmvc2022.mpi-inf.mpg.de/0977.pdf)

